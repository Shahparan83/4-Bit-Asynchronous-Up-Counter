# 4-Bit Asynchronous Up Counter Using JK Flip-Flops

## Project Overview

This project presents the design and simulation of a 4-bit asynchronous up counter using four cascaded JK flip-flops.

The counter is designed to count upward in binary from 0000 to 1111. Each JK flip-flop is configured in toggle mode by connecting both J and K inputs to HIGH (J = K = 1).

The circuit is designed and tested using Tinkercad Circuits.

## Objectives

- To design a 4-bit asynchronous up counter using four JK flip-flops.
- To configure the JK flip-flops in toggle mode.
- To generate the binary counting sequence from 0000 to 1111.
- To observe the ripple effect and sequential state transitions.
- To verify the counter operation using LED outputs.

## Components Used

- 4 JK Flip-Flops
- Function Generator / Clock Source
- LEDs
- Resistors
- Breadboard
- Power Supply
- Connecting Wires

## Working Principle

All four JK flip-flops are configured in toggle mode by setting:

J = 1, K = 1

The first flip-flop receives the external clock signal. The output of the first flip-flop is connected to the clock input of the second flip-flop. Similarly, the output of each flip-flop is connected to the clock input of the following flip-flop.

Therefore, the flip-flops do not change their states simultaneously. The state transition propagates from one stage to the next, producing a ripple effect. This is why the circuit is called an asynchronous or ripple counter.

The outputs Q3, Q2, Q1, and Q0 represent the 4-bit binary count.

## Counting Sequence

The counter generates 16 different states:

0000 → 0001 → 0010 → 0011 → ... → 1110 → 1111

After reaching 1111, the counter returns to 0000 and the counting cycle repeats.

## Simulation

The circuit was implemented and tested in the Tinkercad Circuits environment. LEDs were connected to the four output terminals to visually observe the binary counting states.

## Result

The simulation successfully produced the expected 4-bit binary counting sequence from 0000 to 1111. The output of the counter was correctly represented through the LEDs.

The simulation also demonstrated the ripple effect and propagation delay associated with asynchronous counters.

## Applications

- Frequency Division
- Digital Timers and Clocks
- Digital Measurement Systems
- Educational and Laboratory Applications

## Tinkercad Simulation

[Click here to view the Tinkercad simulation](https://www.tinkercad.com/things/7UvR9EbG5jO-4-bit-asynchronous-up-counter-using-jk-flip-flop/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard)

## References

1. GeeksforGeeks, "What is JK Flip-Flop?"
2. TutorialsPoint, "What is JK Flip-Flop?"
3. Autodesk, "4-Bit Asynchronous Up Counter Using JK Flip-Flop," Tinkercad Circuits.      
