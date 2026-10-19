JeevSetu History Taking Sections 1-21 — V2-5-109
Section 5 dynamic voice-field scan fix

This build is based on V2-5-108, where Sections 1-4 were reported working.
It makes voice-button discovery include dynamically rendered root fields as well
as their descendants, so Section 5 free-text fields receive one microphone button.
The existing single-utterance replacement behavior is retained to avoid appending
repeated transcripts into the same field.

Testing required on Chrome/HTTPS with microphone permission enabled:
1. Complete Sections 1-4.
2. In Section 5, test a free-text answer and verify one microphone button appears.
3. Speak once and confirm the answer appears once only.
4. Move to the next question and confirm the previous answer does not carry over.
5. Complete Section 5 and confirm navigation continues to Section 6.

Live microphone behavior has not been verified on the user's tablet.
