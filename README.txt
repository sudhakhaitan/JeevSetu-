JeevSetu v0.1 — Build 3.9 V2-5-43 — SECTION 1 FINAL

SECTION 1 LOCATION UPDATE

1. State is now a controlled dropdown containing all Indian States and Union Territories in the location dataset.
2. District is a dependent dropdown: after selecting a State, only districts belonging to that State are shown.
3. Free-text State/District entry has been removed, preventing spelling/Hindi-script variations from affecting Patient ID generation.
4. Patient ID geographic prefix now uses a fixed 2-letter State code plus a deterministic District code.
   Example: Rajasthan + Sikar -> JS-RJ-SIK-00001
5. Patient ID is still generated only after all required Section 1 fields are completed.
6. The location dataset is loaded from a current JSON dataset derived from the Government of India's Integrated Government Online Directory (IGOD). It is cached in the browser after first successful load.
7. If the device is offline and the dataset has not previously been cached, the location dropdown cannot be populated. For GitHub Pages testing, the device should have internet access on first load.

SECTION 1 WORKFLOW
Patient details -> State -> District -> Block/Tehsil -> Village/Town -> Centre -> Address -> Age -> Sex -> Preferred language -> Education -> Historian -> Relationship (if needed) -> COMPLETE SECTION 1 -> Patient ID -> Red Flags -> Complaint/HPI

This build intentionally does not change the Section 4/HPI logic.
