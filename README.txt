JeevSetu Master Integration — Sections 1–6 — Sequential Build

BASE: Sections 1–5 master integration.
ADDED: Section 6 Allopathic / Medication History (from JeevSetu_Section6_ALLopathic_CAPTURE_FINAL_v13).

ARCHITECTURE:
1. Sections 1–3 run first.
2. Section 4 Family History follows inside the same master index.
3. Section 4 does NOT generate a clinical note.
4. At the end of Section 4, the patient is explicitly asked whether they want to add any extra information.
5. Section 5 Past Medical History then opens inside the same master index.
6. Section 5 does NOT generate an independent clinical note.
7. Section 5 now transitions directly to Section 6.
8. Section 6 Medication History is integrated into the same master index and does NOT generate an independent clinical note.
9. Section 6 captures allopathic medicines, discontinued medicines, self-restarting medicines, OTC/antibiotic use, Ayurvedic, herbal, vitamin, mineral and supplement products.
10. Allopathic medicine rows are read from the live form and retained when any clinical medication detail has been entered; missing medicine names are explicitly flagged for clinician verification.
11. At the end of Section 6, the patient is explicitly asked whether they want to add extra information.
12. Only after Section 6 extra-information confirmation is completed is ONE Master Clinical Note generated containing Sections 1–3 + Section 4 + Section 4 extra information + Section 5 + Section 6 + Section 6 extra information.
13. Section data and the master note are saved locally.

TESTING:
- Upload index.html to the GitHub Pages repository as the master index.
- Test sequentially with dummy data: Sections 1 → 2 → 3 → 4 → 4 Extra → 5 → 6 → 6 Extra → Master Clinical Note.
- Verify that no clinical note appears at the end of Section 4, Section 5, or Section 6.
- Verify that all Section 6 medication details appear in the final Master Clinical Note.
- Verify that an allopathic medicine row with clinical details but no medicine name is retained and marked for clinician verification.

Field-trial note: verify the generated Master Clinical Note against the entered information before clinical use.
