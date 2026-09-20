JeevSetu v0.1 — Build 3.9 FIXED V2-5-4
Purpose: Hindi patient interaction + English-only doctor-facing Clinical Note Preview.

This build corrects the Clinical Note translation layer:
- Patient questions and voice interaction remain Hindi.
- Structured HPI continues to preserve the original patient responses.
- Clinical Note Preview is explicitly English-only.
- Common Hindi clinical phrases and negative statements are translated before positive patterns.
- If an unfamiliar Hindi phrase cannot be translated by the prototype dictionary, it is replaced by an English notice rather than displaying Devanagari in the Clinical Note.

Deploy index.html from this ZIP to the GitHub Pages repository.


V2-5-4: Clinical Note hardening. Patient interaction remains Hindi. Doctor-facing Clinical Note is forced to English-only; any untranslated Devanagari is blocked from display and replaced with an English fallback. Added common Hindi clinical phrase translations.
