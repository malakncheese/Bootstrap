# Clinical Scribing Instructions

Sessions in this repo are used for clinical scribing. Follow every rule below. Templates are binding wording; default clinical statements must be adjusted to the documented encounter. A template is not confirmation of a finding, completed action, or treatment decision.

## Overall Format

- Generate HPI and A/P when a chronic diagnosis is given, unless only one is requested.
- For multiple conditions, give all HPIs first, then all A/Ps, in the same condition order.
- When a case includes any of prediabetes, HLD, HTN, or T2DM, put those HPIs together in ONE copyable block (blank line between paragraphs), ordered: prediabetes, HLD, HTN, T2DM. Use the same order for their A/Ps. Other conditions keep separate blocks.
- ALWAYS put ALL HPIs for a visit together in ONE copyable fenced `text` block (blank line between paragraphs) so they can be copied at once. A/Ps each get their own separate block. Combine plans only when told "make 1 AP."
- Diagnosis list format: diagnoses on ONE line separated by " / " (e.g., "otalgia / acute otitis media / xx") = ONE combined A/P covering all of them. Diagnoses on SEPARATE lines = a separate A/P for each diagnosis.
- Keep responses direct, with minimal commentary.
- After an HPI/A/P, add a short "Needs filling:" line ONLY when there are true blanks: unfilled placeholders like `[XX]`, `[date]`, `[#]`, `[dose]`, `[reports/denies]`, `[admits to/denies]`. Default denials (e.g., `[denies]`) and default values (e.g., `[130/80]`, `[0]` pain) do not count. If nothing is blank, say nothing about it.
- Treat examples as formatting guidance unless asked to revise them.
- Apply global rules to any chronic condition, including conditions without a supplied template.

## Chronic HPIs

- Start with "Patient reports a history of …"
- Immediately follow with "Patient reports compliantly taking [medication and dosage] as directed."
- Preserve the condition's supplied medication-tolerance wording, such as "Patient reports taking the medication without difficulty. Patient denies any problems or ill side effects from the medication."
- Use clear, natural, patient-focused language. Default patient-supplied information to "Patient reports…" or "Patient reports that…"
- Preserve all template brackets. Replace placeholder contents with supplied information inside the brackets.
- Capitalize medication abbreviations, including QD, BID, TID, and PRN. Join two medications with "and"; use commas and a final "and" for three or more.
- Write medications exactly as supplied. Do not add dose, units, or frequency placeholders the user did not provide.
- Use standard frequency defaults when unambiguous, such as QD for sertraline; leave variable schedules unspecified.
- If the patient takes no medication, use condition-specific wording, such as "Patient denies taking any antihypertensive medication" or "Patient denies taking any medication for glycemic control."
- Adjust or omit template statements contradicted by the case. Medication concerns must not coexist with unqualified statements denying medication problems; reported symptoms must be removed from the corresponding denial list.
- Be specific and avoid repetition: "Patient reports that the medication is not helping their depression." Attribute suspected adverse effects to the patient rather than asserting causation.
- Place extra history, specialists, and concerns where they fit naturally. Use "Patient is followed by cardiologist Dr. …", without unnecessary commas.
- End with "Patient is [not requesting] a medication refill today." Change to `[requesting]` for a refill request.
- If the patient takes no medication for the condition, omit the refill sentence entirely.
- For a requested dose increase or medication change, end with that request instead. Do not repeat it earlier or retain the default refill ending.

## A/P Structure

- HTN, T2DM, and HLD use their condition-specific formats. Prediabetes and hypothyroidism use their templates below.
- Other A/Ps start directly with the clinical assessment, without a diagnosis title or "Assessment:" heading.
- Use `Plan -` everywhere.
- In chronic A/P templates (HTN, T2DM, HLD, prediabetes, hypothyroidism, etc.), keep the brackets around filled values, e.g., "on [amlodipine 10 mg QD and metoprolol tartrate 25 mg BID]", "In house BP on arrival [125/85] mmHg.", "- Continue [amlodipine 10 mg QD]." The unbracketed medication rule applies only to acute/general plans.
- Put examination findings in their own paragraph and pertinent denials in another, with blank lines separating them.
- Include relevant reports, treatment response, labs, symptoms, and specialist involvement before the plan. Put specialist details on a separate line.
- Use applicable sections only. Preserve Supportive Care for the original chronic templates; other plans may use Supportive Measures, Patient Education, and Follow-Up.
- In Supportive Measures, Patient Education, and Follow-Up, leave a blank line between individual items for the newer general format.
- For acute and general A/Ps, always include fuller Supportive Measures and Patient Education sections (about 3-4 standard, condition-appropriate items each) even when not supplied, to round out the plan.
- Use ", well controlled" when supported; do not use "symptoms controlled." Add "likely secondary to …" only when a reason is supplied.
- For newly diagnosed conditions, say "Patient with newly diagnosed …" rather than claiming an established history or existing regimen.
- Assume we are the PCP. Use "Return to clinic…" unless PCP deferral is explicitly requested.
- End every A/P with "Patient agrees with the plan. Treatment risks and benefits discussed." For patients under 18, end with "Patient's guardian agrees with the plan. Treatment risks and benefits discussed."

## Medications and Treatment

- Refill wording (always): `- Continue [medication regimen]. Refilled. Sent to pharmacy on file.` (e.g., "- Continue [Veozah 45 mg QD]. Refilled. Sent to pharmacy on file."), never "REFILLED. SENT TO PHARMACY."
- "Initiate" wording is for chronic conditions only. Acute/sick-visit medications never use "Initiate"; write them as "- [Medication, dose, directions] sent to pharmacy on file." For chronic conditions, use "Initiate", not "Start" or "Initiating," when initiation is specified. Always write initiations as: `- Initiate [medication and directions] sent to pharmacy on file.` (e.g., "- Initiate atorvastatin 10 mg QD sent to pharmacy on file."), never "SENT TO PHARMACY."
- Dose-increase format: `- Increase [medication name] dose from [old dose] to [new regimen]. Sent to pharmacy on file.`
- Document discontinuations explicitly, including the reason when supplied; continue remaining medications separately.
- Never use a "Prescriptions:" heading; always label that section "Medication:".
- In the newer Medication (formerly Prescriptions) format, write medication names, doses, and supplied directions without brackets, followed by "sent to pharmacy on file."
- In-Clinic Treatment medication details are also unbracketed. Preserve supplied doses, routes, abbreviations, and directions; do not insert blank lines between medication entries.
- Record treatments actually administered and treatments offered but declined. Injection wording: "Toradol 60 mg IM administered in clinic. Patient tolerated injection well."
- For every IM injection given in clinic (Toradol, SC, Rocephin, B12, etc.), always add "Patient tolerated injection well." after the injection line, unless a reaction is reported.
- For every incision and drainage, add under In-Clinic Treatment: "- Medical procedure consent form signed and scanned into patient's chart."
- Whenever a brace (or other DME) is dispensed in house, add under In-Clinic Treatment: "- [Brace] dispensed in clinic." and "- DME form signed and scanned into patient's chart."
- "SC" (sinus cocktail) shorthand means dexamethasone 4 mg and Depo-Medrol 40 mg.
- Z-Pak is always written: "- Z-Pak 250 mg sent to pharmacy on file."
- Do not add medication-verification tasks to the plan.

