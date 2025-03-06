# Audio Preamplifier with Voltage-Controlled Gain

## University "Politehnica" of Bucharest
### Faculty of Electronics, Telecommunications, and Information Technology
#### Academic Year 2024-2025

### Project 1 - Design and Implementation of a Voltage-Controlled Gain Audio Preamplifier

Scientific Coordinators:
- Prof. Dr. Eng. Dragoș Dobrescu
- Prof. Dr. Eng. Vasile Mădălin Moise

Group 432B

---

![1.](Layout/pcb.jpg?raw=true "PCB")

## Introduction

In the field of audio electronics, achieving faithful and stable preamplification is essential to ensure a high-quality listening experience. The preamplifier represents the first stage in the signal processing chain, responsible for amplifying signals from very low levels (e.g., microphone, pick-up) to a sufficiently high level, allowing the signal to be processed or transmitted to a power amplifier.

The objective of this project is to design and implement a voltage-controlled gain audio preamplifier capable of providing dynamic gain control, ranging from 1 to 30, depending on the applied control voltage (0-3V). It will operate at a supply voltage of 13V and ensure high-quality audio performance.

---

## Initial Design Data

### Project Description

The project involves the design and implementation of a voltage-controlled gain audio preamplifier. The main requirements are:
- **Power supply**: 13V unipolar or ±13V bipolar
- **Input signal**: 0-30mV at 3kHz
- **Gain control**: Control voltage between 0-3V
- **Output**: The preamplifier will drive a load of 800 Ω

### Block Diagram of the Circuit

The circuit block diagram includes the following stages:
- **Common-Emitter (CE) Stage**: Provides substantial voltage gain
- **Common-Base (CB) Stage**: Ensures stability and additional gain
- **Common-Collector (CC) Stage**: Provides impedance matching and current amplification

### Implementation Method

1. **Tools and Materials Required**:
    - Solder paste
    - Reflow station
    - Anti-static tweezers
    - Additional flux
2. **Soldering Procedure (Reflow)**:
    - Preparing the PCB
    - Applying solder paste
    - Placing SMD components
    - Reflow thermal profile

---

## User Manual

The audio preamplifier is easy to use by following the steps below:

1. **Connecting the Power Supply**:
    - Connect the negative terminal to GND and the positive terminal to VCC.
2. **Input Signal**:
    - Connect the audio signal to the IN terminal.
3. **Gain Control**:
    - Adjust the control voltage (0-3V) to modify the gain.
4. **Audio Output**:
    - Connect the output to external audio equipment.

---

## Conclusions

This project represents the implementation of an efficient voltage-controlled gain audio preamplifier, useful in both professional and hobby applications. The performance obtained from testing and simulations has confirmed the circuit's functionality and reliability.

---

## References

- Technical manuals on audio amplifiers
- Guides for PCB manufacturing and SMT technology
