## How it works

This design implements AND, NAND, and OR logic gates using inputs a and b.  
The outputs correspond to each logic operation.

Additionally, flip-flops are used to divide the clock signal, generating slower output signals.

## How to test

Set the inputs and verify the outputs match the expected logic:

| a | b | AND | NAND | OR |
|---|---|-----|------|----|
| 0 | 0 |  0  |  1   |  0 |
| 0 | 1 |  0  |  1   |  1 |
| 1 | 0 |  0  |  1   |  1 |
| 1 | 1 |  1  |  0   |  1 |

Apply a clock signal (e.g., 10 kHz) and observe the divided outputs changing at slower rates.