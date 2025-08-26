Week 13 — Data systems: LSM prototype; Bloom filters

- Readings
  - DDIA Ch. 1–3. Mitzenmacher & Upfal: Bloom filters (selected).
  - MIT 6.042J: graphs/connectivity (light).
- Labs
  - W13-A LSM KV prototype: memtable; SSTables; compaction; optional Bloom; WAL.
    - Acceptance: crash-recovery pass; Get/Put/Delete; compaction preserves order/tombstones; Bloom meets FPR target.
- Retrieval set 1. Bloom FPR formula reasoning. 2) SSTable order/non-overlap invariant. 3) Write amplification definition/estimate. 4) Fence pointers vs Bloom filters. 5) WAL before data; ordering requirement. 6) Get complexity with L levels. 7) Partial write failure modes/mitigation. 8) When LSM beats B+trees.
  Mon 6–7 pm (Math/Theory) — Bloom math

- 6:00–6:10 Quiz: Qs 1, 6.
- 6:10–6:40 Drills: Bloom params vs FPR; quick graph connectivity tie-in.
- 6:40–7:00 Feynman: “SSTable invariants.”
  Tue 6–9 pm (Deep Lab) — LSM core

- 6:00–6:20 Retrieval: Qs 2, 5.
- 6:20–8:10 Lab W13-A: memtable, WAL, flush to SSTable.
- 8:10–8:30 Reading: DDIA storage patterns.
- 8:30–9:00 Debug + Reflection: recovery test plan.
  Wed 6–7 pm (Drills) — Compaction reasoning

- 6:00–6:10 Retrieval: Qs 3, 7.
- 6:10–6:40 Drills: compaction algorithm sketch; handle tombstones.
- 6:40–7:00 Diagram: level structure.
  Thu 6–9 pm (Deep Lab) — Bloom + compaction

- 6:00–6:20 Retrieval: recap.
- 6:20–8:10 Lab: Bloom integration; background compaction.
- 8:10–8:30 Reading: DDIA compaction trade-offs.
- 8:30–9:00 Reflection: FPR measurement + write amplification estimate.
  Fri 6–7 pm (Drills) — Consistency + failures

- 6:00–6:10 Retrieval: quick.
- 6:10–6:40 Drills: WAL ordering proofs; crash cases.
- 6:40–7:00 Feynman: “Why LSM here.”
