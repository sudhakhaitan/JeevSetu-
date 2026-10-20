JeevSetu V2-5-121 — Section 5 final-result voice routing fix

Code-level correction:
- Hardened the isolated Section 5 voice handler.
- Captures only final speech-recognition results, once per microphone press.
- Routes the transcript only to the exact field whose microphone was pressed; replaces rather than appends.
- Stops and cleans up the active recognition session when Section 5 rerenders or the user starts another field.
- Adds support for input fields without an explicit type and uses the selected language where available.
- Sections 1–4 and 6–21 are otherwise unchanged.

Important test:
1. Upload/extract index.html and README.txt to the same GitHub Pages repository.
2. Open the HTTPS GitHub Pages site in Chrome and allow microphone access.
3. In Section 5, press the microphone beside ONE question, speak one answer, and wait for the success message.
4. Confirm only that question's field changes. Repeat on a second question.
5. If it still fails, send a screenshot showing the Section 5 question, microphone button, and status message immediately after speaking. Do not assume it is fixed until this test passes.
