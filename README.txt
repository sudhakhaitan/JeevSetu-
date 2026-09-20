JeevSetu v0.1 — Build 3.9

Purpose: Hindi voice-first patient interaction with an English doctor-facing Clinical Note Preview.

Build 3.9 FIXED changes:
- Patient questions and Hindi voice interaction are unchanged.
- Doctor-facing Clinical Note Preview is generated in English.
- Structured HPI continues to preserve the patient’s original Hindi answers.
- HTTPS / microphone / Hindi speech diagnostics are retained.

Deployment:
Upload the contents of this build (especially index.html) to the GitHub Pages repository.
Do not open the ZIP directly for voice testing; use the HTTPS GitHub Pages URL.

- Clinical Note fallback corrected: the doctor-facing note no longer displays the generic Hindi-translation warning as the normal output. Common Hindi clinical phrases are converted to English, while original Hindi remains in Structured HPI.
- V2-5-4-FRESH: Expanded the English clinical interpretation engine with sentence-level Hindi clinical phrases, common variants, vocabulary rules, and a strict no-Devanagari doctor-note barrier. Hindi patient interaction remains unchanged.

- V2-5-4-FRESH: Rebuilt the Clinical Note translation function from the source
  rather than relying on the previous fallback behavior. The patient-facing
  Hindi flow is unchanged. The doctor-facing note remains English-only, while
  the Structured HPI retains the original Hindi response.
