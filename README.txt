JeevSetu v0.1 — Build 3.9 FIXED V2-5-17 FRESH

Change in V2-5-17:
- Kept the V2-5-16 architecture and all patient-facing/Hindi logic unchanged.
- Reworked ONLY the doctor-facing Clinical Note formatter.
- Added deterministic translations for common HPI answers that were still appearing in Hindi, including time variation, severity, associated symptoms, aggravating/relieving factors, previous treatment, and relevant negatives.
- Examples: “रात में वैसे ही रहती है” -> “Unchanged at night”; “पांव में दर्द है” -> “Leg/foot pain”; “दबाने से ठीक होता है” -> “Improves with pressure”; “नहीं ऐसा कोई लक्षण नहीं है” -> “No such symptoms”.
- BHASHINI remains the final fallback for phrases not covered locally.
- Duration cleanup remains: e.g. “10 दिनों से” -> “10 days”.
