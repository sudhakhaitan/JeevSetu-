JeevSetu Master Integration 1 — Sections 1 & 4 (Sequential Controller)

This package contains:
- Master root index.html
- Master README.txt
- section1/index.html
- section1/README.txt
- section4/index.html
- section4/README.txt

Architecture:
1. The master root is the workflow controller.
2. Section 1 is the starting point.
3. Section 4 is a separate preserved section, not merged destructively into Section 1.
4. The controller keeps both sections in the same browser session/storage context.
5. Section folders remain available for doctor cross-checking and later integration.
6. The navigation layer listens for the Section-1 save/completion event JEEVSETU_SECTION1_SAVED and automatically opens Section 4.

Important:
This package deliberately does not rewrite the clinical logic inside the original Section 1 or Section 4 files. The next integration step can add a formal shared Master Clinical Record and explicit completion handshake after we verify this navigation layer.


V2 navigation fix:
- Section 1 already emits JEEVSETU_SECTION1_SAVED after saving jeevsetu_master_section1.
- Master Integration now explicitly listens for that event and switches to Section 4 automatically.
- No clinical logic was changed.
