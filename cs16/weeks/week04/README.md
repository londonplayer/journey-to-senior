# Week 04 — Bits/Integers/FP; Asymptotics; C Tooling

Resources
- CS:APP: Ch. 2 (bits, ints, FP), §3.1–3.5 (machine code intro)
- CLRS: Ch. 2–3; §4.1–4.2 (recurrences)
- K&R: Ch. 1–2 refresh; §8.1–8.3 (low-level I/O)

Outcomes
- Master two’s complement and IEEE-754 representations.
- Implement hexdump; link bytes to disassembly.
- Solve recurrences via Master Theorem.

Exit Criteria
- Data-lab style functions pass tests.
- Hexdump matches xxd; disasm mapping verified.

Retrieval Bank
1) Why signed overflow is UB, unsigned wraps mod 2^w.
2) IEEE-754 format for 0.15625 (exact).
3) Solve T(n) = 3T(n/3) + n/2.
4) Two-pass vs single-pass assembler for forward labels.
5) Identify induction vars in assembly for a loop.