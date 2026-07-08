# UART Protocol Verification using Verilog | Vivado

## Overview

This project implements and verifies a Universal Asynchronous Receiver Transmitter (UART) protocol using Verilog HDL. The design includes both UART Transmitter and UART Receiver modules with a self-checking testbench to validate data transmission and reception through simulation.

The project was developed and simulated using Xilinx Vivado.

---

## Objectives

- Design UART Transmitter (TX)
- Design UART Receiver (RX)
- Verify serial communication between TX and RX
- Simulate different data frames
- Validate received data using a self-checking testbench

---

## Tools Used

- Verilog HDL
- Xilinx Vivado 2020.1
- XSim Simulator

---

## Project Structure

```
UART-PROTOCOL-VERIFICATION
│
├── uart_tx.v
├── uart_rx.v
├── uart_tb.v
├── README.md
```

---

## Features

- UART Transmitter
- UART Receiver
- 8-bit Data Transfer
- Start Bit Detection
- Stop Bit Detection
- Self-checking Testbench
- Behavioral Simulation
- RTL Schematic Generation

---

## Simulation Flow

1. Design UART TX module
2. Design UART RX module
3. Create Testbench
4. Run Behavioral Simulation
5. Observe Waveforms
6. Verify Received Data
7. Generate RTL Schematic

---

## Test Cases

| Test Case | Status |
|------------|--------|
| Send 0x55 | ✅ Pass |
| Receive 0x55 | ✅ Pass |
| Send 0xAA | ✅ Pass |
| Receive 0xAA | ✅ Pass |

Simulation successfully verified correct UART communication.

---

## Simulation Results

The simulation confirms:

- Successful serial transmission
- Accurate data reception
- Correct start and stop bit detection
- No transmission errors

Console Output:

```
PASS: Received 0x55 correctly
PASS: Received 0xAA correctly
Simulation Complete
```

---

## RTL Schematic

The RTL schematic generated in Vivado confirms the successful synthesis of the UART Transmitter and Receiver architecture.

---

## Learning Outcomes

Through this project, I learned:

- UART Communication Protocol
- Serial Data Transmission
- Verilog RTL Design
- Testbench Development
- Behavioral Simulation
- Debugging using Waveforms
- RTL Analysis in Vivado

---

## Applications

- Embedded Systems
- FPGA Development
- Microcontroller Communication
- IoT Devices
- Sensor Interfaces
- Industrial Automation

---

## Future Improvements

- Configurable Baud Rate
- UART FIFO Buffer
- Parity Bit Support
- Multiple Stop Bits
- Error Detection
- Loopback Testing

---

## Author

**Narasimha Lakkimsetty**

Electronics and Communication Engineering (ECE)

Interested in:
- Digital Design
- FPGA
- ASIC Design
- RTL Design
- Verification
- VLSI

Connect with me on LinkedIn and GitHub for more VLSI and FPGA projects.
