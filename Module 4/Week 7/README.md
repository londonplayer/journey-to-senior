Week 7 — Allocator design; recurrences; sanitizers

- Readings
  - OSTEP memory/alloc; CS:APP 9.9–9.12. MIT 6.042J: recurrences (substitution/iteration).
- Labs
  - W7-A Explicit free-list allocator with boundary tags and coalescing.
    - Acceptance: alignment; coalesce; stress traces; fragmentation threshold.
- Retrieval set 1. Block header/footer and free list invariants. 2) Prove total allocated size preserved across coalescing/decoalescing. 3) Amortized costs for split/coalesce. 4) Internal vs external fragmentation. 5) Syscalls behind malloc. 6) Peak heap usage estimation. 7) Double-free detection. 8) Free list search complexity.
  Mon 6–7 pm (Math/Theory) — Recurrences

- 6:00–6:10 Quiz: Qs 2, 3.
- 6:10–6:40 Drills: substitution; telescoping examples.
- 6:40–7:00 Feynman: “Allocator invariants.”
  Tue 6–9 pm (Deep Lab) — Allocator core

- 6:00–6:20 Retrieval: Qs 1, 4.
- 6:20–8:10 Lab W7-A: layout, free list, malloc/free; start tests.
- 8:10–8:30 Reading: CS:APP allocator chapter.
- 8:30–9:00 Debug + Reflection: add -fsanitize=address,undefined.
  Wed 6–7 pm (Drills) — Traces and metrics

- 6:00–6:10 Retrieval: Qs 5, 7.
- 6:10–6:40 Drills: analyze a trace; estimate fragmentation/peak.
- 6:40–7:00 Diagram: block coalescing.
  Thu 6–9 pm (Deep Lab) — Optimizations + tests

- 6:00–6:20 Retrieval: recap.
- 6:20–8:10 Lab: coalesce edge cases; realloc; performance trace.
- 8:10–8:30 Reading: OSTEP allocation lessons.
- 8:30–9:00 Reflection: report draft on fragmentation.
  Fri 6–7 pm (Drills) — Proofs + edge cases

- 6:00–6:10 Retrieval: quick.
- 6:10–6:40 Drills: invariant proofs (headers/footers).
- 6:40–7:00 Feynman: “mmap vs sbrk.”
