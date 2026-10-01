JeevSetu V2-5-80 — verified runtime/data repair

1. Section 12 dynamic buttons now use ONE click path only: delegated binding. Duplicate inline onclick execution was removed.
2. Sections 17–20 collectors now ignore all elements inside hidden branches, preventing male/female and conditional subsection contamination.
3. Section 17 Master Clinical Note output uses readable labels and includes only the applicable male or female branch; menstrual vs menopause fields are filtered by the recorded answer.
4. Section 18 Master Clinical Note output uses readable labels instead of raw i1/i2... keys and excludes conditional fertility-treatment fields unless applicable.
5. Sections 19–20 retain not-applicable handling and readable labels.
6. Section 21 remains the gate for final Master Clinical Note generation.
7. JavaScript syntax was checked with Node.js before packaging.
