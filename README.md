# D-FLIPDLOP-NEGEDGE

**AIM:**

To implement  D flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**D Flip-Flop**

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/48c81fe8-bc3f-40e7-95e2-519fc155ad51)

This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/e5f3fda7-68ec-4a3a-a0a4-cf6f9cc4ab55)

Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D

![image](https://github.com/naavaneetha/D-FLIPDLOP-NEGEDGE/assets/154305477/8592c0d8-2917-4142-91b9-d6c30dd891d2)

Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

**Procedure**

Inputs:
D: The data input.
clk: The clock signal.
reset (optional): To initialize or reset the output.

Output:
Q: The current state (output).
Q_bar (optional): The inverted output.

Behavior:
On the rising edge of the clock:
Q is set to the value of D.
If a synchronous or asynchronous reset is present, the output is reset to 0 (or a defined state).


**PROGRAM**
DEVELOPED BY :RAM PRASATH S , Register Number :24900195

![DE ex8 code](https://github.com/user-attachments/assets/709464c3-22a6-4f94-b58e-fbcceefd1a38)


**RTL LOGIC FOR FLIPFLOPS**

![DE ex8 diagram](https://github.com/user-attachments/assets/705841e2-1893-4a8a-a943-636ecd44c4d5)


**TIMING DIGRAMS FOR FLIP FLOPS**

![DE ex8 waveform](https://github.com/user-attachments/assets/aabfd524-37ed-4baa-93aa-20cf39177f98)


**RESULTS**

The implementation  D flipflop using verilog and validating their functionality using their functional tables
