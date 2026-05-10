# Low Power VLSI ALU for IoT Bike Device

This project presents the design and implementation of a low-power VLSI Arithmetic Logic Unit (ALU) intended for an IoT-enabled smart bike system. The design focuses on minimizing power consumption while maintaining efficient digital operation for battery-powered embedded devices.

## Project Overview

The ALU was designed using Cadence Virtuoso as part of a Low Power VLSI course project. The architecture supports multiple arithmetic, logical, comparison, and shifting operations optimized for low-power IoT applications such as:
- GPS Tracking
- Performance Monitoring
- Theft Prevention Systems
- Smart Sensor Processing

### Design Specifications
- Supply Voltage: 1V
- Operating Frequency: 100 MHz

## Main Components

### Shifter Block
Implemented using a barrel shifter composed of four parallel 4-to-1 multiplexers supporting:
- Arithmetic Shift Left
- Logical Shift Right
- Rotate Right
- Rotate Left

### Add/Subtract Block
Designed using:
- Ripple Carry Adder
- XOR-based Control Logic

Supports:
- Addition/Subtraction
- Decrement Operation

### Comparator Block
Performs:
- Magnitude Comparison
- Arithmetic Shift Right
- 2’s Complement
- Increment Operations

### Logic Unit
Implements bitwise operations:
- AND
- OR
- XOR
- 1’s Complement

## Low Power Design Techniques

The project focused on reducing power consumption through:
- Transistor Sizing Optimization
- CMOS Logic Design
- Pass Transistor Logic (PTL)
- Careful Gate-Level Implementation

Several iterations were performed to balance:
- Power Consumption
- Delay
- Area Efficiency
