# AI-Assisted FPGA Threshold Monitor

## Project Overview
This project simulates an FPGA-based threshold monitoring system integrated with AI decision-making.

## System Flow
Sensor Input → FPGA Logic (Simulated) → AI Model → Decision

## System Diagram
<img width="278" height="381" alt="image" src="https://github.com/user-attachments/assets/c97f0d3f-ae05-4680-99f6-7f8e5c3fd0cb" />

## Features
- Simulated FPGA threshold logic
- AI-based classification (Normal / Warning / Critical)
- Python implementation using Jupyter Notebook

## Results
| Value | FPGA Output | AI Decision |
|------|------------|------------|
| 2    | NORMAL     | Normal     |
| 5    | NORMAL     | Normal     |
| 8    | NORMAL     | Normal     |
| 9    | HIGH       | Warning    |
| 12   | HIGH       | Warning    |
| 15   | HIGH       | Critical   |

## Note

- The FPGA logic in this project is simulated using Python to demonstrate system behavior without requiring physical hardware.
- The design follows a hardware–software co-design approach, where FPGA performs preprocessing and AI handles high-level decision-making.
- The system can be implemented on real FPGA hardware such as Zynq by replacing the simulated logic with Verilog code.
- The AI decision stage can be automated using APIs (e.g., NVIDIA models), but manual interaction was used here for simplicity.
- This project demonstrates a scalable pipeline that can be extended to real-world applications such as sensor monitoring, anomaly detection, and smart control systems.
- Simulation was used as a standard engineering practice to verify system functionality before hardware deployment.

## Future Work

- Implement the FPGA logic using Verilog on a physical board.
- Integrate real-time sensor data instead of simulated inputs.
- Automate AI decision-making using APIs.
- Extend the system for real-time monitoring applications.
