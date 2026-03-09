# Digital-Logic-Sprints 🛡️

> A 14-day structured sprint to master Digital Logic and VLSI fundamentals through hands-on Logisim-evolution circuit design.

Built by **Nishanth** (1MS24EI037) · MS Ramaiah Institute of Technology
Based on **NPTEL Digital Electronic Circuits** by **Prof. Goutam Saha, IIT Kharagpur**

---

## 🎯 Goal

To bridge the gap between academic theory and industry-ready VLSI fundamentals — building a professional engineering portfolio through daily circuit design, minimization, and verification tasks.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Logisim-Evolution | Circuit design & simulation |
| Combinational Analysis (Logisim) | Truth table verification |
| Git & GitHub | Version control & portfolio |
| NPTEL (Prof. Goutam Saha) | Curriculum reference |

---

## 📂 Project Navigation

### ✅ Phase 1 — Logic Blocks (Days 1–14)

| Day | Topic | Status |
|-----|-------|--------|
| [Day 01](./Day_01_Comparators) | Number Systems & 2's Complement | ✅ Complete |
| [Day 02](./Day_02_Logic_Gates) | Logic Gates & Universal Logic | ✅ Complete |
| [Day 03](./Day_03_KMap_Minimization) | K-Map Minimization | ✅ Complete |
| [Day 04](./Day_04_QM_Minimization) | Quine-McCluskey Method | ✅ Complete |
| Day 05 | Hazards in Combinational Circuits | ⏳ Upcoming |
| Day 06 | MUX, DEMUX & Data Routing | ⏳ Upcoming |
| Day 07 | Encoders, Decoders & Priority Logic | ⏳ Upcoming |
| Day 08 | Combinational Review & Mini Project | ⏳ Upcoming |
| Day 09 | Latches & Flip-Flops | ⏳ Upcoming |
| Day 10 | Registers & Shift Registers | ⏳ Upcoming |
| Day 11 | Counters | ⏳ Upcoming |
| Day 12 | Finite State Machines | ⏳ Upcoming |
| Day 13 | Arithmetic Circuits & ALU | ⏳ Upcoming |
| Day 14 | Phase 1 Capstone Project | ⏳ Upcoming |

---

## 🚀 Skills & Concepts Covered

### Phase 1: Logic Blocks

- **Day 01 — Number Systems & 2's Complement**
  - Binary representation, signed vs unsigned numbers, magnitude comparison
  - 📐 *Proof Task:* 4-bit Universal Comparator with signed/unsigned mode switch

- **Day 02 — Logic Gates & Universal Logic**
  - Universal gates (NAND/NOR), Boolean algebra, circuit conversion & optimization
  - 📐 *Proof Task:* 4-bit Range Detector — AND/OR logic converted to minimized NAND-only

- **Day 03 — K-Map Minimization**
  - 4-variable K-Maps, Gray Code ordering, Don't Care (X) conditions
  - 📐 *Proof Task:* BCD-to-Gray Code converter, verified via Combinational Analysis

- **Day 04 — Quine-McCluskey Method**
  - Tabular QM minimization, prime implicant extraction, cost criteria
  - 📐 *Proof Task:* 4-bit Prime Number Detector using QM-minimized SOP
  - 📐 *Proof Task 2:*Dual Output Fibonacci + Div3 Detector

---

## 📁 Folder Structure Convention

```
Day_XX_TopicName/
├── README.md          ← Day summary, theory notes, NPTEL reference
├── screenshots/       ← Logisim circuit screenshots
└── *.circ             ← Logisim-evolution circuit files
```

---

## 📝 Commit Convention

Every commit follows this format:

**Title:** `Day XX: <Short descriptive task name>`

**Description:**
```
Task: <What was built>
Logic: <Method or approach used>
Verification: <How it was verified>
Ref: NPTEL Digital Electronic Circuits - Lecture XX, Prof. Goutam Saha, IIT Kharagpur
---
```

## 🔗 Reference

**Course:** NOC: Digital Electronic Circuits
**Instructor:** Prof. Goutam Saha
**Institute:** IIT Kharagpur
**Platform:** NPTEL / SWAYAM
**URL:** https://nptel.ac.in/courses/108105132
