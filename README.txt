JeevSetu History Taking Sections 1–21 — V2-5-108
SECTION 4 EXTRA INFORMATION VOICE DUPLICATION FIX

Changes:
- Updated only the Section 4 Extra Information voice-recognition handler.
- Processes only new recognition results instead of replaying the full results list on each callback.
- Preserves the spoken text across Chrome recognition restarts and removes overlapping/repeated transcript fragments.
- Keeps the existing Section 4 flow and Sections 1–3 unchanged.
- Allows the user to stop recording and manually edit the captured text.

Test on HTTPS (GitHub Pages) in Chrome. Test Section 4 Extra Information with a short utterance and a longer narration, stop the microphone, and confirm the text is not duplicated. Sections 1–3 should remain unchanged.
