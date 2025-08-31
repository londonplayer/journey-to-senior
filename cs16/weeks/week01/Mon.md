# Week 01 — Mon 6–9 pm — Deep Lab A: Gates and Adders

Objectives
- Build And, Or, Not, Xor, Mux, DMux, HalfAdder, FullAdder, Add16, Inc16.
- Explain each chip’s correctness in 2–4 sentences.

Warm-up (20 min)
- Quick answers to retrieval: 1, 2, 4.

Lab (110 min)
- Implement chips in Nand2Tetris HDL.
- Keep a per-chip note: interface, truth table, and how composition preserves
  correctness.

Acceptance
```bash
HardwareSimulator.sh projects/01/And.tst
HardwareSimulator.sh projects/01/Mux.tst
HardwareSimulator.sh projects/02/Add16.tst
HardwareSimulator.sh projects/02/Inc16.tst
```

Reading/Annotation (20 min)
- 6.042J Ch. 1–2 key definitions; N2T Ch. 1–2 ALU design patterns.

Debugging (30 min)
- Use built-in .cmp diff; minimize gate depth where possible.

Reflection (20 min)
- Log decisions; add 5–10 Anki cards; short write-up: “Why NAND suffices.”
- Artifact: screenshot(s) of passing tests.