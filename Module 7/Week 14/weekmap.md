Week 14 — Transactions lite; batching; CAP; queueing

- Readings
  - DDIA Ch. 7–9. MIT 6.042J: review; entropy (optional intro).
- Labs
  - W14-A Transactions-lite: batching + fsync policy; snapshot reads; optional mock 2PC across two instances (single host).
    - Acceptance: documented durability; recovery test passes; snapshot reads correct.
- Retrieval set 1. Snapshot read invariant proof. 2) CAP theorem statement + example. 3) Throughput/latency under batching via Little’s law. 4) Why fsync frequency affects tail latency. 5) Idempotency keys for retries. 6) Group commit trade-offs.
  Mon 6–7 pm (Math/Theory) — Invariants for consistency

- 6:00–6:10 Quiz: Qs 1, 3.
- 6:10–6:40 Drills: formalize snapshot invariant.
- 6:40–7:00 Feynman: “CAP in practice.”
  Tue 6–9 pm (Deep Lab) — Snapshot reads + durability

- 6:00–6:20 Retrieval: Qs 4, 5.
- 6:20–8:10 Lab W14-A: implement batching/fsync; snapshot views.
- 8:10–8:30 Reading: group commit.
- 8:30–9:00 Debug + Reflection: recovery tests.
  Wed 6–7 pm (Drills) — Queueing math

- 6:00–6:10 Retrieval: Q 6.
- 6:10–6:40 Drills: Little’s law under batching; backpressure impact.
- 6:40–7:00 Diagram: durability pipeline.
  Thu 6–9 pm (Deep Lab) — Optional mock 2PC + tail latency study

- 6:00–6:20 Retrieval: recap.
- 6:20–8:10 Lab: 2-instance commit mock; latency measurements.
- 8:10–8:30 Reading: DDIA consistency sections.
- 8:30–9:00 Reflection: write-up notes.
  Fri 6–7 pm (Drills) — Ethics and failure budgets

- 6:00–6:10 Retrieval: quick.
- 6:10–6:40 Drills: failure injection plan; safety limits.
- 6:40–7:00 Feynman: “Batching trade-offs.”
