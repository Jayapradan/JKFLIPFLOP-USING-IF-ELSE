## NAME:JAYAPRADAN

## REG NO:24900886

## EXP NO 5: IMPLEMENTATION  OF JKFLIPFLOP 

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK FLIP-FLOP**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

## PROCEDURE: 

 1.Launch Quartus on your computer and create a new project: Go to File → New Project Wizard.
 Specify the project name, directory, and top-level entity name (e.g., JK_FlipFlop).
 Create the JK Flip-Flop Circuit and implement the JK Flip-Flop by writing VHDL/Verilog code. Go to
 File → New → Select Verilog File.
 Compile the Project Click on Processing → Start Compilation.
 Fix any syntax or schematic errors if present.
 Simulate the Circuit: Go to Tools → University Program VWF.
 Define the inputs for J, K, and CLK in the waveform editor.
 Run the simulation and observe the waveforms.
 Verify the Results. Compare the simulated results with the truth table for a JK Flip-Flop

**PROGRAM**

![WhatsApp Image 2024-12-26 at 11 33 21_f0f50eb2](https://github.com/user-attachments/assets/3d27764a-e015-40fd-ac70-71a206c06b9b)


**RTL LOGIC FOR FLIPFLOPS**

![WhatsApp Image 2024-12-26 at 11 33 20_1db83955](https://github.com/user-attachments/assets/191121fe-c8ff-4524-a101-4bdd0eb7cfd8)


**TIMING DIGRAMS FOR FLIP FLOPS**

![WhatsApp Image 2024-12-26 at 11 33 20_0bf357c5](https://github.com/user-attachments/assets/dbb0b685-ae26-433a-88df-8e7d22621678)


**RESULTS**

 Designed and verified the implimentation of JK flipflop circuit and truthtable in quartus ii using
 verilog programming successfully
