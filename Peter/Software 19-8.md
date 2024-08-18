# Half Adder/ Full Adder

### Decimal vs binary

- **Decimal Addition**:
    - Example: 2 + 2 = 4 (no carry)
    - Example: 6 + 8 = 14 (carry 1 to next column, sum = 4)
- **Binary Addition**:
    - Maximum digit is 1.
    - Example: 1 + 0 = 1 (sum = 1, carry = 0)
    - Example: 1 + 1 = 10 (sum = 0, carry = 1)

## Truth Table for Half Adder

| A (Input 1) | B (Input 2) | Sum (S) | Carry (C) |
| --- | --- | --- | --- |
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

### Half Adder Logic Circuit

- **Components**:
    - **Exclusive OR (XOR) Gate** for Sum (S)
    - **AND Gate** for Carry (C)

### Limitations of Half Adders

- Half adders can only handle single-digit binary numbers.
- For larger numbers, we need full adders.

### Full Adder Logic

- A full adder can handle three inputs: two significant bits and a carry-in from the previous addition.

### Truth Table for Full Adder

| A (Input 1) | B (Input 2) | Carry-In (C_in) | Sum (S) | Carry-Out (C_out) |
| --- | --- | --- | --- | --- |
| 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 1 | 1 | 0 |
| 0 | 1 | 0 | 1 | 0 |
| 0 | 1 | 1 | 0 | 1 |
| 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 0 | 1 |
| 1 | 1 | 0 | 0 | 1 |
| 1 | 1 | 1 | 1 | 1 |

###  Full Adder Logic Circuit

- **Components**:
    - **Three-input XOR Gate** for Sum (S)
    - **AND Gates** to determine Carry-Out (C_out)
    - **OR Gate** to combine carry conditions.

###  Connecting Adders

- Half adders are used for the least significant bit (rightmost).
- Full adders are used for subsequent bits, taking into account carry from previous additions.

### Example of Binary Addition

- **Example 1**: 3 (0011) + 2 (0010) = 5 (0101)
- **Example 2**: 7 (0111) + 8 (1000) = 15 (1111)

