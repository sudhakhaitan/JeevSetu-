JeevSetu V2-5-135 — Existing-ID Correction / Addition

Built on V2-5-134. Adds a patient-ID-specific correction/addition panel in the archive lookup result. It records amendments as a dated, patient-reported addendum, preserving the original history rather than silently overwriting it. Saved amendments are included in the final Master Clinical Note when the patient record is reopened and the note is generated again.

Data remains in browser localStorage and is not uploaded to GitHub. Use the same GitHub Pages URL and Chrome profile. This is an unverified test build: use dummy data first, and keep JSON backups. Test by retrieving one of the existing archive IDs, saving a short correction, closing/reopening the site, retrieving the same ID, and checking that the correction appears in the archive note.
