## 2. Basic differential amplifier

### AIM :

Design and Analyze the MOS differential amplifier circuitfor the following specifications
VDD=3.3V,P<3mw Vicm=1.65V Vocm 1.7V vp=0.5V


###  Components Required:

N-MOSFET(nmos4),Resistors(3.5k,0.5k,voltage source)

### basic differential amplifier

A differential amplifier amplifies the difference between two input signals. It rejects common noise and is used in signal processing. It is a key part of op-amps and instrumentation
circuits.

### Working principle

A basic differential amplifier takes two input signals and finds the difference between them.It makes this difference bigger while ignoring any common noise in both signals. If one input is higher, the output goes positive; if the other is higher, the output goes negative. If bothinputs are the same, the output is zero.

# procedure

* Open the LTspice software, merge the library file for getting accurate values of NMOS.
* select the required components
* change the mosfet length and width, adjusting the id
* let do the dc analysis
* then select the sine wave For AC analysis, we should do some changes like converting DC source to sinusoidal signal
* then do transient analysis

### CIRCUIT:1



### DC Analysis:



### AC analysis



### CIRCUIT:2 


### DC Analysis


### Transient Analysis


### AC Analysis


### CIRCUIT 3


### DC Analysis


### Transient Analysis


### AC Analysis


### Inference

1. Differential Gain - The amplifier strengthens the difference between two input signals, making it perfect for applications that need accurate signal boosting.
2. Common-Mode Rejection - It effectively removes unwanted noise common to both inputs,making it great for noise-free signal processing.
3. Biasing and Stability - Proper biasing keeps the amplifier working steadily, though small changes in resistor values or transistor properties can affect its performance.
4. Practical Limitations - The output may slightly differ from theoretical expectations due to component variations, transistor imperfections, and power supply fluctuations.

