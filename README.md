# Water_Level_Indicator_DLD

This project implements a simple, cost-effective water level detection system using digital logic gates. It monitors water levels in a container using probes and provides visual feedback via an LED indicator, preventing overflow or dry tank conditions.

# Features

Detects water levels using probes.

Provides real-time feedback with an LED indicator.

Utilizes digital logic gates (IC 7404) for signal processing.

Cost-efficient and reliable design.

# Components

IC 7404 (NOT Gate IC)

BC 547 Transistor

Resistors (10kΩ, 220Ω)

LED (Red)

7805 Voltage Regulator

11.1V Battery

Breadboard and Jumper Wires

# How It Works

Low Water Level: When water is below the probe, the NOT gate outputs a LOW signal, keeping the LED off.

High Water Level: When water contacts the probe, the NOT gate outputs a HIGH signal, turning the LED on.

The 7805 regulator ensures a stable 5V supply for the circuit.

# Setup

Assemble the circuit on a breadboard using the specified components.

Place probes at desired water level thresholds in the container.

Connect the 11.1V battery and verify the 5V output from the regulator.

Test and calibrate the system for accurate detection.

# Acknowledgments

GIK Institute and Faculty, especially Sir Mehran Ali, for their guidance.

# References

"Digital Design: Principles and Practices" by John F. Wakerly

"Digital Logic Design" by M. Morris Mano

IC 7404 Datasheet: https://www.ti.com/lit/ds/symlink/sn74hc04.pdf

BC 547 Datasheet: https://www.onsemi.com/pdf/datasheet/bc547-d.pdf

