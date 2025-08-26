Week 4 — Virtual memory; loader; asymptotics/recurrences; metastability demo

- Readings
  - CS:APP 9.1–9.8; 7.6–7.11. OSTEP: address spaces. MIT 6.042J: asymptotics; recurrences.
- Labs
  - W4-A VM/loader trace: strace -f, /proc/pid/maps; provoke page faults; measure minor/major.
    - Acceptance: report addresses of segments; one page fault explained.
  - Micro-Lab ML2 (Thu): Logisim async domains + 1 vs 2-FF synchronizer; metastability demo.
- Retrieval set 1. TLB role. 2) Master method for \(T(n)=2T(n/2)+n\). 3) Copy-on-write at fork. 4) Synchronizer invariant. 5) ASLR randomized segments. 6) Runtime relocation of SOs. 7) Why major faults are slow.
  Mon 6–7 pm (Math/Theory) — Asymptotics and Master method

- 6:00–6:10 Quiz: Qs 2, 7.
- 6:10–6:40 Drills: big‑O/Θ definitions; solve a simple recurrence.
- 6:40–7:00 Feynman: “What a TLB does.”
  Tue 6–9 pm (Deep Lab) — VM + loader

- 6:00–6:20 Retrieval: Qs 1, 3, 5.
- 6:20–8:10 Lab W4-A: strace/memory maps; trigger page fault; record events.
- 8:10–8:30 Reading: OSTEP address space chapters.
- 8:30–9:00 Debug + Reflection: write map report with addresses.
  Wed 6–7 pm (Drills) — Recurrences + ELF loader

- 6:00–6:10 Retrieval: Qs 4, 6.
- 6:10–6:40 Drills: iterate method for \(T(n)=2T(n/2)+n\); loader relocation steps.
- 6:40–7:00 Diagram: process memory layout.
  Thu 6–9 pm (Deep Lab) — Micro-Lab ML2 + wrap VM

- 6:00–6:20 Retrieval: review set.
- 6:20–8:10 ML2: build async clock domains; observe metastability; two-flop fix.
- 8:10–8:30 Reading: DDCA metastability section.
- 8:30–9:00 Reflection: estimate qualitative MTBF trend.
  Fri 6–7 pm (Drills) — VM cases

- 6:00–6:10 Retrieval: quick.
- 6:10–6:40 Drills: CoW experiments; minor vs major fault story.
- 6:40–7:00 Feynman: “ASLR: what/why.”
