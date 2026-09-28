JeevSetu Master Integration — Sections 1–4 — Sequential Build

BASE: JeevSetu SECTION1 V2-5-45 (Sections 1–3 continuity preserved).
ADDED: Section 4 Family History v9.

ARCHITECTURE:
1. Section 1–3 runs first exactly as the base build.
2. After HPI/complaints are completed, the user sees the Section 1–3 structured summary.
3. CONTINUE TO SECTION 4 opens Family History inside the SAME master index.
4. Section 4 no longer generates an independent clinical note.
5. COMPLETE SECTION 4 generates ONE Master Clinical Note containing Sections 1–3 + Section 4.
6. Section 4 data and the Master Clinical Note are saved locally.
7. Export produces a combined Section 1–4 JSON record.

NEXT ITERATION:
Section 5 can be added to this same master index in the same way. Its independent clinical-note generation should be removed, and the final Master Clinical Note should be extended rather than replaced.
