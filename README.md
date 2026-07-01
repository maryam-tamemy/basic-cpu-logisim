# 16-bit Basic CPU — Datapath & Hardwired Control Unit

Implemented a Mano Basic Computer architecture in Logisim for CSIS 402 at GUC.

## Milestone 1 — Datapath
- 256-word 16-bit RAM
- 6 registers: AC, DR, AR, PC, IR, TR
- 7-function ALU: transfer, add, subtract, multiply, divide, complement, XOR
- 3-line common bus with mux control

## Milestone 2 — Control Unit
- Hardwired control: sequence counter + instruction decoder + combinational logic
- Executes: LDA, STA, ADD, DIV, XOR, ISZ, BUN
- Verified program output: A = 101, C = 35

## Files
- `cpu.circ` — Logisim circuit file
- `memory.txt` — Preloaded program memory
- `report.pdf` — Full RTL documentation

## How to Open
Download Logisim Evolution, open `cpu.circ`, load `memory.txt` into RAM.

## Author
Maryam Tamemy — GUC Spring 2026
