Week 10 — Rate limiting or work-stealing; Chernoff overview; scheduling

- Readings
  - OSTEP scheduling; concurrency patterns. Mitzenmacher & Upfal: hashing basics; Chernoff bound overview.
- Labs
  - W10-A Rate limiter (token bucket) or simple work-stealing.
    - Acceptance: throughput within ±5%; tail latency bounded at given load.
- Retrieval set 1. Token bucket steady throughput derivation. 2) Bound P[X ≥ (1+δ)μ] (use Markov/Chernoff idea). 3) Token accounting invariant. 4) Scheduling policy minimizing mean response (M/M/1). 5) ABA problem in lock-free queues. 6) Backoff and fairness. 7) Interpret perf top output.
  Mon 6–7 pm (Math/Theory) — Tail bounds (overview)

- 6:00–6:10 Quiz: Qs 1, 2.
- 6:10–6:40 Drills: apply Markov/Chernoff conceptually to bursts.
- 6:40–7:00 Feynman: “Why invariants matter in rate limiting.”
  Tue 6–9 pm (Deep Lab) — Implement rate limiter/stealing

- 6:00–6:20 Retrieval: Qs 3, 4.
- 6:20–8:10 Lab W10-A: core algorithm; tests.
- 8:10–8:30 Reading: OSTEP scheduling.
- 8:30–9:00 Debug + Reflection: perf plan.
  Wed 6–7 pm (Drills) — perf tooling + lock-free pitfalls

- 6:00–6:10 Retrieval: Qs 5, 7.
- 6:10–6:40 Drills: perf top/record; identify hot functions.
- 6:40–7:00 Diagram: token bucket state.
  Thu 6–9 pm (Deep Lab) — Load test + analysis

- 6:00–6:20 Retrieval: recap.
- 6:20–8:10 Lab: measure latency distribution; adjust parameters.
- 8:10–8:30 Reading: fairness/backoff notes.
- 8:30–9:00 Reflection: invariants check; report.
  Fri 6–7 pm (Drills) — Queueing practice

- 6:00–6:10 Retrieval: quick.
- 6:10–6:40 Drills: Little’s law with batching; M/M/1 intuition.
- 6:40–7:00 Feynman: “Scheduling and response time.”
