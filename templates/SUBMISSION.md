# Synapse MD — Submission

## Idea
A self-evolving medical knowledge wiki that breaks down 
department silos in hospitals. Doctors input charts as usual. 
AI agents connect fragmented records across departments, 
detect hidden patterns, and automatically update a wiki 
that gets smarter with every case.

## Self-improvement Loop
1. Doctor inputs clinical notes → stored in Redis session memory
2. Cognee distills notes into permanent knowledge graph
3. Three agents debate: Connector links cross-department patterns,
   Skeptic validates statistically, Linter checks ADA 2024 guidelines
4. Linter scores the run — missing referral = low score (0.3)
5. SkillRunEntry records feedback → Cognee proposes SKILL.md rewrite
6. improve_skill(apply=True) upgrades the diagnostic rules
7. Wiki confidence score rises with each case accumulated

## Before/After Evidence
- Run 1: Wiki v18, Confidence 64%, basic diabetes monitoring rules
- Run 2: Wiki v19, Confidence 74%, ophthalmology referral recommended
- Run 3: Wiki v20, Confidence 81%, ADA 2024 §4.2 ALERT triggered

## Tech Stack
- Frontend: Next.js
- Backend: FastAPI
- Memory: Redis (session) + Cognee (permanent knowledge graph)
- AI: OpenAI GPT-4
- Skills: my_skills/diabetic-retinopathy/SKILL.md
