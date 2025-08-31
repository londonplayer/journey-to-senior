# Week 01 — Proofs, Bits, Boolean Logic

Resources
- 6.042J: Ch. 1–2 (logic, proof techniques), Ch. 3.1–3.3 (sets, functions)
- Nand2Tetris: Ch. 1–2 (Boolean logic, Boolean arithmetic)
- CS:APP: §1.1–1.3 (systems overview)

Outcomes
- Implement basic combinational circuits and 16-bit adders.
- Practice proof by contradiction and induction.
- C environment smoke test; bitwise ops basics.

Exit Criteria
- All N2T Ch.1–2 tests pass; short correctness notes per chip.
- C warm-up tests pass on 32/64-bit builds; valgrind: 0 leaks/errors.

Retrieval Bank (use across sessions)
1) Prove by induction: 1 + … + n = n(n+1)/2.
2) Why is NAND functionally complete? Build NOT, AND, OR from NAND.
3) Provide a minimal C example with signed overflow UB; explain why it’s UB.
4) If a 2:1 mux has delay δ, what’s the delay through a 4-level mux tree?
5) Explain two’s complement representation and why -x = ~x + 1.
6) Contrast simulator vs. emulator vs. real CPU on timing/observability.