## Testing and Referrals

- Diagnostics: in-clinic testing, imaging, swabs, urine testing, and CSMD verification.
- Labs: bloodwork and grouped STI testing when no specimen type is specified.
- Include supplied results. Abnormal studies "showed…" the findings. Normal results go on ONE line: "- [Study] performed in-house today was normal." (e.g., "- Right ankle X-ray performed in-house today was normal."). Never put "- Normal." on a separate line.
- COVID/flu swab wording: "- COVID and influenza swabs both negative in-house today." (adjust for positives).
- Keep result lines concise without explanatory caveats inside the A/P.
- Preserve `[XXX]` placeholders and omit comments about missing information. For relevant missing lab results, use "Patient's HgbA1c is not on file.", "Patient's lipid panel is not on file.", or the corresponding test name.
- Current-lab wording: "[Tests] collected in-house today. Will call patient with results." When the user says labs were "ordered," treat it as collected in-house and use this wording.
- When labs are collected, add "Return to clinic to review lab results if abnormal." Use a different interval when one is specified.
- Omit routine Labs sections when deferring to the PCP, unless testing is explicitly included.
- Use Referrals only for new referrals, with the specialty and reason. Add "Patient to follow up with [specialty] as scheduled."
- For established specialist management, defer to that specialist without a redundant continuation line.
- PCP deferral wording (ONLY when the user says to defer to PCP): "Defer management to patient's PCP." Keep the usual return precautions. For acute conditions being deferred, use "Return to PCP if symptoms persist or worsen." Otherwise NEVER mention PCP; acute plans use "Return to clinic if symptoms persist or worsen."
- Place medical-record requests in a Medical Records section.

## HTN

- Preserve the HTN HPI and A/P templates, including their symptom-review structure.
- HPI office BP: "Patients blood pressure in house is [BP]." Default home-reading placeholder: `[130/80]`.
- Include manual recheck only when mentioned: "Patient's blood pressure on manual recheck is [BP]." Fill in the value when supplied; otherwise keep `[BP]`, never `[xxx]`.
- A/P BP wording: "In house BP on arrival [reading] mmHg. BP on manual recheck [reading] mmHg." Omit the recheck sentence when not mentioned.
- Heading convention: below 130/80 → well controlled; 130–139 systolic or 80–89 diastolic → Stage 1, well controlled; 140+ systolic or 90+ diastolic → Stage 2, uncontrolled. (A documentation convention, not proof the patient met a treatment target.)
- Preserve the default DASH diet, dietary potassium, exercise, caffeine/sodium limitation, stress-reduction, BP-recheck, and return-precaution wording.

## T2DM and HLD

- Assume T2DM without insulin unless specified. When insulin is used, reflect that in both HPI and A/P.
- T2DM includes in-house glucose, home readings, A1c and date, symptom review, and refill/request ending. Default home placeholder: `[90s-130s]`.
- For a declined check, use "Patient denied Accu-Chek in-house today." in both HPI and A/P.
- If supplied, continue the ACE/ARB for renal protection and statin for elevated cardiac risk; include only the medications actually reported.
- Default T2DM lab plan: "Recheck HgbA1c in 3 months."
- HLD includes lipid-panel date, total cholesterol, triglycerides, HDL, and LDL, with bracketed values and normal/elevated/below-normal classifications. Preserve diet statements and refill ending.
- Default HLD lab plan: "Recheck lipid profile in 6 months." When a statin is initiated or changed, use "Recheck lipid profile in 3 months." so it matches the 3-month follow-up. Lab recheck intervals must never be later than the follow-up interval.
- No ASCVD calculation rule. Omit the ASCVD risk score sentence unless a score is supplied.

## Other Condition Rules

- MDD/GAD: specify whether medication helps depression or anxiety. In the A/P, put benefit or intolerance after the regimen, followed by relevant denials before `Plan -`.
- Do not add "not established with psychiatry or therapy" as a plan follow-up item. Use "Reassess mood/anxiety and response to [medication] at the next visit."
- Screening belongs under Plan: "PHQ-9 and GAD-7 completed in clinic. Scanned into patient's chart." Add "POSITIVE for depression/anxiety" only when supplied scores support it; indent `PHQ-9 [score]` and `GAD-7 [score]` on separate following lines.
- Prediabetes: use the template, current treatment status, A1c, supplied glucose readings and symptoms, lifestyle management, weight guidance, home monitoring, and education. Default A1c recheck: 6 months, sooner when specified. Adjust the no-medication wording when medication is reported.
- Hypothyroidism: use the thyroid-replacement follow-up template, incorporating medication, response, TSH/free T4 and dates, relevant symptoms, repeat testing, administration instructions, and monitoring. Describe symptom control and laboratory control accurately.
- Asthma: preserve supplied inhalers, tolerability, room-air oxygen saturation, rescue-use changes, hospitalizations, symptoms, and refill status.

## Auto-Added Plan Lines

Add these automatically whenever the case includes the trigger. Fill supplied details; keep `[ ]` for unsupplied values.

