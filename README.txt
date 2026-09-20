JeevSetu v0.1 — Build 3.8 — HTTPS Voice Diagnostic

Purpose:
Build 3.8 keeps the Build 3.7 HTTPS voice architecture but adds a dedicated
"Test Voice Service" diagnostic.

Testing on Samsung tablet:
1. Extract the ZIP.
2. Open JeevSetu from the HTTPS website (not file://).
3. Tap START HPI.
4. Tap "🎙️ Test Microphone".
5. Tap "🔎 Test Voice Service".
6. If it says Speech service STARTED, speak a short Hindi sentence.
7. Send a screenshot of the diagnostic result.

Important:
- Do NOT tap Test Voice Service from file:// mode.
- The diagnostic calls SpeechRecognition.start() directly from the button tap.
- It does not await getUserMedia before starting speech recognition.
- This helps distinguish ordinary microphone permission from Chrome/Android
  Web Speech service refusal.
