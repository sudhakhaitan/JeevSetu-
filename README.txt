JeevSetu History Taking Sections 1–21 — V2-5-124
Targeted fixes:
1. Section 6: Added the missing medicine-category label helper that caused a runtime error when Ayurvedic, herbal, vitamin, mineral, or supplement entries were present. The note builder now safely uses the saved Section 6 record if live form capture is unavailable and preserves allopathic medicine entries.
2. Section 21: Corrected the question labels associated with each field ID to match the actual form. Answers now stay aligned with the right question for household members, household size, work-related separation, family support, housing, water/sanitation, cooking fuel, food security, treatment costs, access to healthcare, medicine availability, phone/internet, treatment adherence, lifestyle changes, loneliness/support, and additional circumstances.
3. The conditional Section 21 follow-up (21.3a) is retained when applicable.
Validation performed: ZIP integrity, JavaScript syntax checks for all inline scripts, and confirmation that Section 21 field IDs are present. Live browser/microphone and end-to-end clinical note generation still require testing on the target device.
