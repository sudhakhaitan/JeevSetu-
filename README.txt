JeevSetu Master Integration — Sections 1–20
Build: V2-5-62

GitHub-ready root package:
- index.html
- README.txt

Integrated:
- Sections 1–16 from V2-5-61 RED-FLAG NEGATIVE FIXED
- Sections 17–20 from the refined V2-4 module
- Sections 17–20 use the existing Section 1 patient sex/age; no duplicate registration.
- Female flow: Section 17 → 18 → 19 → 20 → Section 21 placeholder.
- Male/other flow: Section 17 → 18 → Section 21 placeholder.
- Each section is saved before transition.

Clinical-note rule:
- No individual Clinical Note is generated after Sections 17, 18, 19, or 20.
- No Master Clinical Note is generated before Section 21.
- The single final Master Clinical Note remains reserved for completion of Section 21.

Red-flag rule retained:
- NEGATIVE / नहीं → save → safety check complete → immediately continue.
- POSITIVE / हाँ → red alert → stop routine history.
- Negative red-flag answers do not fall through to the generic red-flag detector.

Package is intentionally flattened at the ZIP root for direct GitHub upload.
