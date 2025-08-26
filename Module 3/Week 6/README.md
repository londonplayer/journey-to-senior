Week 6 — Bytecode VM; combinatorics; C structs/layout

- Readings
  - Crafting Interpreters Ch. 14–17, 19–20. MIT 6.042J: counting/binomials.
  - K&R C Ch. 6 (skim).
- Labs
  - W6-A Bytecode VM skeleton: consts, arithmetic, cmp, jumps, call/ret; VM loop and frame layout; disassembler.
    - Acceptance: suite of bytecode programs pass; disassembler round-trip.
- Retrieval set 1. Stack frame design; justify. 2) Induction: subsets count \(2^n\). 3) VM SP/FP invariant. 4) Hash table with chaining: worst vs average. 5) Short jump encoding choice. 6) Tail-call optimization impact. 7) C UB risks when writing VM.
  Mon 6–7 pm (Math/Theory) — Counting

- 6:00–6:10 Quiz: Qs 2, 4.
- 6:10–6:40 Drills: binomial identities; subsets proof.
- 6:40–7:00 Feynman: “VM stack invariants.”
  Tue 6–9 pm (Deep Lab) — VM implementation

- 6:00–6:20 Retrieval: Qs 1, 3.
- 6:20–8:10 Lab W6-A: VM loop; SP/FP; basic ops.
- 8:10–8:30 Reading: call/ret stack mgmt.
- 8:30–9:00 Debug + Reflection: state trace snapshot.
  Wed 6–7 pm (Drills) — C structs/layout

- 6:00–6:10 Retrieval: Qs 5, 6, 7.
- 6:10–6:40 Drills: struct packing; sizeof/offsets; draw layout.
- 6:40–7:00 Diagram: VM frame layout.
  Thu 6–9 pm (Deep Lab) — VM disassembler + tests

- 6:00–6:20 Retrieval: recap.
- 6:20–8:10 Lab: disassembler; bytecode round-trip tests.
- 8:10–8:30 Reading: error handling in interpreter.
- 8:30–9:00 Reflection: UB audit checklist.
  Fri 6–7 pm (Drills) — Combinatorics practice

- 6:00–6:10 Retrieval: counting quiz.
- 6:10–6:40 Drills: compositions/permutations quick set.
- 6:40–7:00 Feynman: “Tail-calls vs stack.”
