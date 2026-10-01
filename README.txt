JeevSetu V2-5-81 — Section 12 + Sections 17–18 clinical-note repair

Changes in this build:
1. Section 12: added a fail-safe capture-phase click handler for dynamically rendered Yes/No controls and the Section 12 Extra Information Yes/No buttons. This prevents the previous non-responsive Yes-button path from being bypassed by stale/duplicate handlers.
2. Section 12 still saves its answers to localStorage and does not generate any intermediate Clinical Note.
3. Section 17: final Master Clinical Note now prints the actual patient-facing question text (for example, 17.1...) rather than internal field IDs such as m1/f1.
4. Section 17: final note uses the patient's saved/current sex to include only the applicable male or female branch and ignores stale non-applicable branch data.
5. Section 17: menstruation versus menopause questions are filtered from the saved answers using f1.
6. Section 18: final Master Clinical Note now prints the actual question text (18.1–18.10) rather than i1/i2... IDs. Conditional infertility questions are included only when 18.1 is Yes.
7. Section 19–20 and Section 21 logic is retained; Section 21 remains the final gate for the single Master Clinical Note.
8. Patient sex is additionally persisted in localStorage at the Section-1 completion gate so the final note does not depend only on a live page variable.
9. JavaScript syntax checked with Node.js after repair.

Important: This build changes the runtime/source logic. It is not merely a renamed copy of V2-5-80.
