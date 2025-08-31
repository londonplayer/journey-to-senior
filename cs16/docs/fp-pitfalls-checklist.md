# Floating-point Pitfalls Checklist

- Avoid equality; use tolerances.
- Non-associativity: (a+b)+c ≠ a+(b+c).
- Use compensated/pairwise summation; prefer FMA when available.
- Beware catastrophic cancellation (x−y with x≈y).
- Track condition numbers; scale/normalize inputs.
- Handle NaNs/Infinities/subnormals; consider FE exceptions.
- Document and justify tolerances.