JeevSetu Build 3.9 — Clinical Note formatter + optional BHASHINI V2-5-14 FRESH.

Based on V2-5-13 FRESH.

Working Hindi patient interaction, question sequence, and answer storage are unchanged.

Changes in V2-5-14:
- Keeps the V2-5-13 safe local clinical formatter and Duration cleanup.
- Adds an optional BHASHINI Hindi→English translation adapter for statements that the local formatter cannot safely translate.
- Multiple unresolved Hindi answers are sent together in one BHASHINI translation request.
- The BHASHINI inference API key is entered by the user through “Configure BHASHINI Translation” and stored only in this browser's localStorage. It is NOT included in this ZIP or source code.
- If BHASHINI is not configured or the request fails (including browser CORS restrictions), JeevSetu automatically falls back to the existing safe local formatter and preserves the original wording rather than inventing an English translation.

Important:
BHASHINI requires an inference API key. The official BHASHINI documentation also notes that browser CORS can block direct calls in some environments. For production deployment, a secure server-side proxy is preferable so the API key is not exposed to the browser.
