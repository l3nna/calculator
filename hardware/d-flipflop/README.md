# D Flip-Flop Model

A transistor-level model of a **D flip-flop** built as part of my calculator project.

Instead of using the flip-flop IC as a black box, I wanted to understand what is happening inside it and how a circuit can store a single bit of information.

For this experiment, I built a functional D flip-flop using **2N7000H60 N-channel MOSFETs**, resistors, LEDs, and push buttons.

## What is a D Flip-Flop?

A D flip-flop is a basic **sequential logic circuit** capable of storing one bit of binary information.

It has two important inputs:

* **D (Data)** — the value that will be stored
* **CLK (Clock)** — determines when the input is captured

When the clock triggers the flip-flop, the value present at the D input is transferred to the output and stored.

```text
D ───────► D Flip-Flop ───────► Q
                 ▲
                 │
                CLK
```

The stored state remains at the output until the flip-flop is triggered again.

## Why I Built It

The calculator I'm building relies on digital components such as **registers and memory elements**.

Rather than only connecting an existing IC and treating it as a black box, I wanted to understand the logic behind one of its fundamental building blocks.

This experiment helped me explore:

* Sequential logic
* Binary data storage
* Clocked circuits
* MOSFET-based logic
* The relationship between transistors and higher-level digital components

## Components

* 2N7000H60 N-channel MOSFETs
* Resistors
* LEDs
* Push buttons
* Breadboard
* Jumper wires

## Project Status

**Working prototype ✓**

The LEDs provide a visual representation of the stored binary state, making it possible to observe the flip-flop capturing and holding the input.

This is one of the building blocks I'm studying while developing the larger calculator project.

## Next Step

The next goal is to use multiple flip-flops together to create a **register capable of storing multiple bits**.

> From storing one bit to building a complete digital system.
