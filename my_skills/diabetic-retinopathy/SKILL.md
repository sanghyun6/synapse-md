```yaml
description: Detect diabetic retinopathy risk in patient charts and recommend timely ophthalmology referrals, prioritizing urgent evaluations for acute vision changes and considering alternative causes for vision symptoms, while ensuring comprehensive diabetes management is addressed, including evaluation of other potential systemic conditions and medication interactions.

allowed-tools: memory_search

# Instructions

Review the clinical notes carefully.

Current rules:
- Patients with Type 2 Diabetes require regular monitoring, with HbA1c levels considered for risk assessment. An HbA1c above 9% necessitates urgent evaluation and potential adjustment of diabetes management plans. With HbA1c levels above 11%, immediate action is critical due to significantly increased risk of complications.
- Document the patient's diabetes duration, as this is crucial in evaluating the risk of complications, including diabetic retinopathy, and tailor management plans accordingly.
- Sudden vision changes, such as blurriness and floaters, must trigger an **immediate referral to ophthalmology** for evaluation of potential diabetic retinopathy and other acute conditions, including retinal detachment and vitreous hemorrhage. This referral should **not be delayed** regardless of patient compliance with previous consultations or absence of acute complaints at the current visit.
- Conduct a thorough differential diagnosis to rule out alternative causes of vision blur, particularly in patients with a history of visual disturbances. This should include assessment for acute conditions such as retinal vein occlusion, vitreous hemorrhage, and retinal detachment, as well as consideration of systemic conditions like poorly controlled hypertension that could exacerbate the risk of ocular complications.
- Ensure that a **comprehensive eye examination** is conducted for all patients with blurred vision, particularly those with HbA1c levels above 9% or ongoing symptoms. This examination must rule out potential complications and include evaluation for diabetic retinopathy, retinal detachment, and any systemic influences.
- Document and flag any missed referrals or treatments based on the urgency of vision symptoms and diabetes management protocols. Emphasize the importance of addressing both glycemic control and other complications in patients with concerning symptoms.
- Clinicians must assess the patient's entire clinical context, including current diabetes management strategies (e.g., Metformin dosage), medication reconciliation, any symptomatic reports (including subtle changes like floaters), previous ophthalmic evaluations, current HbA1c levels, and diabetes duration before concluding the diagnosis. This includes checking for other medical conditions that may impact treatment and management decisions.
- In cases where microaneurysms are detected or patients report worsening vision or concerning symptoms, implement a comprehensive management plan addressing both the retinopathy and any underlying systemic conditions, including poorly controlled hypertension. **Prompt referral to ophthalmology is critical** in these instances.
- Recommend follow-up eye exams annually for all patients with diabetes and urge compliance with the monitoring schedule, especially for patients with persistently elevated HbA1c levels or recent changes in vision.
- Emphasize the urgency of addressing poor glycemic control and any concurrent medical conditions in patients presenting with concerning symptoms, as this can significantly exacerbate both diabetes-related complications and the risk of vision deterioration. Prioritize patients with a history of hypertension and those not previously referred for ophthalmologic evaluation, particularly in the context of acute symptoms.
- Ensure that all history of missed referrals and previous evaluations, along with ongoing management of eye health and diabetes, are thoroughly documented in the patient's chart. This is crucial for continuity of care and clinical decision-making, especially in patients with elevated HbA1c and concerning ocular symptoms.
- Always check for the absence of prior ophthalmology referrals and evaluate the need for timely referrals based on the patient's clinical context and presentation to mitigate safety concerns.
- Perform medication reconciliation prior to any imaging or procedure requiring contrast, particularly in diabetic patients taking Metformin, to avoid critical interactions and assess risks like lactic acidosis. The absence of this step must be documented and addressed immediately, especially if the patient has an elevated HbA1c level.
- Acknowledge and resolve any inter-departmental conflicts regarding medication management, as this can impact the safety and effectiveness of pre-procedure evaluations and patient care.
- Any new symptoms, including subtle changes like floaters, should prompt reconsideration of prior evaluations and possible immediate referrals, even in the absence of acute complaints at the visit.
- Ensure that a comprehensive evaluation of potential cardiac and pulmonary causes of chest pain is completed prior to any high-risk procedures. Clinicians should assess renal function and involve Internal Medicine for clearance, especially in patients on renal-impacting medications like Metformin, to ensure safety prior to contrast administration.

Safety alert raised: True
Score: 0.3
```