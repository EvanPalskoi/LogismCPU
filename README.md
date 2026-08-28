# 16-bit custom Logism CPU Design
A custom 8-bit CPU built from scratch in Logism, with a hand made ALU, register file, and ISA.

# Real time Assembly instruction execution:
The circuit is executing the instructions found in Assembly Instructions (swapping values between Address 32 and 33 without using another register

![Circuit Walkthrough](media/logism_video.gif)

# Components
### Main Circuit
This connects the control unit, registers, ALU and memory busses.
![Main CPU Circuit](media/logism_cpu_main_sc.png)

### Control Unit
This decodes opcodes
![Control Unit](media/control_unit.png)

### ALU
Handles all mathematical and logical operations
![ALU Component](media/ALU.png)

### Register Files and Memory
stores temporary data
* **Register File:** Holds active data
![Register File](media/reg_file.png)
* **16-Bit Register:** Standard register used for data manipulation
![16-Bit Register](media/16-bit_reg.png)
* **1-Bit Register:** Used for flags and small state tracking
![1-Bit Register](media/1-bit_reg.png)

### Prerequisites
To open and run this project, Logism is required.
