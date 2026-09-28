JeevSetu Master Integration 1 — Sections 1 + 4

Purpose:
- Keep Section 1 and Section 4 as independent modules.
- Add a master integration layer.
- Section 1 saves a structured bridge record after completion.
- Section 4 saves a structured bridge record when Section 4 is saved.
- Master Clinical Record combines the two records without deleting the originals.

Testing:
1. Open index.html through a suitable web host/GitHub Pages for full browser behavior.
2. Complete Section 1.
3. Complete/save Section 4.
4. Tap Refresh Master Record.
5. Verify one Patient ID and one integrated record.
6. Original section data remains separately available in browser localStorage for cross-checking.

Voice:
As in the original build, microphone/speech recognition should be tested on HTTPS/GitHub Pages rather than directly from a ZIP/file URL.
