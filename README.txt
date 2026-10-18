JeevSetu V2-5-92

Repairs carried forward from V2-5-91:
1. Section 21 is an input stage only; after saving it, the patient verification record is shown before concise clinician-note generation.
2. Patient/representative approval is required before the concise clinician note is generated.
3. Section 21 screen is hidden during verification and clinician-note display.

V2-5-92 clinical-note formatting repair:
4. Removed redundant “ADDITIONAL INFORMATION — SECTION X” labels for Sections 6, 7, 9, 10, 11, 12 and 13; these now appear simply as “ADDITIONAL INFORMATION”.
5. Section 21 content remains included in the records, but its numbered heading is replaced by “SOCIOECONOMIC & LIVING CIRCUMSTANCES” so Section 21 is not presented as a second clinical-note section heading.
6. No intermediate clinical note generation was introduced.


V2-5-93 UPDATE
- Added optional speak-to-text controls to eligible free-text fields across Sections 1–21, including dynamically displayed fields.
- Added patient speech-language selector (Hindi, Bengali, Marathi, Gujarati, Tamil, Telugu, Kannada, Malayalam, Punjabi, Odia, English India).
- Spoken text is inserted into the existing field; users should review it before proceeding. Typing remains available.
- Existing Section 2 voice workflow, saving/navigation logic, and Section 21 final-note gate are preserved.
- Browser speech recognition requires a compatible browser/service and usually HTTPS; language availability can vary by device/service.
- History answers are not automatically translated.
