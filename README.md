# LiteX Verilog Simulation Test

This repository documents experiments evaluating the current state of
LiteX Verilog simulation using Verilator.

## Tools Used

- LiteX
- Verilator
- mor1kx (OpenRISC CPU)

## Command Tested
```
litex_sim --cpu-type=mor1kx --no-compile-software
```

## Result

LiteX successfully generated the SoC hierarchy and built the Verilator
simulation environment. After installing required dependencies
(libevent and json-c), the simulation binary compiled and launched.

## Screenshots

See the `screenshots/` folder for step-by-step outputs.
