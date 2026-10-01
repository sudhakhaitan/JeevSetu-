JeevSetu V2-5-79 — runtime/data-layer repair

1. Section 12 Yes/No, text, multi-select and confirmation buttons have direct function bindings, so tapping the visible buttons does not depend on delegated event handling.
2. Section 17, 18, 19 and 20 use separate DOM-scoped collectors. Data from one section is not copied into another section's record.
3. Pregnancy and breastfeeding dynamic rows remain attached only to Sections 19 and 20.
4. Section 21 has a direct save onclick fallback and verifies localStorage before final Master Clinical Note generation.
5. Final Master Clinical Note is generated only after Section 21 is successfully saved.
6. No intermediate Clinical Note is generated in Sections 4–20.
7. Print button remains available on the final Master Clinical Note.
8. JavaScript syntax checked successfully with Node.js.
