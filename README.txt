JeevSetu V2-5-75 — targeted fixes
1. Section 12 Yes/No controls use direct handlers as a fallback, preventing delegated click handling from blocking the Alcohol History flow.
2. Section 21 save is independent from Master Clinical Note generation. A note-generation error can no longer make Section 21 appear unsaved.
3. Final Master Clinical Note generation no longer aborts solely on Part-A validation warnings; Section 21 completion remains the trigger.
4. Print button is ensured on the final Master Clinical Note card.
