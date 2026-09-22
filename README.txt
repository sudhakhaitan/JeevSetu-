JeevSetu v0.1 Build 3.9 — V2-5-24 RED-FLAG
Baseline: V2-5-23 RED-FLAG

Changes:
1. History-giver identification remains the first question.
2. Added a mandatory explicit red-flag screen immediately after identifying who is giving the history.
3. Red-flag questions are written in simple patient-friendly Hindi and avoid technical clinical wording.
4. The red-flag screen is independent of the patient's first complaint; it is not left to the discretion of the non-technical history taker.
5. If a positive red flag is identified, routine history taking stops immediately and a RED FLAG ALERT is generated.
6. "Not known" on a red-flag question is retained as unknown; it is not incorrectly treated as a negative answer.
7. The existing complaint + adaptive HPI workflow is retained.
8. After completing HPI for a complaint, JeevSetu asks whether there is another complaint.
9. If yes, the next complaint gets its own HPI cycle; if no, the Hindi clinical note is generated.
10. The free-text red-flag pattern check remains as a secondary safety net during complaint/HPI.
