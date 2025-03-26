# RISC-V Single-Cycle Processor (Lab Task)

## Overview

This project implements a **RISC-V single-cycle processor** as part of a lab task. The design follows a simplified version of the **RISC-V ISA**, focusing on **All-types of instructions**. The implementation includes key components such as the **instruction fetch unit, control unit, ALU, register file, and data memory**.

## Features

- Supports a subset of **RISC-V instructions**  
- **Single-cycle execution model**  
- **Modular design** for ease of understanding and modification  
- Simulated using a **hardware description language (HDL)** and evaluated through **waveform analysis**  

## Components

### 1. Instruction Fetch Unit
- Fetches instructions from memory  
- Provides the instruction to the decode stage  

### 2. Control Unit
- Decodes the instruction opcode  
- Generates control signals for different processor components  

### 3. ALU (Arithmetic Logic Unit)
- Performs **arithmetic and logical operations**  
- Takes inputs from the register file and immediate values  

### 4. Register File
- Contains **32 registers**  
- Supports **read and write operations**  

### 5. Data Memory
- Stores data for **load/store instructions**  
- Read/Write operations controlled by the control unit  

## Simulation & Testing

- The design is verified using simulation tools such as **ModelSim/Verilog simulator**.  
- A **testbench** is provided to check the execution of basic **RISC-V instructions**.  
- **Waveform analysis** is performed to validate instruction execution and data flow.  

## Getting Started

To begin exploring the RV32I 5-Stage Pipeline Processor:

  **1)** Clone this repository to your local machine:

     git clone "mygitpath" your_pc_folder

  **2)** Navigate to the project directory:

     cd your_pc_folder

  **3)** Refer to the documentation provided in the repository to build, simulate, or test the processor implementation.

  **4)** Experiment with the design, explore optimizations, or integrate additional features to further enhance the processor's capabilities.
