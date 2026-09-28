JeevSetu Master Integration — Sections 1–5 — Sequential Build

BASE: Sections 1–4 master integration.
ADDED: Section 5 Past Medical History.

ARCHITECTURE:
1. Sections 1–3 run first.
2. Section 4 Family History follows inside the same master index.
3. Section 4 does NOT generate a clinical note.
4. At the end of Section 4, the patient is explicitly asked whether they want to add any extra information.
5. Section 5 Past Medical History then opens inside the same master index.
6. Section 5 does NOT generate an independent clinical note.
7. At the end of Section 5, its final confirmation/additional-information flow is completed.
8. Only then is ONE Master Clinical Note generated containing Sections 1–3 + Section 4 + Section 4 extra information + Section 5.
9. Section data and the master note are saved locally.

NEXT ITERATION:
Section 6 can be appended to this same master index. Section 6 should not generate an independent clinical note; the single Master Clinical Note should be generated only after the final section.
