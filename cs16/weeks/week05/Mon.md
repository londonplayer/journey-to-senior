# Week 05 — Mon 6–9 pm — Deep Lab A: Sorting + Heap

Lab (110 min)
- Binary min-heap with O(log n) push/pop.
- Quicksort (median-of-three, 3-way) and mergesort (stable).

Acceptance
```bash
./sort_test --size 100000 --algo quick --check
./sort_test --stable-check mergesort
./heap_test --random 100000 --check
```

Reading (20 min)
- CLRS Ch. 6–7; stacks/queues/lists; BST basics.

Debugging (30 min)
- Property tests; adversarial inputs.

Reflection (20 min)
- Stability notes; Anki entries.