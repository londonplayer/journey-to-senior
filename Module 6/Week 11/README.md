Week 11 — Sockets + HTTP/1.1; Bayes; TLS overview

- Readings
  - Kurose & Ross Ch. 2–3; TLPI sockets intro. MIT 6.042J: conditional probability; Bayes.
- Labs
  - W11-A TCP echo → HTTP GET (persistent); parse request; serve static file; thread pool.
    - Acceptance: curl tests; pipelining; Connection header handling.
- Retrieval set 1. TCP three-way handshake; why ISNs. 2) TCP guarantees and non-guarantees. 3) Bayes for packet loss given retransmissions (simple model). 4) Nagle vs delayed ACK. 5) HTTP/1.1 keep-alive semantics. 6) TLS needs randomness; name primitives. 7) Syscall sequence accept→read→write→close. 8) Latency budget components.
  Mon 6–7 pm (Math/Theory) — Bayes rule

- 6:00–6:10 Quiz: Qs 3, 8.
- 6:10–6:40 Drills: conditional probability exercises.
- 6:40–7:00 Feynman: “Handshake latency budget.”
  Tue 6–9 pm (Deep Lab) — Echo → HTTP core

- 6:00–6:20 Retrieval: Qs 1, 2.
- 6:20–8:10 Lab W11-A: echo server; extend to HTTP GET; persistent conns.
- 8:10–8:30 Reading: socket options, HTTP request format.
- 8:30–9:00 Debug + Reflection: curl tests; plan concurrency.
  Wed 6–7 pm (Drills) — TCP behaviors

- 6:00–6:10 Retrieval: Qs 4, 5, 7.
- 6:10–6:40 Drills: Nagle/delayed ACK scenarios; syscall timelines.
- 6:40–7:00 Diagram: HTTP keep-alive lifecycle.
  Thu 6–9 pm (Deep Lab) — Concurrency + parsing robustness

- 6:00–6:20 Retrieval: recap.
- 6:20–8:10 Lab: thread pool integration; pipelined requests.
- 8:10–8:30 Reading: RFC excerpts.
- 8:30–9:00 Reflection: input limits/timeouts plan.
  Fri 6–7 pm (Drills) — TLS concepts

- 6:00–6:10 Retrieval: Qs 6, 8.
- 6:10–6:40 Drills: TLS 1.3 message order (concept); randomness role.
- 6:40–7:00 Feynman: “What TCP does and doesn’t guarantee.”
