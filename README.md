# AI-Assisted FPGA Threshold Monitor

## Project Overview
This project simulates an FPGA-based threshold monitoring system integrated with AI decision-making.

## System Flow
Sensor Input → FPGA Logic (Simulated) → AI Model → Decision

System Diagram

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
The FPGA logic is simulated in Python. The system can be deployed on real FPGA hardware such as Zynq.