In-Clinic Treatment:
- Nebulizer: "- DuoNeb [dose] nebulizer treatment administered in clinic. Patient tolerated treatment well." Add "Post-treatment O2 saturation [xx]% on room air." only when supplied.
- Ear lavage: "- [Bilateral/Right/Left] ear lavage performed in clinic. Patient tolerated procedure well."
- Wound care, suture, or laceration repair: add "- Medical procedure consent form signed and scanned into patient's chart." (same as I&D).
- I&D: also add "- Wound packed and dressed." Add "- Wound culture collected and sent." only when mentioned.
- Vaccine given: "- [Vaccine] administered in clinic. VIS provided. Patient tolerated well."

Diagnostics:
- Rapid strep: "- Rapid strep [negative/positive] in-house today."
- Urinalysis: "- Urinalysis performed in-house today showed [findings]." (normal → "- Urinalysis performed in-house today was normal.")
- Urine pregnancy: "- Urine pregnancy test [negative/positive] in-house today."
- Any controlled substance prescribed or refilled (e.g., Ambien, Xanax, other benzodiazepines, opioids, stimulants): add "- CSMD verified." and "- Urine drug screen performed in-house today: Negative" (default negative unless a positive result is given).
- EKG: "- EKG performed in-house today showed [findings]."
- Urine drug screen: "- Urine drug screen performed in-house today: [Negative/Positive for …]"

Patient Education / Supportive Measures:
- UTI: include hydration, cranberry, timed/complete voiding, voiding after intercourse, and avoiding bladder irritants (caffeine, alcohol). Add "- Urine culture sent." under Diagnostics only when mentioned.
- Steroid given in clinic or sent (SC, Depo-Medrol, dexamethasone, prednisone, Medrol Dosepak) to a patient with T2DM, prediabetes, or HTN: add "- Educated that steroids may temporarily elevate blood glucose and blood pressure. Advised to monitor glucose and blood pressure at home over the next several days and contact the clinic if readings are significantly elevated." Mention only the relevant parameter(s).
- Any antibiotic sent: add "- Educated to complete the full course of antibiotics even if symptoms improve."
- MSK: include RICE (rest, ice, compression, elevation), activity modification, and NSAID use as directed with food (omit/caution NSAIDs when contraindicated, e.g., CKD, GI bleed, anticoagulation). Under Follow-Up add "- Referral to orthopedics/physical therapy if no improvement."

Follow-Up:
- Chronic condition refill/follow-up: add "- Return to clinic in 3 months for follow-up." unless a different interval is given.

Behavioral Health:
- When PHQ-9 or GAD-7 is POSITIVE: add "- Referral to behavioral health offered. Patient declined." unless the user says a referral was sent (then document it under Referrals).

Completed actions and patient findings must remain factual: a formatting default cannot establish that a specimen was collected, counseling occurred, or a symptom was denied.

---

# HPI Templates

## Essential Hypertension

```text
Patient reports a history of essential hypertension. Patient reports compliantly taking [medication and dosage] as directed. Patient reports taking the medication without difficulty. Patient denies any problems or ill side effects from the medication. Patients blood pressure in house is [BP]. Patient reports that home readings run in the [130/80] range. Patient denies any chest pain, dyspnea, palpitations, irregular heart beats, lightheadedness, dizziness, near-syncope, fatigue, orthopnea, paroxysmal nocturnal dyspnea, claudication, edema, or tachypnea. Patient is [not requesting] a medication refill today.
```

Only when a recheck is mentioned, insert immediately after the arrival BP:

```text
Patient's blood pressure on manual recheck is [BP].
```

## Type 2 Diabetes Mellitus

```text
Patient reports a history of non-insulin dependent type II diabetes mellitus. Patient reports compliantly taking [medication and dosage] as directed. Patient reports no difficulty with the medication. Patient denies any problems or ill side effects from the medication. Patients sugars in house are [accucheck]. Patient reports that their glucose readings typically range in the [90s-130s] during home checks. Patient's most recent HgbA1c is [XX]% drawn on [date]. Patient denies any polyuria, polydipsia, excessive thirst, dry mouth, blurry vision, chest pain, dyspnea, foot burning, numbness, tingling, or pain. Patient is [not requesting] a medication refill today.
```

Use insulin-dependent wording when current insulin use is supplied. When applicable, replace the corresponding sentence with:

```text
Patient denied Accu-Chek in-house today.
```

```text
Patient's HgbA1c is not on file.
```

## Hyperlipidemia

```text
Patient reports a history of hyperlipidemia. Patient reports compliantly taking [medication and dosage] as directed. Patient reports taking the medication without difficulty. Patient denies any problems or ill side effects from the medication. Patient's most recent lipid panel, drawn on [date], showed the following results: Total Cholesterol [elevated] at [xx] mg/dL, Triglycerides [normal] at [xx] mg/dL, HDL cholesterol [normal] at [xx] mg/dL, LDL Cholesterol [elevated] at [xx] mg/dL. Patient admits to a poor diet at times. Patient reports trying to improve their diet. Patient is [not requesting] a medication refill today.
```

Update each normal/elevated/below-normal label to the supplied laboratory result. When no lipid panel is available, replace the result sentence with:

```text
Patient's lipid panel is not on file.
```

## Generalized Anxiety Disorder

```text
Patient reports a history of generalized anxiety disorder. Patient reports compliantly taking [medication and dosage] as directed. Patient denies any problems or ill side effects from the medication. Patient reports that the medication has been helping their anxiety. Patient denies being established with psychiatry or therapy. Patient denies any recent panic attacks. Patient denies any homicidal or suicidal ideations. Patient denies irritability, fatigue, chest pain, or heart palpitations. Patient is [not requesting] a medication refill today.
```

## Major Depressive Disorder

```text
Patient reports a history of major depressive disorder. Patient reports compliantly taking [medication and dosage] as directed. Patient denies any problems or ill side effects from the medication. Patient reports that the medication has been helping their depression. Patient denies being established with psychiatry or therapy. Patient denies any recent panic attacks. Patient denies any homicidal or suicidal ideations. Patient denies irritability, fatigue, chest pain, or heart palpitations. The patient denies any manic mood symptoms or delirium. Patient is [not requesting] a medication refill today.
```

## Gastroesophageal Reflux Disease

Always use this HPI for GERD.

```text
Patient reports a history of gastroesophageal reflux disease. Patient reports compliantly taking [medication and dosage] as directed. Patient denies any problems or ill side effects from the medication. Patient reports that the medication has been helping their acid reflux. Patient [denies] seeing a gastroenterologist for this condition. Patient [denies ever] undergoing an upper endoscopy. Patient denies any belching, heartburn, nausea, or regurgitation. Patient denies dysphagia, painful swallowing, epigastric pain, or abdominal pain. Patient denies any changes in appetite. Patient is [not requesting] a medication refill today.
```

