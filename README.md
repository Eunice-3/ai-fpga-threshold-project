# AI-Assisted FPGA Threshold Monitor

## Project Overview
This project simulates an FPGA-based threshold monitoring system integrated with AI decision-making.

## System Flow
Sensor Input → FPGA Logic (Simulated) → AI Model → Decision

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
