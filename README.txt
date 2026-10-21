JeevSetu V2-5-125 — Autosave/Resume syntax repair test

What was repaired:
- The automatic local autosave/resume code had accidentally been inserted inside the Master Clinical Note print-window JavaScript string.
- This broke the main page script and could cause the form to get stuck.
- The print-window HTML is now closed correctly, and the autosave/resume code runs as part of the main JeevSetu page script.
- JavaScript syntax was checked after the repair.

How to test on your Samsung tablet:
1. Download and extract this ZIP.
2. Open index.html in Chrome.
3. Enter dummy/test information in a few fields/questions.
4. Wait 2–3 seconds for automatic saving.
5. Close the page/tab, then reopen the same extracted index.html in the same Chrome browser.
6. If the resume banner appears, tap “वहीं से आगे जारी रखें”. Check whether the earlier answers return.
7. Continue a little further and repeat the close/reopen test.

Important:
- This is local-only browser storage. It is not a cloud backup and may not persist if Chrome/site storage is cleared or if the file is opened under a different file origin/path.
- Use dummy data for this test. Do not enter real patient data until restoration has been verified.
- Keep JSON backups separately as an additional safeguard.
