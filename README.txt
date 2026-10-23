JeevSetu V2-5-128 — Patient ID Persistence Patch

Fix: Patient profile updates now merge the existing profile instead of replacing it. This preserves the generated patientId when Section 1 demographic fields are saved or updated, so the persistent ID banner can continue to show the same ID across later sections.

No intentional changes to the history questions, section navigation, or clinical note generation. Please test with dummy data first. This build uses local browser storage only and is not a multi-patient archive; download a JSON backup before starting a fresh record.
