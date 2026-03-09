# Day 04 — Quine-McCluskey Minimization

**NPTEL Reference:** Digital Electronic Circuits — Lectures 12–13  
**Instructor:** Prof. Goutam Saha, IIT Kharagpur

## Topic Covered
- Quine-McCluskey tabular minimization method
- Prime implicant extraction and selection
- Gate input cost vs literal cost criteria
- Multi-output function minimization
- Complement minimization (F' method)
- Shared gate identification across outputs

## Proof Task 1 — Prime Number Detector
4-bit Prime Number Detector (inputs 0–15)  
Minterms: {2, 3, 5, 7, 11, 13}  
Method: QM minimization → minimized SOP → Logisim implementation

**Minimized Expression:**  
`F = ĀB̄C + B̄CD + BC̄D + ĀBD`

**Result:** Verified ✅ — all 16 rows correct via Combinational Analysis

## Proof Task 2 — Bonus: Dual Output Fibonacci + Div3 Detector
Two-output 4-bit circuit in a single Logisim file.

### F1 — Fibonacci Number Detector
Minterms: {1, 2, 3, 5, 8, 13}  
Method: QM minimization

**Minimized Expression:**  
`F1 = ĀB̄C + BC̄D + AB̄C̄D̄ + ĀB̄D`

### F2 — Divisible by 3 Detector
Minterms: {0, 3, 6, 9, 12, 15}  
Method: QM attempted — no minimization possible (no adjacent minterms)

**Expression (Canonical SOP = Minimal):**  
`F2 = ĀB̄C̄D̄ + ĀB̄CD + ĀBC̄D̄ + AB̄C̄D + ABC̄D̄ + ABCD`

### Key Insight — Shared Gate
`BC̄D` appears in both F1 and F2' (complement of F2).  
One AND gate feeds both outputs — demonstrates multi-output gate sharing.

**Result:** Both outputs verified ✅ — all 16 rows correct via Combinational Analysis

## Files
- `Prime_Detector.circ` — Proof Task 1 Logisim circuit
- `Prime_Detector_Proof.png` — Proof Task 1 screenshot
- `Dual_Output_Fib_Div3.circ` — Proof Task 2 Logisim circuit
- `Dual_Output_Proof.png` — Proof Task 2 screenshot
```

---


