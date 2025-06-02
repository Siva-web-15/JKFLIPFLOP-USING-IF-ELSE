# JKFLIPFLOP USING IF ELSE
# NAME:SIVABALAN M
# REG No:21224230269
**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.
![300541519-a649c30b-232b-4558-b188-fd6c09845180](https://github.com/user-attachments/assets/8bf24edd-3784-4da3-81ca-c9e44f42c6ae)



This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![300541618-c4360742-e8a8-4937-b089-c46c0433f9a3](https://github.com/user-attachments/assets/b70c2281-59be-4dc8-8183-991532bbb539)


 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
![300541696-6c275261-a6d5-4c37-a3a7-1e88ca11c4cd](https://github.com/user-attachments/assets/97a62f56-b8e1-4c09-bbe5-5c0a875f944d)
 

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![300541801-5174f41b-0ce0-4329-a372-6d1943ea6673](https://github.com/user-attachments/assets/168a21a9-5a2e-40f3-804d-4d2b53379361)


The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next s!
tate Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**PROGRAM**

![image](https://github.com/user-attachments/assets/3dfcf119-d243-43ed-96c2-f7ad82a6e6df)

**TRUTH TABLE**
![434133879-fdab606d-854f-4092-b725-bcc6abbcf50d](https://github.com/user-attachments/assets/50d6a5d3-b014-4f9a-b687-4a2bc7e9c714)


**RTL LOGIC FOR FLIPFLOPS**

![434133995-da4b4f1f-e7ec-4553-8d4b-9fdc8eedd459](https://github.com/user-attachments/assets/fafa8902-b079-403b-8a97-38f93d0ca31a)

**WAVEFORM**
![434134157-a59ef99b-66cb-4d01-8a3d-d837afbd13cf](https://github.com/user-attachments/assets/0a46eb00-40c8-4179-a338-3647461f54e6)

**RESULTS**
Thus the given JK flipflops are implemented using and their operations are verified using Verilog programming.
