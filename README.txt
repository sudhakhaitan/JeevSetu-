JeevSetu v0.1 — Master Sections 1–21 Integrated — V2-5-118

Section 5 voice capture correction:
- Adds dedicated microphone buttons to text fields dynamically rendered inside Section 5. The main Section 5 microphone now routes speech to a visible text field before considering radio choices, fixing mixed screens where injury details and yes/no options appear together.
- Uses one final speech result per button press and replaces only the active field, preventing duplicate/carryover text.
- Keeps Sections 1–4 and other sections unchanged.

GitHub Pages: extract this ZIP and upload the website files (index.html and README.txt) to the JeevSetu repository root. Do not upload the ZIP itself as the website.

Test on HTTPS in Chrome: complete Sections 1–4, then in Section 5 select a previous illness and test voice capture on the diagnosis/date/details text fields. Confirm the words appear in that field before proceeding. Do not proceed to Section 6 until Section 5 is confirmed working.