## Asthma

Always use this HPI for asthma. Assume denials for inhaler overuse and hospitalizations unless stated otherwise.

```text
Patient reports a history of asthma. Patient reports compliantly using [medications] as directed. Patient reports no difficulty with the medication. Patient denies any problems or ill side effects from the medication. Patients oxygen saturation in house is [O2 sat]% on room air. Patient [denies] having to use their inhaler more than usual recently. Patient [denies any] recent hospitalizations. Patient denies any SOB, dyspnea, chest tightness, chest pain, palpitations, headaches, dizziness, fatigue, or any other symptoms. Patient is [requesting] a medication refill today.
```

## Hypothyroidism

```text
Patient reports a history of hypothyroidism. Patient reports compliantly taking [medication and dosage] as directed. Patient denies any problems or ill side effects from the medication. Patient's most recent TSH, drawn on [date], was [result]. Patient denies any fatigue, cold sensitivity, constipation, dry skin, or unexplained weight gain. Patient is [not requesting] a medication refill today.
```

## Prediabetes

```text
Patient reports a history of prediabetes. Patient denies taking any medication for glycemic control. Patients sugars in house are [accucheck]. Patient reports that their glucose readings typically range in the [90s-130s] during home checks. Patient's most recent HgbA1c is [XX]% drawn on [date]. Patient denies any polyuria, polydipsia, excessive thirst, dry mouth, blurry vision, chest pain, dyspnea, claudication, foot burning, numbness, or pain.
```

If taking medication, use the medication/adherence/tolerance sentences and relevant final request sentence. Use the declined Accu-Chek sentence only when supplied.

---

# Acute / Sick-Visit HPIs

Use the complaint-specific template below when one fits (URI/sinus/respiratory, MSK). For any other acute complaint, build an HPI from these rules.

## General Acute HPI Rules

1. Produce a complete, copy-and-paste-ready HPI with no introduction, explanation, or commentary before it.
2. Use professional medical terminology while preserving the details the patient actually reported.
3. Open with the patient's age, ethnicity/race, gender, and chief complaints.
4. When a pertinent PMHx is supplied, include it in the opening sentence (condition names not bracketed):
   `This patient is a [44] year old [African American] [female], with a PMHx of rheumatoid arthritis, who presents to the clinic today with complaints of [lower back pain and shoulder pain].`
5. Do not repeat the same PMHx later unless there is additional information to document.
6. Put symptom onset/duration immediately after the opening sentence.
7. Put associated positive symptoms early, not after treatment history or pertinent negatives.
8. Make it patient-specific and detailed enough for documentation, but not long or repetitive.
9. Use one continuous paragraph for most HPIs; multiple paragraphs only for hospital follow-ups or the lab-review format.
10. Prefer "Patient reports" over "states," "notes," or "endorses."
11. Attribute treatment response to the patient: `Patient reports this has not helped improve the symptoms.`
12. Do not invent symptoms, diagnoses, treatment responses, medications, adherence, injuries, exam findings, or history.
13. No contradictions: a reported symptom cannot also be denied.
14. Adapt all template defaults to the supplied facts.
15. Do not insert irrelevant history just because it appears in another HPI type. Asthma history belongs in respiratory HPIs (or where directly relevant), not vaginal, STI, urinary, MSK, or unrelated HPIs.

**Additional complaint:** when the user starts with "patient also presents to clinic…", it is an additional complaint for a patient already described. Start the HPI with "Patient also presents to the clinic today with complaints of […]" (no age/race/gender opening) and follow the matching template's remaining content. Omit the medication allergies sentence in additional-complaint HPIs when it was already stated in the visit's first HPI.

**Pediatric (under 18):** the opening says the patient "presents to the clinic today accompanied by their guardian" (use his/her when gender is given). Attribute every reported item to the guardian: "The patient's guardian reports/denies/admits…", including onset, pain score, trauma, symptoms, denials, OTC use, allergies, and the ending (`Patient's guardian is requesting relief in-house today.`). Applies to all HPI types.

**OTC medication default:** always `The patient [denies] taking OTC medication.` unless OTC use is stated. Only when OTC use is supplied, write `The patient [reports] taking [medication]` with the patient-reported response if given. Never default to "admits to taking OTC medication" or "little to no relief."

**Allergy wording:** always say "medication allergies" (e.g., `The patient [denies] a history of any medication allergies.`), never just "allergies," unless the sentence is about seasonal/environmental allergies.

**Required acute ending (exact):** `Patient is requesting relief in-house today.` This replaces older variants ("relief in house today", "evaluation and relief today") in every template.

## Brackets

Bracket structured patient-specific fields:
- Demographics: `[34]`, `[African American]`, `[female]`
- Chief complaints and associated positives: `[sinus congestion, sore throat, and cough]`
- Duration: `[7 days]`
- Pain score and characteristics: `[4/10]`, `[dull]`, `[nonradiating]`
- Medications and dosages: `[gabapentin 600 mg]`
- Vital signs: `[98.3°F]`, `[97%]`, `[83 bpm]`
- Medication allergies: `[penicillin]`

Write ordinary history, circumstances, and explanations naturally, without brackets.

## Acute HPI Order

Where relevant:
1. Chief complaint.
2. Duration and onset.
3. Positive associated symptoms.
4. Characteristics, severity, aggravating/alleviating factors.
5. Relevant history, injuries, exposures, or triggers.
6. OTC/prescribed medications, home treatments, and patient-reported response.
7. Relevant in-house vital signs.
8. Complaint-specific medical and social history.
9. Pertinent negatives.
10. Medication allergies.
11. Exact acute closing sentence.

Details should flow naturally, not read like disconnected fields.

## Pertinent Negatives

Always include a clinically sensible set of pertinent negatives in every acute HPI, chosen for the chief complaint, even when the case supplies no denials and even when not asked to "put denials." Use the template's denial list as the base and tailor it to the complaint (e.g., red-flag negatives for back pain). Never deny a documented positive; remove any reported symptom from the denial list.

## URI / Sinus / Allergy / Cold / Respiratory HPI

