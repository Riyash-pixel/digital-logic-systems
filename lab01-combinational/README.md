# Lab 01 — Combinational Logic Circuit Design

## Overview
Designed and implemented a combinational logic system processing 18 digital inputs using multiple logic design approaches. The goal was to derive optimized Boolean expressions and implement them under gate constraints.

## Tools Used
- Lattice Diamond (schematic design)
- ModelSim (simulation & verification)

## Key Constraints
- Maximum 4 inputs per logic gate
- Three different implementations required:
  - AND-OR logic
  - NAND-only logic (using DeMorgan’s Law)
  - MUX 4:1 based design

## Design Process

### 1. Input Processing
- Converted 18 input values into binary representation
- Organized data into structured tables for mapping

### 2. Karnaugh Map Optimization
- Mapped inputs into K-maps
- Grouped adjacent values to minimize logic expressions
- Ensured no grouping exceeded 4-variable constraint

### 3. Boolean Equation Derivation
- Derived simplified expressions from K-map groupings
- Verified coverage of all required conditions

## Implementations

### 1. AND-OR Implementation
- Built circuit using AND, OR, NOT gates
- Ensured gate input limits were respected

### 2. NAND Implementation
- Converted logic using DeMorgan’s Law
- Implemented full circuit using NAND gates only

### 3. MUX 4:1 Implementation
- Divided system into 4 sub-circuits
- Used selector signals to control MUX inputs
- Each sub-circuit minimized independently

## Simulation & Verification
- Tested all implementations in ModelSim
- Verified identical output behavior across all designs
- Validated results against theoretical Boolean expressions

## Key Learning
- Logic minimization using K-maps
- Practical constraints in circuit design
- Multiple implementation strategies for the same logic
- Verification through waveform analysis

## Screenshots
(Add here: K-maps, schematics, waveforms)
