JeevSetu History Taking Sections 1–21
Version: V2-5-111 — Dedicated Section 5 Voice Input Fix

Changes in this build:
- Section 5 now uses its own voice-input controller for dynamically changing questions.
- Voice buttons are added to each eligible Section 5 text field after each screen redraw.
- Long answers can continue across recognition service restarts; press “रोकें” when finished.
- Each recognized segment is written to that field only; repeated adjacent final segments are filtered.
- Generic voice binding skips Section 5 to avoid competing handlers or duplicate buttons.
- Existing Sections 1–4 and the remainder of the 21-section module are preserved from V2-5-109.

Open index.html from the hosted HTTPS JeevSetu site (not as a local file), using Chrome on Android.

V2-5-111: Section 5 now has a voice control on every question screen, including radio and checkbox screens. Speech-to-text writes to visible text fields or attempts to select matching yes/no and checkbox options.
