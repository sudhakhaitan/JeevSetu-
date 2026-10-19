JeevSetu Master Sections 1–21 — V2-5-104 Section 2 Voice Isolation Fix

Based on the uploaded V2-5-102 ZIP. This build focuses on Section 1 registration reliability:
- Field-specific voice buttons write only to the field whose microphone was pressed.
- Section 1 speech recognition captures one final utterance per press and does not repeatedly append interim/final results.
- Mobile voice input keeps digits only, attempts to convert common English/Hindi number words, and limits entry to 10 digits.
- Manual editing remains available after voice entry.
- Mobile number validation requires a 10-digit Indian mobile number beginning with 6–9.
- State dropdown is locally populated. District dropdown uses the online state/district dataset when available and includes an offline fallback list for Madhya Pradesh and Bihar.

IMPORTANT: Chrome Web Speech recognition normally requires the app to be served from HTTPS and internet access. Opening the HTML directly from a ZIP/Files app may block speech recognition.

Test Section 1 before proceeding to other sections: name, mobile, state/district, block/tehsil, village, manual edits, and completing Section 1. This is a prototype build; please validate on the target Samsung tablet/Chrome before using with patients.


V2-5-104 Section 2 fix:
- Stops the active Section 2 recognizer when saving, skipping, or changing questions.
- Prevents the previous question's speech results from being written into the next question's answer field.
- Prevents the recognizer's onend handler from restoring stale text after the next question has cleared the answer field.
- Long narration remains supported while the microphone is active; press Save & Next to stop and save that question before moving on.


V2-5-105 patch: Section 2 voice input retains continuous recognition for long narration but ignores duplicate final transcripts emitted after Android Chrome speech-service restarts. Question-change cleanup remains enabled so speech from one question cannot be written into the next.