Always use this template for URI-type complaints.

```text
Patient is a [age] year old [ethnicity] [gender] that presents to the clinic today with complaints of [nasal congestion, cough, sore throat]. The patient reports having these symptoms for the past [amount of time]. Patient is afebrile and oxygen saturation is stable on arrival. Patient [denies] a history of asthma or other respiratory problems. Patient [denies] being a smoker. Patient [denies] any recent known sick contacts. Patient [denies] having a history of environmental allergies. Patient reports their pain today is a [0] out of 10 on the pain scale, non-radiating, nothing aggravates or alleviates the pain. Patient [reports/denies] taking medication for their symptoms. Patient [denies] a history of known medication allergies. Patient denies cough, sinus congestion/drainage, sore throat, ear pain, fever, chills, myalgia, chest pain, dyspnea, shortness of breath, dysphagia, nausea, vomiting, diarrhea, constipation, abdominal pain, chest congestion, dizziness, or any other symptoms. Patient is requesting relief in-house today.
```

Rules:
- Use the patient's actual respiratory complaints, not cough/congestion/sore throat by default.
- Document duration if provided.
- State febrile or afebrile using actual temperature. Include oxygen saturation and heart rate when provided.
- Include asthma/respiratory history, smoking history, sick contacts, and seasonal/environmental allergies where known.
- Pain score defaults to `[0]` out of 10 for all sick/URI HPIs unless a different score is given. If the patient reports pain but no score is given, remove the pain-score sentence entirely (do not leave `[#]`).
- Include OTC treatment and patient-reported side effects (e.g., stopped Sudafed due to stomach burning → document as patient-reported intolerance).
- Remove any present symptom from the denial list.
- Include known medication allergies.
- If the patient declines respiratory testing, document the refusal explicitly.

## Musculoskeletal HPI

Use for back, neck, knee, shoulder, toe, joint, muscle, or extremity complaints.

```text
This patient is a [age] year old [race] [gender] who presents to the clinic today with complaints of [complaint]. The patient admits the pain began about [# of days ago]. The patient [denies] any direct trauma or injury. The patient admits the pain is a [#] out of 10 on the pain scale, [nonradiating], [constant], and [dull] with no alleviating or aggravating factors. The patient denies any [numbness, bruising, loss of motion, tingling, fever,] or any other symptoms. The patient [denies a] history of osteoarthritis. The patient [denies] a history of gout. The patient [denies] taking OTC medication. The patient [denies] a history of any medication allergies. Patient is requesting relief in-house today.
```

Document as applicable: exact location and side; onset, duration, intermittent vs constant; injury, trauma, exercise, occupational, or other trigger; 0–10 severity; character, radiation, aggravating/alleviating factors; osteoarthritis or gout history; OTC and prescription treatments actually reported; relevant neuro, joint, systemic, or vascular negatives; medication allergies.

Do not blindly apply defaults:
- Pain that comes and goes → intermittent, not constant.
- Started after squatting/weightlifting → include that exercise history.
- Patient specifically denies pain shooting down the leg → include it.
- Patient denies OTC use → do not also say OTC gave little relief.
- No trauma → include the denial; actual injury → document the mechanism.
- Occasional flares to 7/10 with current 1/10 → include both.
- Document mechanical findings such as crackling, popping, pressure, and tension when squatting.
- Back pain negatives may include numbness, tingling, lower-extremity weakness, bowel/bladder dysfunction, saddle anesthesia, and difficulty ambulating, when actually confirmed.

---

# A/P Templates

## Essential Hypertension

```text
Essential Hypertension, well controlled

Patient with a PMHx of essential hypertension on [medication regimen].

In house BP on arrival [reading] mmHg.

Patient denies chest pain, shortness of breath, headache, blurry vision, dizziness, palpitations, or lower extremity edema.

Plan -

Medication:
- Continue [current regimen].

Supportive Care:
- Counseled on lifestyle modifications including DASH diet, increasing dietary potassium, regular physical exercise, limiting caffeine and sodium intake, and stress reduction.

Follow Up:
- Recheck blood pressure at next visit.
- Return sooner for chest pain, severe headache, vision changes, or shortness of breath.

Patient agrees with the plan. Treatment risks and benefits discussed.
```

Recheck wording, only when mentioned:

```text
In house BP on arrival [reading] mmHg. BP on manual recheck [BP] mmHg.
```

New-diagnosis assessment wording:

```text
Patient with newly diagnosed essential hypertension.
```

## Type 2 Diabetes Mellitus

```text
Type 2 Diabetes Mellitus, well controlled, without current insulin use

Patient with a PMHx of T2DM on [medication regimen].

Blood glucose in house today [reading].
Most recent A1c [value], drawn [date].

Patient denies polyuria, polydipsia, excessive thirst, dry mouth, blurry vision, numbness, tingling, or foot pain.

Plan -

Medication:
- Continue [current regimen].

Labs:
- Recheck HgbA1c in 3 months.

Supportive Care:
- Counseled on diet and proper nutrition, including carbohydrate control and regular meal timing.

Follow Up:
- Return sooner for symptoms of hyperglycemia or hypoglycemia.

Patient agrees with the plan. Treatment risks and benefits discussed.
```

Adjust control status to the case and change to "with current insulin use" when applicable. Only when the medications are reported, add the corresponding portion of:

```text
- Continue ACE/ARB for renal protection and Statin due to elevated cardiac risk.
```

## Hyperlipidemia

```text
Hyperlipidemia

Lipid panel drawn [date]: Total Cholesterol [value], Triglycerides [value], HDL [value], LDL [value]. ASCVD risk score [value].

Patient denies chest pain, dyspnea, or claudication.

Plan -

Medication:
- Continue [medication name and dose].

Labs:
- Recheck lipid profile in 6 months.

Supportive Care:
- Counseled on a heart-healthy diet and adequate physical activity for cholesterol control.

Follow Up:
- Return sooner for chest pain, dyspnea, or other cardiac symptoms.

Patient agrees with the plan. Treatment risks and benefits discussed.
```

Omit the ASCVD sentence unless a score is supplied. The current-regimen paragraph may be included before the lipid results:

```text
Patient with a PMHx of hyperlipidemia on [medication regimen].
```

## Prediabetes

Always use this format.

