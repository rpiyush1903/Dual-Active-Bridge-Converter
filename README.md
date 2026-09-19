# 3 kW Single-Phase Dual Active Bridge (DAB) Converter for Electric Vehicle Charging

---

## About the Project

Electric vehicles are becoming common on Indian roads, and with them comes a growing need for good charging infrastructure. Fast charging depends heavily on the power electronic converter that sits between the grid and the vehicle's battery . It needs to move a good amount of power efficiently and safely.

This project is built around the **Dual Active Bridge (DAB) converter**, a widely used topology for EV charging because it keeps the vehicle side electrically isolated from the grid side, can send power in both directions, and can be made fairly compact by running at a high switching frequency.


## Objectives

- Design and build a working single-phase DAB converter for EV charging
- Validate the converter's performance in hardware, not just simulation
- Extend the design into a closed-loop system using sensor feedback
- Integrate CAN-based communication with the battery for data-driven charging control

## Approach

I started by studying the DAB converter's structure and control using phase-shift modulation, then designed the power stage — including the high-frequency transformer around a 3 kW target. After simulating the circuit to check the expected voltage, current, and power behavior, I built the design as a hardware prototype and tested it on the bench to confirm it performs as expected.

The next phase of the project involves adding sensing hardware and a control loop, along with a CAN interface to communicate with the battery, so the converter can move from a fixed, open-loop design to one that responds to real battery conditions.


## Current Status

So far, I've designed and built a **single-phase DAB converter** and tested it in hardware, achieving a stable **3 kW output**. The converter currently runs in **open-loop**, meaning the output is not yet actively regulated through feedback.

## Work Left

I'm currently developing a **closed-loop version of this DAB converter**, which will include:

- Voltage and current sensors for real-time feedback
- A control loop to regulate the output based on sensor readings
- **CAN bus communication with the battery**, so the converter can read live battery data (such as voltage, current, and state of charge) and adjust charging behavior accordingly

This is meant to make the converter behave more like a real EV charger, where charging decisions are made based on what the battery is actually reporting, rather than a fixed operating point.



