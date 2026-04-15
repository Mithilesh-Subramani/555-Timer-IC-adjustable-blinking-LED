# Adjustable Flashing LED Circuit using 555 Timer IC

## Overview

This project demonstrates the design and implementation of an **adjustable LED flashing circuit** using the **555 Timer IC in astable mode**.
The circuit generates a continuous square wave signal, enabling an LED to blink at a controllable frequency.

By varying resistor and capacitor values, the blinking speed can be precisely adjusted, making this a fundamental and practical application in **digital electronics and embedded systems**.

---

## Objectives

* Design a stable LED blinking circuit using the 555 Timer IC
* Implement adjustable frequency control using passive components
* Understand astable multivibrator operation
* Analyze timing characteristics and waveform generation

---

## Components Required

* 555 Timer IC
* Resistors (R1, R2) 220, 1K  ohms respectively 
* Capacitor (C) 10 uF
* LED
* Breadboard
* Connecting wires
* Power supply (5V battery)

---


## Working Principle

The 555 Timer operates in **astable mode**, where it continuously switches between HIGH and LOW states without any external triggering.

* The capacitor charges through **R1 and R2**
* It discharges through **R2**
* This charging and discharging cycle creates a square wave output
* The LED blinks according to the output signal

### Timing Equations

* HIGH Time:
  `T_high = 0.693 × (R1 + R2) × C`

* LOW Time:
  `T_low = 0.693 × R2 × C`

* Total Time Period:
  `T = 0.693 × (R1 + 2R2) × C`

* Frequency:
  `f = 1 / T`

---

## Adjustability

The blinking speed can be controlled by:

* Changing resistor values (R1, R2) or
* Using a potentiometer for variable resistance
* Modifying capacitor value

This allows for:

* Slow blinking (seconds interval)
* Fast blinking (milliseconds interval)

---

## Applications

* LED flashers and indicators
* Signal generators
* Alarm and warning systems
* Basic clock pulse generation
* Educational demonstrations in electronics

---

## How to Use

1. Assemble the circuit as shown in the diagram
2. Connect the power supply
3. Observe LED blinking
4. Adjust resistor/potentiometer to change blinking speed

---

## Learning Outcomes

* Understanding of **astable multivibrators**
* Hands-on experience with the 555 Timer IC
* Basics of waveform generation and timing circuits
* Practical implementation of electronic theory

---

## Author

**Mithilesh Subramani**



---

