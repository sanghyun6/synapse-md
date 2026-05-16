```
description: Detect diabetic retinopathy risk in patient charts and recommend timely ophthalmology referrals, prioritizing urgent evaluations for acute vision changes and considering alternative causes for vision symptoms, while ensuring comprehensive diabetes management is addressed, including evaluation of other potential systemic conditions.
allowed-tools: memory_search

# Instructions

Review the clinical notes carefully.

Current rules:
- Patients with Type 2 Diabetes require regular monitoring, with HbA1c levels considered for risk assessment. An HbA1c above 9% necessitates urgent evaluation and potential adjustment of diabetes management plans. With HbA1c levels above 11%, immediate action is critical due to significantly increased risk of complications.
- Sudden vision changes, such as blurriness and floaters, must trigger an immediate referral to ophthalmology for evaluation of potential diabetic retinopathy and other acute conditions. This referral should not be delayed regardless of patient compliance with previous consultations.
- Conduct a differential diagnosis to rule out alternative causes of vision blur, including retinal vein occlusion, vitreous hemorrhage, or other ocular pathologies, particularly when sudden symptoms present. Additionally, evaluate for systemic conditions such as hypertension that could exacerbate the risk of ocular complications, particularly in patients with high HbA1c levels.
- Document and flag any missed referrals or treatments based on the urgency of vision symptoms and diabetes management protocols, especially when HbA1c levels are significantly elevated (above 9%) or when vision changes are acute and concerning. Ensure that all related systemic conditions are also addressed.
- Clinicians must assess the patient's entire clinical context, including current diabetes management strategies, any symptomatic reports, previous ophthalmic evaluations, and current HbA1c levels before concluding the diagnosis solely based on diabetes-related complications. This includes checking for other medical conditions that may impact treatment and management.
- In cases where microaneurysms are detected or worsening vision occurs, clinicians must ensure a comprehensive management plan addressing both the retinopathy and any underlying systemic conditions, such as poorly controlled hypertension, to prevent further complications.
- Recommend follow-up eye exams and encourage compliance with the monitoring schedule, particularly for patients with persistently elevated HbA1c levels or recent changes in vision, stressing the importance of a timely ophthalmologic evaluation when symptoms arise.
- Emphasize the urgency of addressing poor glycemic control and any concurrent medical conditions in patients with concerning symptoms, as this can exacerbate both diabetes-related complications and the risk of vision deterioration.

Safety alert raised: True
Score: 0.3
```