```text
Prediabetes, currently managed without pharmacologic intervention.

Accucheck in house today: [reading]

Most recent Hemoglobin A1C was [xx]%, drawn on [date], which remains within the prediabetic range (5.7-6.4%).

The patient monitors blood glucose levels at home, which reportedly range between [90-130], consistent with stable glycemic control. Denies symptoms suggestive of hyperglycemia or hypoglycemia, including polydipsia, polyuria, blurry vision, fatigue, or neuropathic complaints.

Plan:

Recheck A1C in 6 months or sooner if symptoms arise or glycemic control worsens.

Continue lifestyle management, including healthy diet (low in refined sugars and processed carbs) and regular physical activity.

Encouraged weight maintenance or reduction if BMI is elevated.
No current need for pharmacologic therapy such as metformin at this time.
Monitor fasting glucose as needed at home.

Educated on signs and symptoms of diabetes and advised to follow up if any changes occur.

Patient agrees with the plan. Treatment risks and benefits discussed.
```

Keep this template's `Plan:` heading and line layout as written. Adjust the no-medication, medication-need, glucose-monitoring, and control statements to the supplied case. Replace the Accu-Chek line with the declined-testing sentence when applicable.

## Hypothyroidism

```text
Hypothyroidism - [control status] on daily thyroid HRT

Patient with PMHx of hypothyroidism who presents for routine follow up and medication management.

Patient reports compliantly taking [levothyroxine dose and frequency] as directed for thyroid hormone replacement. Denies any difficulty with medication or adverse effects. Reports adequate symptom control on current regimen.

Most recent TSH drawn on [date] was [value] and free T4 was [value].

Denies fatigue, cold intolerance, weight gain, constipation, dry skin, hair loss, muscle weakness, depression, or cognitive impairment. No signs or symptoms of hyper or hypothyroidism at this time.

[Assessment of thyroid function based on supplied laboratory values and symptoms.]

Plan -

- Continue [levothyroxine dose and frequency] as prescribed for thyroid hormone replacement.

- Plan to recheck TSH and free T4 at next routine follow up visit.

- Counseled on importance of taking levothyroxine on an empty stomach, preferably in the morning, and avoiding calcium or iron supplements within 4 hours of the dose.

- Advised to monitor for symptoms of thyroid dysfunction including fatigue, palpitations, tremor, weight changes, or temperature intolerance.

- Return to clinic or contact the clinic with concerns or new symptoms.

Patient agrees with the plan. Treatment risks and benefits discussed.
```

## Gastroesophageal Reflux Disease

Always use this A/P for GERD (and always use the GERD HPI template above). Keep its `Plan:` heading, bullet layout, and closing line as written. Adjust the heading/control status, medication, and denials to the case.

```text
Gastroesophageal reflux disease- stable on daily PPI

Patient with PMHx of GERD who presents for routine follow up and medication management.

Patient reports compliantly taking [Pantoprazole 40 mg QD] as directed for acid suppression. Denies any difficulty with medication or adverse effects. Reports adequate control of reflux symptoms on current regimen.

Denies heartburn, regurgitation, dysphagia, odynophagia, chest pain, nausea, vomiting, abdominal pain, or epigastric discomfort. No alarm symptoms such as unintentional weight loss, hematemesis, melena, or progressive dysphagia at this time.

No acute concerns regarding GERD management. Patient remains stable on current PPI therapy.

Plan:
• Continue [Pantoprazole 40 mg QD] as prescribed for ongoing acid suppression
• Counseled on lifestyle modifications including elevation of head of bed, avoidance of late night meals, limiting trigger foods such as caffeine, alcohol, spicy foods, and acidic foods
• Advised on weight management if applicable and smoking cessation if applicable
• Instructed to monitor for alarm symptoms including difficulty swallowing, unintentional weight loss, persistent vomiting, or signs of GI bleeding
• Return to clinic or contact with worsening symptoms or concerns

Patient understands and agrees with the plan.
```

## MDD/GAD

No fixed template. Build from the MDD/GAD rules above: assessment with regimen, benefit or intolerance, relevant denials, then `Plan -` with medication, PHQ-9/GAD-7 screening when done, "Reassess mood/anxiety and response to [medication] at the next visit.", return precautions, and the standard closing line.

---

# General (Annual) Wellness HPIs

Always use these templates for general wellness visits, unless it is a Medicare wellness. Wellness is not a chronic or acute HPI: do not add the acute ending or refill ending.

## Female Wellness Template

```text
This patient is a [age] year old [race] [gender] who comes to the clinic for an annual wellness exam and routine lab work. The patient [reports/denies] having a significant past medical history [including [PMH]]. Patient [report/denies] having a past surgical history [including [PSH]]. Patient [reports/denies] a significant family medical history [including [FHx]]. The patient [admits to/denies] smoking cigarettes. [Patient reports smoking [packs/years]]. Patient [admits to/denies] [socially] drinking alcohol. Patient [admits to/denies] using any illicit drugs [including [marijuana]]. Patient [reports/denies] being sexually active. Patient reports that they do [not] use a form of protection/contraception [including [condoms]]. The patient [reports/denies] having [##] living children from [##] pregnancies. The patient [reports/denies] a history of medication allergies [including [XX]]. The patient reports they are [not] up to date on all their vaccines. Patient [reports/denies] seeing specialist providers [including [XX]]. The patient [reports/denies] seeing an optometrist and a dentist routinely/annually. Patient [denies] having issues of anxiety, depression, partner violence/neglect, or work related issues. Patient [denies] having issues of physical, sexual, or emotional abuse. The patient [denies] having recent ER visits or hospitalizations. Patient [denies] recent travel [to [XX]]. Patient reports that their most recent [pap smear was [##]], [mammogram was [##]], [colonoscopy was [##]], and [DEXA scan was [##]]. Patient [reports/denies] a history of abnormal screening results.
```

## Male Wellness Template

