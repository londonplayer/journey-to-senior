Week 9 — Concurrency + FP micro-lab; Little’s law; expectation

- Readings
  - OSTEP: locks/conds/semaphores/deadlock. MIT 6.042J: probability basics; expectation.
  - Goldberg FP Sects. 1–4.
- Labs
  - W9-A Thread pool + bounded queue with condvars; graceful shutdown.
    - Acceptance: ordering and at-most-once pass; no races under tsan/helgrind; throughput scaling measured to N=8.
  - Micro-Lab ML3 (Mon): FP rounding + Kahan summation.
    - Acceptance: error vs order plots; conditioning vs stability explanation.
- Retrieval set 1. Little’s law; apply to thread pool. 2) Linearity of expectation; apply to jobs in system. 3) Deadlock + Coffman conditions. 4) IEEE rounding modes examples. 5) Conditioning vs stability. 6) Atomic ops needed. 7) Spurious wakeups → while. 8) Bounded queue implements backpressure.
  Mon 6–7 pm (Math/Theory) — Micro-Lab ML3

- 6:00–6:10 Quiz: Qs 1, 2.
- 6:10–6:40 Lab: naive vs Kahan; different orders; measure error.
- 6:40–7:00 Feynman: “Conditioning vs stability.” Artifact: plot + notes.
  Tue 6–9 pm (Deep Lab) — Thread pool core

- 6:00–6:20 Retrieval: Qs 3, 6, 7.
- 6:20–8:10 Lab W9-A: queue + workers; condvar protocol; shutdown.
- 8:10–8:30 Reading: OSTEP locking pitfalls.
- 8:30–9:00 Debug + Reflection: tsan/helgrind run; fixes.
  Wed 6–7 pm (Drills) — Probability basics

- 6:00–6:10 Retrieval: Qs 4, 5.
- 6:10–6:40 Drills: indicator RVs; simple expectations; Bernoulli sums.
- 6:40–7:00 Diagram: bounded queue state machine.
  Thu 6–9 pm (Deep Lab) — Throughput scaling study

- 6:00–6:20 Retrieval: recap.
- 6:20–8:10 Lab: measure scaling; apply Little’s law to estimate WIP.
- 8:10–8:30 Reading: concurrency perf sections.
- 8:30–9:00 Reflection: performance note with graphs.
  Fri 6–7 pm (Drills) — Deadlock + proofs

- 6:00–6:10 Retrieval: quick.
- 6:10–6:40 Drills: construct deadlock case; eliminate via ordering.
- 6:40–7:00 Feynman: “Backpressure via bounded queues.”
