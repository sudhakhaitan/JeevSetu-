JeevSetu v0.1 — Build 3.9 FIXED V2-5-16 FRESH

Change in V2-5-16:
- Isolated the doctor-facing Clinical Note Preview formatter from Structured HPI.
- Structured HPI now displays the original stored patient answers and is not passed through clinicalEnglish().
- Clinical Note Preview alone uses the existing local formatter + optional BHASHINI fallback.
- No changes to Hindi questions, voice input, answer storage, or BHASHINI adapter.
- Duration cleanup remains in the Clinical Note formatter (e.g. "10 days with/from" -> "10 days").
