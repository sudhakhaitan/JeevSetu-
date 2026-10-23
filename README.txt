JeevSetu V2-5-126 — Patient ID Entry Screen + Fresh Record Isolation

Fix: Fresh Form now starts a genuinely fresh record. If patient data already exists in this browser, the user is asked to confirm after being warned to download a JSON backup. On confirmation, existing JeevSetu patient/form/note data is cleared before reload, while the Patient ID sequence and offline district list are preserved. The app then opens directly into the form.

Update Existing Record / View Clinical Note remain limited to the single current browser record in this build; this is not a multi-patient archive.

Privacy: local browser storage only; no server upload. Please test with dummy data first. Before starting a fresh record, download and securely retain a JSON backup of any record you need.
