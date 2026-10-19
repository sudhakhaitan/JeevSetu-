JeevSetu History Taking Sections 1–21 — Corrected Build V2-5-100

Corrections applied to the supplied V2-5-99 ZIP:
1. Repaired a malformed printMasterClinicalNote() block that had accidentally embedded the global voice-entry/navigation script inside the print-window HTML string. This prevented the main JavaScript from parsing and stopped Section 1 initialization and later section handlers.
2. Restored the print function to write the clinical note, close the print document, and print it.
3. Restored the global voice-entry and reversible section-navigation code to executable page JavaScript.
4. Verified all four page script blocks pass JavaScript syntax checking.

Important testing notes:
- Open on the existing HTTPS GitHub Pages site for microphone support. Voice recognition may not work when the ZIP is opened directly from Android Files using file://.
- Please test Section 1 state dropdown, then Sections 2–5, voice input in free-text fields, and Back navigation before using this version for patient records.
- This is a prototype; review patient-entered data and clinical notes before clinical use.
