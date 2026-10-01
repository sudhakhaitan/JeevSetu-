JeevSetu V2-5-78 — runtime event-binding repair

1. Section 12 now has exactly ONE click handler. The previous secondary wrapper and duplicate listener were removed.
2. Section 12 answer functions are explicitly exposed on window for reliable runtime dispatch.
3. Section 21 now has exactly ONE direct save handler; competing capture/bubbling handlers were removed.
4. Section 21 localStorage persistence is verified before final Master Clinical Note generation.
5. Final Master Clinical Note is generated only after Section 21 is successfully saved.
6. No intermediate Clinical Note is generated in Sections 4–20.
7. Print button remains available on the final Master Clinical Note.
