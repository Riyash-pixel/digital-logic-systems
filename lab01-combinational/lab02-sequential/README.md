# Lab 02 — Sequential Logic Design (JK Triggers & Universal Shift Register)

## Overview
Designed and simulated sequential logic systems including multiple JK trigger architectures and a 5-bit universal shift register with asynchronous reset. The focus was on system behavior, timing, and verification through simulation.

## Tools Used
- Lattice Diamond (schematic design)
- Questa Lattice OEM / ModelSim (simulation)

## Key Components

### 1. JK Trigger Implementations
- Static JK Trigger
- Master–Slave JK Trigger
- Dynamic JK Trigger

Each implementation was analyzed and compared based on behavior and timing characteristics.

### 2. Control Signal Derivation
- Derived input control equations based on given logic conditions
- Implemented using logic gates within schematic design

### 3. Universal Shift Register (5-bit)
- Designed a 5-bit register with asynchronous reset
- Supported operations:
  - Shift left
  - Shift right
  - Parallel load
  - Hold state

## Design Process

### 1. Operation Table & Analysis
- Defined trigger behavior for all input combinations
- Verified expected output transitions

### 2. Schematic Implementation
- Built circuits using logic gates and flip-flop structures
- Ensured correct signal propagation and clock behavior

### 3. Simulation & Verification
- Applied test signals using simulation scripts
- Observed waveform outputs for each trigger type
- Compared simulation results with theoretical expectations

## Key Results
- Verified correct operation of all JK trigger types
- Observed differences in behavior between static, master–slave, and dynamic designs
- Successfully implemented and validated a 5-bit universal shift register

## Key Learning
- Sequential logic design and timing behavior
- Differences between trigger architectures
- Importance of simulation in verifying system correctness

## Screenshots
(Add here: schematics, waveforms, simulation outputs)