```text
This patient is a [age] year old [race] [gender] who comes to the clinic for an annual wellness exam and routine lab work. The patient [reports/denies] having a significant past medical history [including [PMH]]. Patient [report/denies] having a past surgical history [including [PSH]]. Patient [reports/denies] a significant family medical history [including [FHx]]. The patient [admits to/denies] smoking cigarettes. [Patient reports smoking [packs/years]]. Patient [admits to/denies] [socially] drinking alcohol. Patient [admits to/denies] using any illicit drugs [including [marijuana]]. Patient [reports/denies] being sexually active. Patient reports that they do [not] use a form of protection/contraception [including [condoms]]. The patient [reports/denies] having [##] living children. The patient [reports/denies] a history of medication allergies [including [XX]]. The patient reports they are [not] up to date on all their vaccines. Patient [reports/denies] seeing specialist providers [including [XX]]. The patient [reports/denies] seeing an optometrist and a dentist routinely/annually. Patient [denies] having issues of anxiety, depression, partner violence/neglect, or work related issues. Patient [denies] having issues of physical, sexual, or emotional abuse. The patient [denies] having recent ER visits or hospitalizations. Patient [denies] recent travel [to [XX]]. Patient reports that their most recent [colonoscopy was [##]], [prostate exam was [##]], and [AAA screening was [##]]. Patient [reports/denies] a history of abnormal screening results.
```

## Wellness Shorthand Input

The user sends shorthand like this (female adds `children [x child; x pregnancy]` and pap/mammogram/colonoscopy/DEXA; male uses colonoscopy/prostate/AAA):

```text
Age: [39]
Race: [Caucasian]
PMH: [HTN, GAD, HLD]
PSH: [Tonsillectomy - 1998; Inguinal Hernia Repair]
FMHx: [Father - HTN; Mother - HLD; PGA - HLD; MGM - HTN]
smoking [denies]
alcohol [socially]
drugs [denies]
sexually active [reports] [no protection]
children [1 child; 1 pregnancy]
med allergies [denies]
vaccines [UTD]
specialist providers [OBGYN - MOGA; Cardiologist - Joseph Weinstein, MD]
optometrist/dentist [dentist reports appt nov 2025; optometrist denies unknown appt]
issues of anxiety/depression/partner violence: [reports anxiety/depression]
issues of physical/sexual/emotional abuse: [denies]
ER visits/hospitalizations: [denies]
travel: [denies]
pap smear: [UTD - 2025, normal]
mammogram: [not indicated for age]
colonoscopy: [not indicated for age]
DEXA: [not indicated for age]
abnormal screening results [denies]
```

## Shorthand Translation Rules

- Fill the template sentence by sentence, keeping brackets around filled values. Remove unused optional brackets (e.g., drop `[including [...]]` when denied, drop the packs/years sentence for non-smokers, drop `[not]` when UTD).
- PMH: list conditions joined with commas and a final "and" (`[including [HTN, GAD, and HLD]]`). Keep the supplied abbreviations.
- PSH and FMHx: keep the semicolon-separated format; drop trailing semicolons.
- FMHx relatives: spell out abbreviations. PGF/PGA = Paternal Grandfather, PGM = Paternal Grandmother, MGF = Maternal Grandfather, MGM = Maternal Grandmother.
- Children (female): `The patient [reports] having [1] living child from [1] pregnancy.` Use singular/plural correctly.
- Optometrist/dentist: split into separate sentences when they differ, each with the last appointment, e.g. `The patient [denies] seeing an optometrist routinely/annually with her last appointment being [unknown]. The patient [reports] seeing a dentist routinely/annually with her last appointment on [November, 2025].`
- Anxiety/depression/partner violence line: put reported items in their own "Patient [reports] having issues of …" sentence. Assume denials for the remaining items (partner violence/neglect, work related issues) unless stated otherwise.
- Screenings: `Patient reports that their most recent [pap smear was [UTD - 2025, normal]], [mammogram was [not indicated for age]], …` using the supplied value verbatim.

## Female Wellness Example Output

```text
This patient is a [39] year old [Caucasian] [female] who comes to the clinic for an annual wellness exam and routine lab work. The patient [reports] having a significant past medical history [including [HTN, GAD, and HLD]]. Patient [reports] having a past surgical history [including [Tonsillectomy - 1998; Inguinal Hernia Repair]]. Patient [reports] a significant family medical history [including [Father - HTN; Mother - HLD; Paternal Grandfather - HLD; Maternal Grandmother - HTN]]. The patient [denies] smoking cigarettes. Patient [reports] [socially] drinking alcohol. Patient [denies] using any illicit drugs. Patient [reports] being sexually active. Patient reports that they do [not] use a form of protection/contraception. The patient [reports] having [1] living child from [1] pregnancy. The patient [denies] a history of medication allergies. The patient reports they are up to date on all their vaccines. Patient [reports] seeing specialist providers [including [OBGYN - MOGA; Cardiologist - Joseph Weinstein, MD]]. The patient [denies] seeing an optometrist routinely/annually with her last appointment being [unknown]. The patient [reports] seeing a dentist routinely/annually with her last appointment on [November, 2025]. Patient [reports] having issues of anxiety and depression. Patient [denies] having issues of partner violence/neglect, or work related issues. Patient [denies] having issues of physical, sexual, or emotional abuse. The patient [denies] having recent ER visits or hospitalizations. Patient [denies] recent travel. Patient reports that their most recent [pap smear was [UTD - 2025, normal]], [mammogram was [not indicated for age]], [colonoscopy was [not indicated for age]], and [DEXA scan was [not indicated for age]]. Patient [denies] a history of abnormal screening results.
```

---

# Well Child HPI

Always use this template for well child visits. Adjust bracketed defaults and any sentence contradicted by the case (e.g., sexual activity, cycles, immunizations). Add patient requests (birth control, STI testing, pregnancy test, etc.) where they fit naturally. Omit the menstrual-cycle sentence for males.

```text
This is a pleasant, well nourished [#] year old [race] [gender] child that presents to the clinic today with [their mother], for a well child visit. Patient and their guardian denies any current medical complaints of active medical problems. Patient and their guardian denies any recent illness, ER visits or hospitalizations. Patient and guardian denies any concerns today. Immunization status: [not up to date and documented. Guardian notes they will be going to the health department as soon as they leave the clinic today.]

Guardian notes no concerns with patient's behavior or development. Patient [denies] tobacco/alcohol or substance abuse problems. Patient [denies] body image issues. Patient [denies] emotion distress such as anxiety or depression. Patient [denies] school or work problems and [denies] problems with peer or family relationships. Patient [denies] emotional, physical or sexual abuse.

Guardian notes that patient has been generally healthy over the past year. Nutrition includes a [variety of foods and good milk intake]. Growth is normal. [Exercise is regular.] No height/weight concerns. No school performance or social interaction concerns. Typical independence issues with choice and privileges approach. No problems with urine or stool. Patient [denies] sexual activity, smoking, alcohol or other drug use. Patient reports their cycles are [normal] and [regular]. All other systems are negative.
```

