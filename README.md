# MV-Switchgear-Automation-System

## Project Description
This project implements an MV switchgear automation and monitoring system using Structured Text (ST) in CODESYS.

The system handles circuit breaker control, interlocking logic, alarm management, and real-time measurement monitoring through Modbus communication with field devices.

---

## System Overview

The system includes:

- Circuit Breaker control with interlocking logic
- Earth switch and motor spring monitoring
- Local/Remote operation mode
- Alarm management (protection, auxiliary supply, gas, etc.)
- Electrical measurements (voltage, current, power, frequency, temperature)
- Safety logic with automatic tripping conditions

---

## Communication

The system communicates via Modbus RTU with:

- Prometer 100 (electrical measurements)
- NT511 (temperature monitoring)

---

## Simulation

Simulation was performed using ModSim and ModScan tools based on the provided Modbus register mappings for both devices.

---

## Project Deliverables

- Technical Offer (System Architecture + BOM)
- CODESYS Structured Text implementation
- Modbus simulation files (ModSim / ModScan configuration)
