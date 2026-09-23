JeevSetu v0.1 — Build 3.9 V2-5-40 — SECTION 1 + ID GATE

This build corrects the Section 1 workflow.

SECTION 1 fields:
1. Patient name
2. Mobile number
3. Patient address
4. Who is giving the history (Patient / Another person)
5. Relationship to patient — asked only when another person is responding
6. Patient age
7. Patient sex
8. Communication / understanding

GATE:
- Patient ID is generated ONLY after all Section 1 fields are completed.
- No red-flag question and no complaint question appears before Patient ID generation.
- After ID generation, red-flag screening starts.
- Female-specific emergency screening is also placed after the ID gate.
- Existing complaint/HPI, additional-HPI closing question, second-complaint flow, and duplicate-complaint protection are retained.

Prototype ID format remains JS-MP-BAR-000001 style and is generated from browser localStorage for testing.
