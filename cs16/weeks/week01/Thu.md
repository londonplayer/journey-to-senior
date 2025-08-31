# Week 01 — Thu 6–9 pm — Deep Lab B: C Warm-up

Objectives
- Detect endianness; print type sizes; implement bit ops library.

Warm-up (20 min)
- UB vs. implementation-defined vs. unspecified behavior; signed overflow.

Lab (110 min)
- Program: report sizeofs, endianness; bit ops (set/clear/toggle/test).

Acceptance
```bash
make test
valgrind --leak-check=full ./tests_run
```

Reading (20 min)
- K&R Ch. 1–2 skim; CS:APP §1.1–1.3.

Debugging (30 min)
- Run under valgrind; try `-fsanitize=address,undefined`.

Reflection (20 min)
- Notes on UB pitfalls; add 5 Anki cards (endian, UB, aliasing).