Week 5 — Parsing; structural induction; C control flow

- Readings
  - Crafting Interpreters Ch. 4–6, 10–12. MIT 6.042J: graphs/trees; structural induction.
  - K&R C Ch. 3.
- Labs
  - W5-A Lexer+parser for MiniLang: tokens, grammar (expr, let, if, while, print).
    - Acceptance: 100-case token corpus; AST pretty-printer round-trips 30 cases.
- Retrieval set 1. Left vs right associativity for minus; parse trees. 2) Structural induction property on expression size/leaves. 3) FIRST/FOLLOW meaning. 4) Error recovery in RD parsing. 5) Tokenize/parse complexity. 6) AST visitor invariant. 7) Why identifier tables often hash maps; expected lookup. 8) Parser security risk + mitigation.
  Mon 6–7 pm (Math/Theory) — Structural induction

- 6:00–6:10 Quiz: Qs 2, 5.
- 6:10–6:40 Drills: tree size/leaf proofs; graph basics.
- 6:40–7:00 Feynman: “Associativity and parse trees.”
  Tue 6–9 pm (Deep Lab) — Lexer + parser

- 6:00–6:20 Retrieval: Qs 1, 3.
- 6:20–8:10 Lab W5-A: tokens/grammar; RD parser; AST; tests.
- 8:10–8:30 Reading: grammar/FIRST/FOLLOW.
- 8:30–9:00 Debug + Reflection: error-reporting plan.
  Wed 6–7 pm (Drills) — C control + assembly mapping

- 6:00–6:10 Retrieval: Qs 6, 7, 8.
- 6:10–6:40 Drills: loop to assembly mapping (labels/jumps) inspection.
- 6:40–7:00 Diagram: AST traversal invariants.
  Thu 6–9 pm (Deep Lab) — Parser robustness

- 6:00–6:20 Retrieval: mixed.
- 6:20–8:10 Lab: expand grammar cases; add diagnostics.
- 8:10–8:30 Reading: error recovery patterns.
- 8:30–9:00 Reflection: security notes (input limits/fuzzing plan).
  Fri 6–7 pm (Drills) — Proofs + hashing

- 6:00–6:10 Retrieval: short proof.
- 6:10–6:40 Drills: hash map expected probes; collision considerations.
- 6:40–7:00 Feynman: “Parser invariants.”
