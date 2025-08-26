Week 12 — Network layer; RTT/goodput study; TLS 1.3 overview

- Readings
  - Kurose & Ross Ch. 4 overview. RFC 8446 Sec. 1–2, 4. MIT 6.042J: variance; tail bounds (high level).
- Labs
  - W12-A Latency/goodput measurement: RTT to multiple locations; handshake breakdown via tcpdump/wireshark; compute goodput at varying windows.
    - Acceptance: plots; compare to speed-of-light lower bounds.
- Retrieval set 1. Goodput given RTT and MSS. 2) 95% CI for mean RTT (normal approx). 3) TLS 1.3 1‑RTT handshake outline. 4) When BDP dominates. 5) SYN cookies impact on options. 6) Variance reduction via batching.
  Mon 6–7 pm (Math/Theory) — Micro-Lab ML4 prep and variance

- 6:00–6:10 Quiz: Qs 1, 2.
- 6:10–6:40 Drills: compute CIs; variance basics.
- 6:40–7:00 Feynman: “Speed-of-light bounds.”
  Tue 6–9 pm (Deep Lab) — Measurement runs

- 6:00–6:20 Retrieval: Qs 4, 5.
- 6:20–8:10 Lab W12-A: measure RTT/handshakes; capture with tcpdump/wireshark.
- 8:10–8:30 Reading: BDP and windows.
- 8:30–9:00 Debug + Reflection: draft plots; list confounders.
  Wed 6–7 pm (Drills) — Micro-Lab ML4 (speed-of-light)

- 6:00–6:10 Retrieval: Q 6.
- 6:10–6:40 Lab: compute geo RTT lower bounds; compare to measured.
- 6:40–7:00 Feynman: “Why we can’t beat physics.” Artifact: table.
  Thu 6–9 pm (Deep Lab) — Goodput analysis

- 6:00–6:20 Retrieval: recap.
- 6:20–8:10 Lab: window adjustments vs throughput; plot goodput vs window/RTT.
- 8:10–8:30 Reading: RFC notes; TLS handshake messages.
- 8:30–9:00 Reflection: latency report outline.
  Fri 6–7 pm (Drills) — TLS 1.3 overview

- 6:00–6:10 Retrieval: Qs 3 recap.
- 6:10–6:40 Drills: handshake sequencing; early data caveats.
- 6:40–7:00 Feynman: “BDP intuition.”
