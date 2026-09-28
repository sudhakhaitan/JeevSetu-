JeevSetu Master Integration V3
================================

GitHub Pages entry point:
    index.html

Structure:
    index.html              -> Master controller
    section1/index.html     -> Section 1
    section4/index.html     -> Section 4

Navigation:
    1. Master loads Section 1.
    2. Section 1 completes and posts JEEVSETU_SECTION1_SAVED.
    3. Master switches the same iframe to Section 4.
    4. Section 4 opens without requiring a second GitHub upload.

IMPORTANT:
Upload/replace the ENTIRE contents of this ZIP in the GitHub repository.
Do not upload section1/index.html as the repository root index.html.
The repository root index.html must remain the V3 master controller.

Recommended test:
1. Open the GitHub Pages URL.
2. Complete Section 1 with dummy data.
3. Confirm the master page changes to Section 4 automatically.
4. Do not manually open section4/index.html for this test.
