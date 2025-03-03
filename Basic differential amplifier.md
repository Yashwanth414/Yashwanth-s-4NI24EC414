# Basic differential amplifier

## AIM :

Design and Analyze the MOS differential amplifier circuitfor the following specifications
VDD=3.3V,P<3mw Vicm=1.65V Vocm 1.7V vp=0.5V



##  Components Required:

N-MOSFET(nmos4),Resistors(3.5k,0.5k,voltage source)

## Theory

## basic differential amplifier

A differential amplifier amplifies the difference between two input signals. It rejects common noise and is used in signal processing. It is a key part of op-amps and instrumentation
circuits.

## Types of modes

*Differential mode 

*common mode

## Working principle

A basic differential amplifier takes two input signals and finds the difference between them.It makes this difference bigger while ignoring any common noise in both signals. If one input is higher, the output goes positive; if the other is higher, the output goes negative. If bothinputs are the same, the output is zero.

## procedure

* Open the LTspice software, merge the library file for getting accurate values of NMOS.
* select the required components
* change the mosfet length and width, adjusting the id
* let do the dc analysis
* then select the sine wave For AC analysis, we should do some changes like converting DC source to sinusoidal signal
* then do transient analysis
* run the simulation
* verify the result

# CIRCUIT:1
![1 ckt](https://github.com/user-attachments/assets/a5c02d0c-7316-4828-8b79-21dbc66e33ad)


## DC Analysis:
![1 dc](https://github.com/user-attachments/assets/81f1a6bc-ce27-4cad-91fc-81eb46208ea6)

Id1=Id2=0.45ma 

Iss =0.9ma 

vicm=1.65v

## Transient Analysis:

Input and output waveform

![1 tran](https://github.com/user-attachments/assets/d22409f5-3033-47df-8aef-822ff2992bc0)

## AC analysis
![1 ac](https://github.com/user-attachments/assets/5a36bad2-bfc8-4fa3-9aa4-716cafd0e626)

# CIRCUIT:2 
![2 ckt](https://github.com/user-attachments/assets/83de9dca-81f0-467e-8140-c2508f971968)

## DC Analysis
![2 dc](https://github.com/user-attachments/assets/84f95b69-c839-404a-b2b1-7893370bdaa0)

## Transient Analysis

Input and output waveform

![2 tran](https://github.com/user-attachments/assets/5739e54f-a00d-42e1-9954-dbeea4d5c244)

## AC Analysis
![2 ac](https://github.com/user-attachments/assets/8cd33435-3ba3-4834-a6ad-b5273a295c12)


# CIRCUIT 3:
![3 ckt](https://github.com/user-attachments/assets/0fbaa5db-a0c3-4c05-97d5-de06cee1df9d)


## DC Analysis
![3 dc](https://github.com/user-attachments/assets/ebd12f4f-8907-4cd3-a58b-3ccc23dc0823)

## Transient Analysis

Input and output waveform

![3 tran](https://github.com/user-attachments/assets/4615ba24-23eb-4a4a-b3a5-87e3bd53f047)

## AC Analysis
![3 ac](https://github.com/user-attachments/assets/c3186c74-8eaa-4d4e-a91f-c4448cbf6fde)

# Inference

1. Differential Gain - The amplifier strengthens the difference between two input signals, making it perfect for applications that need accurate signal boosting.
2. Common-Mode Rejection - It effectively removes unwanted noise common to both inputs,making it great for noise-free signal processing.
3. Biasing and Stability - Proper biasing keeps the amplifier working steadily, though small changes in resistor values or transistor properties can affect its performance.
4. Practical Limitations - The output may slightly differ from theoretical expectations due to component variations, transistor imperfections, and power supply fluctuations.

