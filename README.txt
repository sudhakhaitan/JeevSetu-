JeevSetu Master Integration — Sections 1–16
Build: V2-5-61 — RED-FLAG NEGATIVE TRANSITION FIX

GitHub-ready root package:
- index.html
- README.txt

Red-flag safety transition:
- NEGATIVE / नहीं → save answer → mark safety check complete → immediately continue to next question/section.
- POSITIVE / हाँ → red alert → stop routine history.
- NEGATIVE red-flag answers do not fall through to the generic free-text red-flag detector.
- Unknown/non-standard typed safety answers do not get treated as negative.

Clinical-note rule:
- No individual Clinical Note is generated after any section.
- No Master Clinical Note is generated before Section 21.
- The single final Master Clinical Note is generated only after Section 21 is completed.

Package is intentionally flattened at the ZIP root for direct GitHub upload.
