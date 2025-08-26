# Capstone options (choose end of Week 6)

- A) Toy compiler + bytecode VM in C.
- B) Minimal TCP stack helpers + HTTP/1.1 server in C.
- Both: include numerics/perf component and a short security review.

# Assessments and rubric (applies weekly)

- Weekly 10–12 min quiz at start of Monday (Math) session.
- End-of-module oral: one systems explanation + one proof or numerics.
- Rubric per lab/report: Correctness 40%, Clarity 20%, Performance 15%, Invariants/Proofs 15%, Tests 10%.
- Floating-point pitfalls checklist: rounding mode, cancellation, stable formulas, mixed precision, tolerances.

# Tracking (keep in repo)

- Study log: per session goals/results, blockers, next steps; weekly 3-2-1 reflection.
- Backlog: Now / Next / Later / Blocked with tags.
- Anki: add 10–20 new cards during Wed/Fri; review within the sessions.

Summary of Scheduled Micro-Labs

- ML1 Week 2 Mon: Falstad RC delay/noise margins.
- ML2 Week 4 Thu: Metastability demo in Logisim.
- ML3 Week 9 Mon: IEEE-754 rounding/Kahan summation.
- ML4 Week 12 Wed: Speed-of-light bounds vs measured RTTs.

Summary of Core Lab Acceptance Tests (Selected)

- VM: run arithmetic/branch/call bytecodes; SP/FP invariants hold at function exit; disassembler round-trips.
- Allocator: align 8/16B; adjacent free coalesced; fragmentation under benchmark ≤ threshold; sanitizer clean.
- Thread pool: at-most-once; ordered completion per FIFO queue (if required); no races; throughput scaling plot up to N=8.
- HTTP server: pipelined requests handled; Connection header correct; concurrency via thread pool; curl tests pass.
- LSM KV: WAL-recovery restores last committed ops; Get respects tombstones; Bloom FPR within configured bound.
