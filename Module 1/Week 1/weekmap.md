# Week 1 — Bits/Logic Foundations; Toolchain Trace

## 📚 Readings

- **DDCA** Ch. 1–2
- **Nand2Tetris** Part I Project 1 spec
- **MIT 6.042J**: Propositional logic
- **Keshav**: _How to Read a Paper_

---

## 🧪 Labs

- **W1-A: Logisim Combinational Pack**

  - Circuits: half/full adders, 16-bit ripple adder, 2:1 and 4:1 mux, 16-bit ALU slice (Z, N).
  - **Acceptance**:
    - Truth tables match
    - 100 random 16-bit pairs (A, B) pass
    - ALU ops match CSV

- **W1-B: Toolchain Trace in WSL2**
  - Task: small C program build with `-g -O0`; capture preprocess/compile/assemble/link; dump ELF headers/symbols/disasm.
  - **Acceptance**:
    - Provide `readelf` / `objdump` outputs
    - 1-paragraph on 3 symbols and sections

---

## 🧠 Retrieval Set (use all week)

1. Define **noise margin**.
2. 2:1 mux truth table; NAND-only sketch.
3. Ripple adder delay for 16 bits if per-bit delay is \(t_p\).
4. Prove \(p \to q \equiv \lnot p \lor q\) via truth table.
5. Is XOR associative? Show a counterexample or proof.
6. ELF entry point field location.
7. Preprocess vs compile vs assemble vs link.
8. One invariant of your 16-bit adder.

---

## 🗓️ Weekly Schedule

### **Mon 6–7 pm (Math/Theory) — Logic Basics + Noise Margins**

- **6:00–6:10** Quiz: retrieval Qs 1, 3, 4
- **6:10–6:40** Drills:
  - Translate English → logic
  - Build truth tables for AND/OR/IMPLIES
  - XOR associativity check
- **6:40–7:00** Feynman: _Why noise margins matter_ (half page)
  - **Artifact**: write-up

---

### **Tue 6–9 pm (Deep Lab) — Logisim Combinational Pack**

- **6:00–6:20** Retrieval: Qs 2, 5, 8; predict ripple adder delay
- **6:20–8:10** Lab W1-A: implement circuits; run built-in truth-table tests
- **8:10–8:30** Reading focus:
  - DDCA figs on CMOS inverter/logic levels
  - N2T P1 overview
- **8:30–9:00** Debug + Reflection: fix failing cases; commit artifacts; log next steps

---

### **Wed 6–7 pm (Drills) — Toolchain Vocabulary**

- **6:00–6:10** Retrieval: Qs 6, 7
- **6:10–6:40** Drills:
  - Diagram preprocess → link
  - Identify ELF sections
  - `nm` / `readelf` practice
- **6:40–7:00** Diagram: source → binary pipeline
  - **Artifact**: saved diagram

---

### **Thu 6–9 pm (Deep Lab) — Toolchain Trace**

- **6:00–6:20** Retrieval: mixed review from set
- **6:20–8:10** Lab W1-B: build with `gcc -v`; capture cpp/as/ld; dump ELF
- **8:10–8:30** Reading: MIT 6.042J logic notes (implication/equivalence)
- **8:30–9:00** Debug + Reflection: annotate 3 symbols; plan Week 2 Falstad setup

---

### **Fri 6–7 pm (Drills) — ELF and Assembly Reading**

- **6:00–6:10** Retrieval: lightning round from set
- **6:10–6:40** Drills:
  - Identify `.text` / `.data` / `.bss` / `relro`
  - Trace two disasm lines to C
- **6:40–7:00** Feynman: _What does a linker do?_
  - **Artifact**: paragraph + small diagram
