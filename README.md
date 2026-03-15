# Logic Design Simulator

## Overview
The Logic Design Simulator is a comprehensive tool designed for understanding and simulating various logic circuits. It provides an interactive interface for testing and validating logic designs.

## Usage Instructions
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/resitasrav/logic-design-simulator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd logic-design-simulator
   ```
3. Run the application:
   ```bash
   python main.py
   ```

## Flip-Flops
Flip-flops are essential components in sequential circuits. The simulator supports various types of flip-flops:
- SR Flip-Flop
- D Flip-Flop
- JK Flip-Flop
- T Flip-Flop

### Examples
- **Creating an SR Flip-Flop:**
   ```
   sr_flip_flop = SRFlipFlop();
   sr_flip_flop.set_inputs(1, 0);
   sr_flip_flop.perform_operation();
   ```

## Sequential Circuits
Sequential circuits use memory elements like flip-flops to store state information. The simulator can help visualize:
- Mealy and Moore state machines
- Counters and shift registers

### Practical Example
- **4-bit binary counter implementation:**
   ```
   counter = BinaryCounter(4);
   for _ in range(16):
       print(counter.next());
   ```

This allows users to see how sequential logic is implemented and operated within the specified range.