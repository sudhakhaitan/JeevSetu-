JeevSetu AI — Section 6 Medication History v12
DEFINITIVE ALLOPATHIC CAPTURE FIX

This version directly reads every allopathic medicine row from the visible form when
Clinical Note is pressed. It does not rely on the internal medicine array, radio state,
or a previous collection event.

Expected test:
1. Select “हाँ” for current medicines.
2. Enter ONLY an allopathic medicine name (for example Paracetamol).
3. Press Clinical Note तैयार करें.
4. The Clinical Note must show “Allopathic / Modern Medicines — 1 captured”
   and a table row containing Paracetamol.
5. The page also shows a live “Allopathic medicine capture: 1 medicine(s) detected”
   indicator.

If this exact ZIP is opened and the indicator says 1 but the note still shows 0,
the problem is outside the Section 6 capture code (for example an older page/build
being opened rather than this ZIP).


CORRECTION: Section 6 Clinical Note now retains every allopathic medication row containing any entered detail. Medicine name is no longer the sole capture gate; missing names are flagged for verification.
