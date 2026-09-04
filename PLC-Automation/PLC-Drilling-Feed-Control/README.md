# PLC Drilling Feed Control

## Overview

This project demonstrates the implementation of sequential control for an automated drilling feed mechanism using a Siemens PLC.

The system uses edge detection, state transitions and a sequential step-chain to control the movement of the drilling mechanism.

## Objectives

- Implement PLC-based sequential control
- Apply negative-edge detection
- Develop and test a linear step sequence
- Control forward, drilling and return movements
- Evaluate the behaviour of the control system under sensor signal failure

## Control Sequence

The drilling process consists of the following states:

1. Initial State
2. Ready
3. Rapid Forward Movement
4. Drilling
5. Rapid Return Movement

## Technologies

- Siemens SIMATIC S7-1500
- TIA Portal
- PLC Programming
- Sequential Control
- Edge Detection
- Digital Inputs and Outputs

## Key Concepts

- Falling-edge detection
- Set/reset memory functions
- Sequential state control
- PLC scan-cycle behaviour
- Sensor and limit-switch logic
