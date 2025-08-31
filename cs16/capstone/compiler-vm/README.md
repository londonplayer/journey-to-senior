# Capstone: Compiler + Bytecode VM (C)

Scope
- Small language: expressions, variables, conditionals, while, functions.
- Compiler → bytecode; stack-based VM; optional GC (mark-sweep).

Acceptance
- Parsing: valid/invalid suites.
- Semantics: reference outputs; tail recursion test; error handling.
- VM: disassembler round-trip; GC preserves liveness (if implemented).

Required analyses
- Performance study: interpreter vs. VM speed; instruction mix; CPI-like metric.
- Queueing component (if multithreaded).
- Security review: input validation, sandboxing, resource limits (stack depth).