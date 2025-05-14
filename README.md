# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER
# NAME:VINOTH K R
# REG.NO:212224050060
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

![Screenshot 2025-04-21 221428](https://github.com/user-attachments/assets/f892de61-6fd0-4b58-a14c-8c1d0f7827f3)



**PROGRAM**



![image](https://github.com/user-attachments/assets/247dfc34-091d-417b-8e15-a1d83789e545)


**RTL LOGIC FOR SISO Shift Register**


![image](https://github.com/user-attachments/assets/3b90564f-ccd4-402b-90bb-7f5fd5f07835)





**TIMING DIGRAMS FOR SISO Shift Register**

![image](https://github.com/user-attachments/assets/b25c5ef6-7aa3-4e8d-8595-66863f7bbac0)


**RESULTS**

Thus,SISO Shift Register using verilog and validating their functionality using their functional tables has successful execution of the program.
