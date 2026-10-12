# Logic Bench Implementation

This directory documents the **breadboard-level implementation** of the 4-bit ALU developed using Logic Bench.

![Logic Bench Implementation](breadboard-implementation.png)

## Implementation Status

> **Status: Work in Progress**

The circuit was recreated in Logic Bench to explore the implementation of the ALU using TTL logic ICs and breadboard-style connections.

The **logical unit has been successfully implemented and tested**, while the **arithmetic unit is currently under debugging**.

### Current Status

| Section | Status |
|---|---|
| AND | ✅ Working |
| OR | ✅ Working |
| NOT A | ✅ Working |
| XOR | ✅ Working |
| Addition | 🚧 Under debugging |
| Subtraction | 🚧 Under debugging |
| Carry / Borrow | 🚧 Pending arithmetic verification |
| Overflow Flag | 🚧 Pending arithmetic verification |
| Zero Flag | 🚧 Under verification |

## Logical Unit

The logical section currently supports the following 4-bit operations:

- Bitwise AND
- Bitwise OR
- Bitwise NOT of operand A
- Bitwise XOR

These operations have been tested and are functioning as expected in the Logic Bench implementation.

## Arithmetic Unit

The arithmetic section is designed to perform:

- 4-bit addition
- 4-bit subtraction using two's-complement arithmetic
- Carry-out detection
- Borrow detection
- Signed overflow detection

The intended circuit connections follow the ALU design used in the Logisim Evolution implementation. However, the arithmetic section of the Logic Bench implementation is still being debugged and has therefore not yet been fully verified.

## Reference Implementation

The working **Logisim Evolution implementation** serves as the reference design for the project and is used to verify the expected behavior of each ALU operation.

The Logic Bench implementation is included here to document the breadboard-level design and ongoing hardware debugging process.

## Note

The Logic Bench project file is not included at this stage because the implementation is still under development. It will be added once the arithmetic section has been fully debugged and verified.
