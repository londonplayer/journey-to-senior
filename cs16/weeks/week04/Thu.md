# Week 04 — Thu 6–9 pm — Deep Lab B: Hexdump + Disasm Explorer

Lab (110 min)
- Write hexdump (match `xxd -g1 -c16`) and a wrapper linking bytes to
  `objdump -d` addresses.

Acceptance
```bash
./hexdump file.bin > out.txt
xxd -g1 -c16 file.bin > ref.txt
diff -u out.txt ref.txt
# Show 3 mapping snippets aligning bytes ↔ disassembly
```

Reading (20 min)
- CS:APP §3.1–3.5.

Debugging (30 min)
- Test with different binaries; endianness awareness.

Reflection (20 min)
- Notes on instruction encodings and address mapping.