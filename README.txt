JeevSetu v0.1 — Build 3.9 FIXED V2-5-19 FRESH

Change in V2-5-19:
- Used V2-5-18 as the baseline.
- Kept the patient-facing Hindi interaction and Structured HPI display unchanged.
- Kept changes confined to the doctor-facing Clinical Note formatter/translation path.
- Strengthened deterministic English handling for common HPI answers, including negative symptoms, previous treatment, pressure/rest/walking modifiers, and common "nothing specific" responses.
- BHASHINI is still used for unresolved Hindi phrases, but a BHASHINI response containing Hindi is no longer allowed to overwrite a valid local English translation.
- Duration cleanup remains: e.g. “10 दिनों से” -> “10 days”.
