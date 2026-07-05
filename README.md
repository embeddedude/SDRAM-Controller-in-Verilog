# SDRAM-Controller-in-Verilog
A complete SDRAM Controller designed from scratch in Verilog HDL. This project implements the complete command sequencing and timing required for SDRAM communication using a modular, FSM-based architecture
# SDRAM Controller in Verilog

A complete implementation of an SDRAM Controller in Verilog HDL along with detailed theory notes explaining SDRAM architecture, timing, command protocol, and controller design. This repository serves as both a learning resource and a complete RTL implementation.

---

# Objectives

- Understand SDRAM architecture
- Learn SDRAM timing constraints
- Design an FSM-based SDRAM controller
- Implement initialization, refresh, read and write logic
- Verify the design using simulation
- Build a strong foundation before learning DDR memories

---

# Theory

## 1. Memory Hierarchy

- Registers
- Cache
- SRAM
- SDRAM
- DDR SDRAM
- Flash Storage

Why SDRAM is used in modern systems.

---

## 2. DRAM Fundamentals

- DRAM Cell (1 Transistor + 1 Capacitor)
- Read Operation
- Write Operation
- Charge Leakage
- Need for Refresh

---

## 3. SDRAM Architecture

- Memory Banks
- Rows
- Columns
- Address Bus
- Data Bus
- Control Signals

---

## 4. SDRAM Pins

- CLK
- CKE
- CS#
- RAS#
- CAS#
- WE#
- BA0, BA1
- A0-A12
- DQ
- DQM

Purpose of each signal.

---

## 5. SDRAM Commands

- NOP
- ACTIVE
- READ
- WRITE
- PRECHARGE
- AUTO REFRESH
- SELF REFRESH
- LOAD MODE REGISTER
- BURST TERMINATE

---

## 6. Timing Parameters

- tRCD
- tRP
- tRAS
- tRC
- tRFC
- tWR
- CAS Latency
- Burst Length

---

## 7. SDRAM Initialization Sequence

- Power-up Delay
- PRECHARGE ALL
- AUTO REFRESH
- LOAD MODE REGISTER
- Ready State

---

## 8. Refresh Mechanism

- Why Refresh is Needed
- Refresh Interval
- Auto Refresh
- Self Refresh

---

## 9. Mode Register

- Burst Length
- Burst Type
- CAS Latency
- Write Burst Mode

---

## 10. Read Operation

- ACTIVE
- Wait tRCD
- READ Command
- CAS Latency
- Data Output

---

## 11. Write Operation

- ACTIVE
- WRITE Command
- Data Input
- DQM Masking
- PRECHARGE

---

## 12. Finite State Machines

- Initialization FSM
- Refresh FSM
- Read FSM
- Write FSM
- Top-Level Controller FSM

---

## 13. SDRAM Timing Diagrams

- Initialization Timing
- Read Timing
- Write Timing
- Refresh Timing

---

# RTL Modules

- Initialization Controller
- Auto Refresh Controller
- Self Refresh Controller
- Mode Register Controller
- Read Controller
- Write Controller
- Top-Level SDRAM Controller

---

# Verification

- Individual Testbenches
- Micron SDRAM Model
- Waveform Analysis
- Functional Verification

---


# Skills Gained

- RTL Design
- Verilog HDL
- FSM Design
- SDRAM Protocol
- Timing Analysis
- Digital Design
- Memory Controller Design
- Verification
- Waveform Debugging

---

# Future Improvements

- SDR SDRAM Controller
- DDR Controller
- DDR2 Controller
- DDR3 Controller
- AXI Interface
- Wishbone Interface
- FPGA Implementation
