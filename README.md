# 3-Phase BLDC/PMSM Motor Controller

An experimental 3-phase motor controller designed from the ground up to explore power electronics, embedded systems, and modern motor control techniques.

The project aims to develop a low-power, 24V BLDC/PMSM motor drive with a custom MOSFET-based three-phase inverter and an STM32 microcontroller.

## AI Usage

No AI-generated designs, schematics, PCB layouts, or firmware are used in this project. AI tools may be used exclusively for research purposes, such as understanding technical concepts, exploring documentation, and finding relevant engineering resources.

All engineering decisions, hardware designs, PCB layouts, and software implementations are developed by the project author.

## Project Goals

- Design a custom 3-phase MOSFET inverter.
- Implement PWM generation and SVPWM.
- Develop Field-Oriented Control (FOC).
- Implement phase-current sensing and closed-loop current control.
- Experiment with rotor position feedback using Hall sensors and encoders.
- Explore motor control, power electronics, and PCB design.

## Target Specifications

| Parameter | Target |
|---|---|
| DC Input Voltage | 24V |
| Maximum Output Power | 100W |
| Motor Type | 3-Phase BLDC/PMSM |
| Power Stage | 6-MOSFET inverter |
| Controller | STM32 |
| Switching Frequency | 20kHz (target) |
| Modulation | SPWM / SVPWM |
| Motor Control | FOC (planned) |
| Rotor Feedback | Hall sensors / Encoder |

## Development Status

This project is currently in the design and development phase. Hardware design, firmware, and control algorithms will be developed incrementally.

**Note:** This is an educational and experimental project, not a production-ready motor controller.
