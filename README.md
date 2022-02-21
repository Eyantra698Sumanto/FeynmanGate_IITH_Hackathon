# Feynman Gate 
## Abstract

Reversible logic is very effective and important in the formation of low power circuit. 

The aim of low power VLSI circuits is to reduce the power dissipation. 

It is called reversible when it reverses the output. 

It is completely specified N-output, n-input Boolean function and it maps each output to a unique input and vice versa. 

The reversible logic operations do not remove the information and has zero heat dissipation. 

The circuit operates in a backward operation, allows reproducing the inputs from the outputs and consumes zero power. 

A Feynman Gate is one such reversible gate.[1]
## Reference Circuit Details

Feynman Gate is a 2×2 reversible logic gate. 

The inputs are A, B, and the outputs are P, Q. P=A gives the outputs of this gate, Q=A+B. 

Thus the input A gets passed to P and Q gives the output as an XOR of A and B. 

The Quantum cost of an FG is calculated to be 1. Fan-out is not used in reversible logic. 

Cab of the gate is used to get the desired net. The corresponding circuit using MOSFETs has been as shown. 

Here eight CMOS transistor has been used in this design. The model can be used as an improved EXOR gate with a reversibility feature. 

It can be easily verified from the output waveform that design works well for both forward and reverse directions. 

There is also a CMOS pass transistor as shown in the figure M5 and M6 to pass the inputs. [2]

## Reference Circuit Diagram
![image](https://user-images.githubusercontent.com/58599984/154889700-b35bc623-3efb-44f8-8d4b-2e2a40f61463.png)
## Reference Circuit Waveform
![image](https://user-images.githubusercontent.com/58599984/154903055-e02b3b92-689a-4925-94e1-c61876f0a318.png)

## Simulation in Synopsys
## Schematic
![image](https://user-images.githubusercontent.com/58599984/154891572-6f504e7d-fdc1-433e-a665-da131d4305ba.png)
![image](https://user-images.githubusercontent.com/58599984/154891605-1ea09787-dec1-4506-a486-50f9b0292113.png)

## Parameters set for Voltage Source for Input A
![image](https://user-images.githubusercontent.com/58599984/154890823-6743f686-9eed-4966-9420-56bd3a0ee0e2.png)
## Parameters set for Voltage Source for Input B
![image](https://user-images.githubusercontent.com/58599984/154891712-f6c4bfae-d422-4c86-8f40-9874719ed230.png)

## Transient Settings
![image](https://user-images.githubusercontent.com/58599984/154890716-35c2d360-befc-4476-9041-c360d751f378.png)

## Output Waveform
![image](https://user-images.githubusercontent.com/58599984/154890627-af11bc3b-d098-4f2b-9100-996d878b7612.png)

## Acknowlegement
1. Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd. - kunalpghosh@gmail.com
2. Chinmay panda, IIT Hyderabad
3. Sameer Durgoji, NIT Karnataka
## References
1.	U. Kumar, L. Sahu and U. Sharma, "Performance evaluation of reversible logic gates," 2016 International Conference on ICT in Business Industry & Government (ICTBIG), 2016, pp. 1-4, doi: 10.1109/ICTBIG.2016.7892693.
2.	A. K. Rajput, S. Chouhan and M. Pattanaik, "Low Power Boolean Logic Circuits using Reversible Logic Gates," 2019 International Conference on Advances in Computing, Communication and Control (ICAC3), 2019, pp. 1-6, doi: 10.1109/ICAC347590.2019.9036799.

