# Week 05 — Data Structures + Floating-Point Micro-lab

Resources
- CLRS: Ch. 6, 7, §10.1–10.4, §12.1–12.3
- CS:APP: §2.4 (FP ops)
- Higham: §1.2–1.4 (rounding, relative error)

Outcomes
- Implement heap, quicksort (3-way), mergesort; analyze stability.
- FP micro-lab: Kahan vs. naive; quantify error.

Exit Criteria
- Sorting/heap tests pass; stability documented.
- Kahan relative error < 1e-10 on target distribution; naive > 1e-6.

Retrieval Bank
1) Prove heapify correctness + time bound.
2) Input where naive sum loses significant digits; compute relative error.
3) When 3-way quicksort is O(n) with many equal keys.
4) Why mergesort is stable; quicksort not typically.
5) BST worst-case height inputs.