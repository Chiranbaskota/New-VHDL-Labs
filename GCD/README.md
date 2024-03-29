# GCD (Greatest Common Divisor)

This repository contains VHDL code for a GCD (Greatest Common Divisor) calculator (`GCD`) and its corresponding testbench (`tb_gcd`).

## Files

- `GCD.vhdl`: VHDL code for the GCD entity and architecture.
- `tb_gcd.vhdl`: VHDL code for the testbench entity and architecture.

## GCD (`GCD`)

The `GCD` entity represents a GCD calculator with the following ports:

- `RESET`: Reset input.
- `CLK`: Clock input.
- `GO`: Start computation signal.
- `NUM1`: First number input.
- `NUM2`: Second number input.
- `Result_GCD`: Result of the GCD computation output.

## Testbench (`tb_gcd`)

The testbench (`tb_gcd`) is used to verify the functionality of the `GCD` entity. It provides stimulus to the GCD calculator and observes its outputs.

## Running the Testbench

To run the testbench:

1. Compile the VHDL files (`GCD.vhdl` and `tb_gcd.vhdl`) using a VHDL compiler (e.g., GHDL).
2. Simulate the compiled design using a simulator (e.g., GHDL or ModelSim).

## Test Cases


The testbench includes various test cases to verify the behavior of the GCD calculator:

1. **Test Case 1**: Inputs `NUM1 = 12`, `NUM2 = 18`, `GO = '1'`.
2. **Test Case 2**: Inputs `NUM1 = 25`, `NUM2 = 35`, `GO = '1'`.
3. *(Add more test cases as needed)*

## Simulation Duration

Each test case is simulated for a duration to allow sufficient time for the computation to finish and the result to stabilize.
# FSM
![gcdState](https://github.com/Chiranbaskota/New-VHDL-Labs/assets/97309357/44433778-8c35-4d8f-80a4-6c36a1c0b394)
