JeevSetu V2-5-120 — Section 5 single voice-handler correction

Code-level diagnosis: the previous file contained both the older V2-5-116 global Section 5 voice recorder and the newer V2-5-119 per-field recorder. Both could attach/listen on the same Section 5 screen, creating competing capture paths and potential duplicate or misrouted answers.

Correction: removed the obsolete V2-5-116 recorder script and retained the V2-5-119 isolated per-field voice handler. Other section logic is unchanged. Visible version labels updated to V2-5-119 for the retained build.

Upload/extract index.html and README.txt to the same GitHub Pages repository. Test Section 5: tap only the microphone beside one field, speak one answer, and verify only that field changes. Do not proceed to Section 6 until this check passes.
