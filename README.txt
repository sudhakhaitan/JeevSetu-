JeevSetu Master Integration 1–16 — V2-5-68

FIX IN THIS BUILD
1. Section 14 completion narrative is hidden before Section 15 opens.
2. Section 15 completion narrative is hidden before Section 16 opens.
3. Section 16 completion defensively hides any stale Section 14/15 completion cards.
4. Section 16 contains questions 16.11 and 16.12 with the exact wording in the integrated Section 16 package.
5. No Master Clinical Note is generated before Section 21. The final generator remains disabled in this 1–16 build.

TEST FLOW
Sections 1 → 16 sequentially.
After Section 14: Section 14 completion narrative must NOT remain above Section 15.
After Section 15: Section 14 or 15 completion narratives must NOT remain above Section 16.
Section 16: 16.11 and 16.12 must be asked.
After Section 16: no Clinical Note / Master Clinical Note is generated.
