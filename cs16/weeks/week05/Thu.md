# Week 05 — Thu 6–9 pm — Deep Lab B: FP Micro-lab

Lab (110 min)
- Sum n=10^7 alternating magnitude samples; compare naive vs. Kahan;
  compute relative error vs. high-precision baseline.

Acceptance
```bash
./sum_kahan --n 10000000 --seed 1
# Kahan rel error < 1e-10; naive > 1e-6
```

Reading (20 min)
- Higham §1.2–1.4; CS:APP §2.4.

Debugging (30 min)
- Distribution choices; deterministic seeding.

Reflection (20 min)
- Add FP pitfalls to notes; reference docs/fp-pitfalls-checklist.md.