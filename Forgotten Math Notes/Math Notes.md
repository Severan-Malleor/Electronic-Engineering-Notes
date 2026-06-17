### Isolating Squared Variables

**Core Technique** (Solving equations like `value = I² × constant`)

1. **Isolate the squared term**  
   Divide both sides by the constant:  
   $$
   I^2 = \frac{value}{constant}
   $$

2. **Remove the square**  
   Take the square root of both sides:  
   $$
   I = \sqrt{\frac{value}{constant}}
   $$

> **Important**: Mathematically there are two solutions (±), but in electronics (current, voltage, etc.) we almost always use the **positive root**.

**Worked Example**  
$$
0.1 = I^2 \times 2200
$$

- $( I^2 = \frac{0.1}{2200} \approx 0.00004545)$
- $( I = \sqrt{0.00004545} \approx 0.00674\ A )$

**Quick Reference**

| Goal                 | Operation              | Example                             |
| -------------------- | ---------------------- | ----------------------------------- |
| Isolate squared term | Divide both sides      | $I^2 = \frac{right}{constant}$      |
| Undo square          | Square root both sides | $I = \sqrt{left}$                   |
| Check work           | Plug answer back in    | $0.00674^2 \times 2200 \approx 0.1$ |

---

### Working with Exponents & Scientific Notation

**Scientific Notation Standard Form**  
**`a × 10^b`** where **1 ≤ a < 10**

**Examples**

| Number     | Scientific Notation | Notes   |
| ---------- | ------------------- | ------- |
| 830        | $8.3 × 10²$         | Correct |
| 86,956,522 | $8.696 × 10^7$      | Correct |
| 0.00000005 | $5 × 10^{-8}$       | Correct |
| 225        | $2.25 × 10²$        | Correct |

**Key Exponent Rules**

- **Multiply**: Add exponents → $10^3 \times 10^5 = 10^8$
- **Divide**: Subtract exponents → $10^{10} \div 10^2 = 10^8$
- **Square**: Double the exponent → $(10^7)^2 = 10^{14}$

**Common Patterns in Electronics**

- **Current**: $I = \frac{P}{V}$
- **Power Loss**: $P_{loss} = I^2 \times R$
- **Moving the Decimal**:
  - Positive exponent → move decimal **right**
  - Negative exponent → move decimal **left**

**Quick Reference Table**

| Operation       | Rule               | Example                         |
| --------------- | ------------------ | ------------------------------- |
| Multiply powers | Add exponents      | $10^7 \times 10^{-8} = 10^{-1}$ |
| Divide powers   | Subtract exponents | $10^{10} / 10^2 = 10^8$         |
| Square          | Double exponent    | $(10^7)^2 = 10^{14}$            |
