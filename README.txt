JeevSetu Build 3.9 — Clinical Note formatter fix V2-5-13 FRESH.

Based on the uploaded V2-5-12 package. The working Hindi patient interaction,
question sequence, and answer storage are unchanged.

Only the doctor-facing Clinical Note formatter was revised:
- Duration is rendered as the quantity/unit only (for example, “10 days”).
- Common complete Hindi clinical phrases use conservative phrase-level English.
- Unsafe word-by-word translation is removed to prevent malformed English.
- If a statement cannot be safely rendered, the original patient wording is
  preserved rather than showing a misleading generic fallback.
