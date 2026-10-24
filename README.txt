JeevSetu V2-5-131 — Patient ID Edit/Resume Button Patch

Based on V2-5-130_PATIENT_ID_SCRIPT_CLOSURE_FIX.

Change:
- After a matching Patient ID is found, an EDIT / RESUME THIS RECORD button appears.
- The button closes the entry overlay and opens the existing form at Section 1, exposing the existing Section 1–21 navigation so the user can choose a section to review/edit.
- Instructions remind the user to regenerate the Master Clinical Note from Section 21 after changes.

Preserved:
- Existing patient ID persistence/banner logic.
- Existing section content and navigation logic.
- Existing clinical note generation logic.
- Local-only storage model and JSON backup/restore.

Important test note:
- This is a local-browser prototype. The lookup can only match the record currently stored in that browser unless a JSON backup is restored first. Test with dummy data and verify a changed answer is saved and reflected in the regenerated note before clinical use.
