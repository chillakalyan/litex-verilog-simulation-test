# LiteX Verilog Simulation Experiment

## Goal

Test the current state of LiteX Verilog simulation.

## Environment

OS: Ubuntu (WSL)
Python: Virtual environment
Tools: LiteX, Verilator

## Steps

1. Setup LiteX workspace
2. Create Python virtual environment
3. Run simulation command
```
litex_sim --cpu-type=mor1kx --no-compile-software
```

## Observations

- LiteX successfully generated the SoC.
- OpenRISC CPU (mor1kx) instantiated.
- Verilator simulation built successfully.
- Simulation runtime launched.

## Dependencies Required
```
sudo apt install libevent-dev
sudo apt install libjson-c-dev
```

## Conclusion

LiteX Verilog simulation appears functional with the current toolchain.