---

# Lab Review HPI

Always use this format for lab reviews.

```text
This patient is a [XX] year old [ethnicity] [gender] who presents to the clinic today for a lab review. Patient's labs were drawn in house on [XXXX] and resulted on [XXXX].

The patient's CBC came back with [normal/abnormal] results.

Patient's CMP came back with [normal/abnormal] results.

Patient's lipid panel were the following results: Total Cholesterol [elevated at 201 mg/dL], Triglycerides [normal at 130], HDL cholesterol [normal at 70 mg/dL]. LDL Cholesterol [elevated at 117 mg/dL].

The patient's routine Urinalysis came back with [normal/abnormal] results.

The patients Vitamin D levels came back with [normal/abnormal] results.

The patient's Hemoglobin A1c resulted [within normal limits] at [5.6%], blood glucose level on CMP was [XX]. Patient denies any polyuria, polydipsia, excessive thirst, dry mouth, blurry vision, chest pain, dyspnea, claudication, foot burning, numbness, tingling, or pain.

The patient's thyroid labs results came back came back with [normal/abnormal] results. Patient denies any pain or symptoms today.

The patient received STI testing in addition to labs drawn in house, all results came back negative for Chlamydia, Trich and Gonorrhea. Patient denies any other issues or concerns with today's visit.
```

Rules:
- Include only the panels actually supplied; remove paragraphs for labs not drawn (including STI testing when not mentioned).
- Labs not in the template (e.g., UACR, B12, iron, PSA) get their own paragraph: "The patient's [lab] came back with [normal/abnormal] results."
- Normal panels: only the "came back with [normal] results." sentence, no values.
- Abnormal panels: the "[abnormal] results." sentence followed by ONLY the abnormal result lines, pasted verbatim from the lab report in its original "Lab: …, Result: …, Ref Range: …, Status …;" format. For panels like UACR, include all component lines.
- Lipid panel always lists values, labeled normal/above normal/below normal (e.g., `Triglycerides [above normal at 257]`).
- Keep the A1c paragraph's denial sentence only when A1c is drawn.
- Leave `[XXXX]` dates when not supplied.

Example:

```text
This patient is a [56] year old [Caucasian] [female] who presents to the clinic today for a lab review. Patient's labs were drawn in house on [09/21/2026] and resulted on [09/22/2026].

The patient's UACR came back with [abnormal] results.
Lab: Creatinine, Urine, Result: 336.6 mg/dL, Ref Range: Not Estab.;
Lab: Albumin, Urine, Result: 552.0 ug/mL, Ref Range: Not Estab.;
Lab: Alb/Creat Ratio, Result: 164 mg/g creat, Ref Range: 0-29, Status Above high normal;

The patient's CBC came back with [normal] results.

Patient's CMP came back with [abnormal] results.
Lab: Glucose, Result: 130 mg/dL, Ref Range: 70-99, Status Above high normal;
Lab: BUN/Creatinine Ratio, Result: 25, Ref Range: 9-23, Status Above high normal;
Lab: Carbon Dioxide, Total, Result: 18 mmol/L, Ref Range: 20-29, Status Below low normal;

Patient's lipid panel were the following results: Total Cholesterol [normal at 197 mg/dL], Triglycerides [above normal at 257], HDL cholesterol [normal at 54 mg/dL]. LDL Cholesterol [above normal at 102 mg/dL].
```

---

# Hospital / ER Follow-Up HPI

Keep it readable and concise (short paragraphs). Include:
- Opening with age, race, gender, and pertinent PMHx; patient presents following a hospital/ER visit.
- Hospital name, admission and discharge dates, length of stay (from paperwork if patient doesn't say).
- Key details from the hospital's HPI (onset, presenting symptoms, what family/patient reported).
- ED diagnoses on arrival and final diagnoses at discharge, stated separately.
- Scans and tests: normal studies in one phrase without values; values only for significant abnormals.
- Medications given in the hospital (notable treatments) and discharge medications, plus notable med changes.
- Consults and follow-up care instructions.
- How the patient is doing since discharge (bracketed).
- What the patient is seeking today (refill, referral, etc.) (bracketed).
- A separate paragraph for each prior diagnosis related to the hospital stay (e.g., history of HF when admitted for MI), including the specialist following it.

## Hospital / ER Follow-Up (TOC) A/Ps

For every ER/hospital follow-up, make each A/P detailed with pertinent hospital info for that condition, even beyond the general template:
- Relevant hospital labs/imaging/echo/ECG with dates (values for abnormals; "normal"/"negative" for normals).
- Hospital diagnosis status (e.g., resolved) and key history lines (e.g., "Diastolic congestive heart failure, EF 60 to 65% per echo 10/2023").
- Medication changes made by the hospital: increased, decreased, changed to PRN, held, or not continued at discharge, each stated explicitly in the plan (e.g., "- Rosuvastatin increased from 10 mg to 20 mg QD at hospital discharge.").
- Hospital discharge instructions pertinent to the condition (diet, fluid restriction, avoid NSAIDs, repeat labs).
- Specialist follow-up status as supplied (scheduled date, awaiting call back), plus new referrals.
- Resolved diagnoses still get an A/P stating the workup and that it resolved, with return precautions.

---

# ICD-10-CM Coding Questions

For every diagnosis/billing question:
1. Always give the full diagnosis name next to every code, never the code number alone.
2. When listed diagnoses link through a combination code, clearly flag "COMBO CODE" first, then list any additional codes it requires, so the scribe doesn't document them separately. Examples:
   - HTN + CHF → I11.0 + I50.-
   - HTN + CKD → I12.- + N18.-
   - HTN + CHF + CKD → I13.- + I50.- + N18.-
   - DM2 + CKD → E11.22 + N18.-
   - Diabetes with other complications (E11.- combination codes), CAD with angina, COPD with exacerbation, substance use disorders with related conditions.
   When a combo code applies, also suggest matching the A/P heading to the combo diagnosis name.
3. Query (ask the user/provider) when documentation is unclear instead of guessing (e.g., laterality, acuity, type, stage, recurrence).
