# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

Open Quartus Prime software.

Create a new Verilog project and name it appropriately.

Write the Verilog code for a 4-bit SISO shift register.

Compile the design to check for syntax errors.

Generate the RTL schematic to verify the logical connections of the design.

Create a simulation file to verify the functionality of the SISO shift register.

Apply test cases for various input patterns.

Observe the output at each clock cycle to ensure correct data shifting.

Compare the results against the functional table to validate correctness.

Generate the timing diagram to illustrate the propagation of data through the flip-flops.

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:Thamizh.S RegisterNumber:24900483

*/
![Screenshot 2024-12-17 152951](https://github.com/user-attachments/assets/bb6ba95d-da25-4443-97b1-5da5ee0d7c07)

**RTL LOGIC FOR SISO Shift Register**

![Screenshot 2024-12-17 153011](https://github.com/user-attachments/assets/4cae66a6-ef8f-4249-aae9-9420c6a8a328)

**TIMING DIGRAMS FOR SISO Shift Register**
![Screenshot 2024-12-17 153937](https://github.com/user-attachments/assets/f66267e7-9dde-41a2-a1cc-81dfc8bb7726)

**RESULTS**

RTL Logic for SISO Shift Register: The schematic confirms the proper interconnection of flip-flops.
Timing Diagram: Demonstrates the correct shifting of bits through the flip-flops on clock pulses.
The SISO shift register is implemented successfully, and its functionality matches the expected behavior from the functional table.

