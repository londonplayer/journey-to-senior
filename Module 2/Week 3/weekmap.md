Week 3 — From C to ELF; relocations intro; induction basics; C ramp starts

- Readings
  - CS:APP 1.8–1.12, 3, 7.1–7.5; ELF gABI sections (symbols/relocations).
  - MIT 6.042J: Functions/relations; induction basics.
  - K&R C Ch. 1.
- Labs
  - W3-A Multi-unit build: static lib + shared lib; weak symbol; -fPIC.
    - Acceptance: list relocations (two R\_\* types); LD_DEBUG=bindings annotated symbol.
- Retrieval set 1. Static vs shared trade-offs. 2) PLT/GOT. 3) Induction: sum of first \(n\) odd numbers. 4) Call stack frame layout. 5) Endianness detection (concept). 6) Relocation addend/symbol. 7) Big‑O: linear vs binary search. 8) Makefile dependency invariant.
  Mon 6–7 pm (Math/Theory) — Induction intro

- 6:00–6:10 Quiz: Qs 3, 7.
- 6:10–6:40 Drills: write base/step for odd-sum proof; simple function mapping exercises.
- 6:40–7:00 Feynman: “What a relocation is.” Artifact: paragraph.
  Tue 6–9 pm (Deep Lab) — Linking practice

- 6:00–6:20 Retrieval: Qs 1, 2, 6.
- 6:20–8:10 Lab W3-A: build static+shared; inspect relocations; LD_DEBUG capture.
- 8:10–8:30 Reading: ELF tables; K&R Ch.1 skim; compile/run 2 tiny C programs.
- 8:30–9:00 Debug + Reflection: annotate two relocation entries.
  Wed 6–7 pm (Drills) — C basics + gdb intro

- 6:00–6:10 Retrieval: Qs 4, 5.
- 6:10–6:40 Drills: gdb run/backtrace; print argc/argv; inspect a local var.
- 6:40–7:00 Diagram: stack frame sketch for leaf function.
  Thu 6–9 pm (Deep Lab) — ELF deepening

- 6:00–6:20 Retrieval: Qs 8 recap.
- 6:20–8:10 Lab: readelf -r/-s/-h; map sections to memory layout.
- 8:10–8:30 Reading: CS:APP 7.x excerpts on PLT/GOT.
- 8:30–9:00 Debug + Reflection: write “relocation report” artifact.
  Fri 6–7 pm (Drills) — Induction practice

- 6:00–6:10 Retrieval: short proof quiz.
- 6:10–6:40 Drills: prove sum 1..n via induction; quick recurrence warm-up.
- 6:40–7:00 Feynman: “Static vs shared linking.”
