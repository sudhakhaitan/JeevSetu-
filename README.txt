JeevSetu — Section 17 — FINAL CORRECTED — GitHub Ready

This build separates Section 17 into appropriate branches:
1. Female: menstrual and menopause history, followed by pregnancy/obstetric/fertility history.
2. Male: sexual/urinary/reproductive concerns and male fertility history.
3. Other / not stated: only relevant reproductive/sexual/fertility questions.

Important fixes:
- Male patients are NOT asked menstrual, menopause, pregnancy, breastfeeding, or female obstetric questions.
- Pregnancy history starts with the simple question “क्या आपको कभी pregnancy हुई है?”.
- Pregnancy outcomes are captured in a single table with a dropdown (Normal delivery, Caesarean, Miscarriage, Stillbirth, Termination/abortion, Ectopic, ongoing, other).
- The table replaces repetitive outcome questions.
- Conditional complication questions are asked only when a complication is reported.
- “Any further information” is a real text field and stores the patient's response.
- Current pregnancy possibility creates a clinician flag when Yes or uncertain.
- index.html is at ZIP root for GitHub Pages.
