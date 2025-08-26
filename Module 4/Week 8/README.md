Week 8 — Caches and locality; invariants; convexity check

- Readings
  - OSTEP: address translation deep dive; caching. MIT 6.042J: asymptotics practice; invariants.
- Labs
  - W8-A Cache exploration: latency vs stride; working-set sweep to find L1/L2/L3 thresholds.
    - Acceptance: latency plots; cache sizes identified; explanation.
- Retrieval set 1. Spatial vs temporal locality using your results. 2) Upper bound on misses for sequential scan under LRU. 3) Pointer arithmetic vs bounds-checking invariant. 4) TLB shootdown. 5) Is composition of convex functions convex? (quick check). 6) Why prefetching can hurt.
  Mon 6–7 pm (Math/Theory) — Invariants

- 6:00–6:10 Quiz: Qs 2, 5.
- 6:10–6:40 Drills: write/validate invariants for simple loops.
- 6:40–7:00 Feynman: “Locality and asymptotics.”
  Tue 6–9 pm (Deep Lab) — Cache microbenchmarks

- 6:00–6:20 Retrieval: Qs 1, 6.
- 6:20–8:10 Lab W8-A: stride/working-set; perf counters if available.
- 8:10–8:30 Reading: cache hierarchies.
- 8:30–9:00 Debug + Reflection: label L1/L2/L3 knees.
  Wed 6–7 pm (Drills) — Analysis

- 6:00–6:10 Retrieval: Qs 3, 4.
- 6:10–6:40 Drills: bound misses; discuss shootdowns.
- 6:40–7:00 Diagram: cache line behavior.
  Thu 6–9 pm (Deep Lab) — Repeat with variants

- 6:00–6:20 Retrieval: recap.
- 6:20–8:10 Lab: vary prefetching, blocking; gather more data.
- 8:10–8:30 Reading: OSTEP cache replacement.
- 8:30–9:00 Reflection: “When prefetching hurts” note.
  Fri 6–7 pm (Drills) — Wrap-up

- 6:00–6:10 Retrieval: quick.
- 6:10–6:40 Drills: present results; compare with CS:APP reported latencies.
- 6:40–7:00 Feynman: “Locality wins.”
