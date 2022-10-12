Implementation-of-Low-Power-Configurable-Multi-Clock-Digital-System
 
 -It is responsible of receiving commands through UART receiver to do different system functions
 
 Project phases:
- RTL Design from scratch of system block (ALU, Register, UART TX/RX, Synchronous FIFO, Integer Clock Divider, Clock Gating, Synchronizer, Main Controller).
- Integrate and verify functionality through self-checking testbench.
- Constraining the system using synthesis TCL scripts.
- Synthesize and optimize the design using design compiler tool.
- Physical implementation of the system passing through ASIC flow phases and generate GDS File
- Verify Functionality post-layout considering the actual delays.


System blocks:

 ![image](https://user-images.githubusercontent.com/82594179/195421535-5746806d-c558-4961-87dd-9bb474b7ecc6.png)
