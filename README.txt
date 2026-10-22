JeevSetu V2-5-127 — Section 10 Resume Render Fix

This version fixes a blank dynamic Section 10 screen after reopening. It saves/restores Section 10's current question index, answers, and conditional question list in localStorage, and re-renders the question when Section 10 was the active screen. Data remains local to the browser/device; no server upload is added.

Install: replace the existing index.html in the GitHub Pages repository with this index.html. Do not clear browser data. Test with dummy data only.

Validation: JavaScript syntax check performed; full behavior must still be tested in Chrome on the tablet.


V2-5-129 AUTOSAVE RESTORE REPAIR TEST
This is a test build based on V2-5-128. It preserves the existing JeevSetu questions and adds a unified local draft snapshot for form fields, dynamic question screens, module progress, and visible section. Please test with dummy data only. Verify Sections 1-3, then a dynamic section, close/reopen, and check prior answers before continuing. This is a prototype and must not be used for real patient records until validated.

V2-5-131 test: Section 17 Save button now has an inline navigation fallback to explicitly display Section 18. Test with dummy data only.


Version 2-5-132: Section 17 navigation reapplied after the click event to prevent older/duplicate listeners from undoing the transition. This is a targeted test build.
