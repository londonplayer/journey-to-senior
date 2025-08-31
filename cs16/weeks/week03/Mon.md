# Week 03 — Mon 6–9 pm — Deep Lab A: CPU + Assembler

Warm-up (20 min)
- Control truth table; BFS idea.

Lab (110 min)
- CPU.hdl integrating ALU, registers, control.
- Single-pass assembler (A/C-instructions).

Acceptance
```bash
HardwareSimulator.sh projects/05/CPU.tst
CPUEmulator.sh projects/05/Rect.tst
./assembler input.asm > out.hack
diff out.hack expected.hack
```

Reading (20 min)
- N2T Ch. 5–6; graphs basics (6.042J Ch. 10.1–10.3).

Debugging (30 min)
- Unit-test parser/code modules for assembler.

Reflection (20 min)
- Invariant notes; add cards for CPU control signals.