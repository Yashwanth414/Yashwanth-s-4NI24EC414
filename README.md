# EXPERIMENT-1:
Question: Given the power as P=100µw, Perform AC, DC and Transient analysis for the given circuit design by using Ltspice simulator.

### Circuit Diagram-1 :

![Capture](https://github.com/user-attachments/assets/502293a1-3c00-4db0-84ed-ca37947585df)

### Procedure:
BY using this formula P=V*I 
we get the drain current as,
Id=5.55e-005A


#### 1. DC Analysis
Go to simulate, Select the dc output print and the run the simulation.

![image](https://github.com/user-attachments/assets/ef924102-e523-4182-a514-e4dd73970e36)

This figure shows the output of dc analysis
 
  ![image](https://github.com/user-attachments/assets/11e5cc97-94ec-408a-bf4c-c5c8ad44dd46)


#### 2. AC Analysis
Go to simulate, Select the ac analysis, Give the values as shown below and run the simulation.

![image](https://github.com/user-attachments/assets/a0f7da9d-3529-4060-b0c1-7669947a6c04)

Below graph shows the output of the AC analysis.

![image](https://github.com/user-attachments/assets/b547e04e-196e-47fd-8797-e1cc9ba7eb9c)

#### 3. Transient Analysis
Go to simulate, Set the stop time as 1ms and run the simulation.
The below graph shows the output of transient analysis.

![image](https://github.com/user-attachments/assets/eee3db42-638e-430f-9aaf-1dd7c4141f70)

### Result:
* The calculated drain current from the DC analysis was 5.55e-005A, achieved with NMOS dimensions: Length = 175nm, Width = 178nm.
* The circuit maintained stable performance across the tested frequency range.
* The circuit responded well to variations and ensured stable operation

### Inference:
* The drain current helps determine whether the MOSFET is operating in the saturation region.
* The MOSFET's operating region depends on the gate-to-source voltage (VGS).
* Coupling and bypass capacitors significantly influence the frequency response.
* The gain of the circuit is directly influenced by the MOSFET parameters.
* To perform the simulation, specific component library files must be added to the simulation software.
* Adjusting the length and width of the MOSFET allows for precise control over the drain current in the simulation.

### Circuit Diagram-2:

![image](https://github.com/user-attachments/assets/aa571835-21ea-4ca5-942e-f7bcbca4cc25)

### PROCEDURE
#### 1. DC Sweep analysis
This analysis used to find the vin value.
Go to simulate, Select a dc sweep analysis, Give the values as shown below and run the simulation.

![image](https://github.com/user-attachments/assets/33d5b92c-a501-43eb-a134-30cc05e216e1)

Below graph shows the VTC curve and the value of vin as 0.8v

![image](https://github.com/user-attachments/assets/c9c9e3d4-0a57-4356-b84d-8a821b9c8448)

Now give the input as 

![image](https://github.com/user-attachments/assets/bb1c591b-4d3a-4344-b2f2-80372af8567a)

The length and width of the NMOS and PMOS tranistor as shown in the below figure

![image](https://github.com/user-attachments/assets/283c39f0-5eea-4292-a833-91b5da308a6b)

![image](https://github.com/user-attachments/assets/3641668c-d141-48e5-b0e2-aac11a9b014c)

#### 2. DC Analysis
Go to simulate, Select the dc output print and the run the simulation.

![image](https://github.com/user-attachments/assets/daef7b7e-e64c-4510-8f23-e55121daa510)

#### 3. AC Analysis
Go to simulate, Select the ac analysis, Give the values as shown below and run the simulation.

![image](https://github.com/user-attachments/assets/6d629781-a005-40d2-87f3-e2b178e2ad4c)

Below graph shows the output of the AC analysis.

![image](https://github.com/user-attachments/assets/cbcdaa25-38e7-4266-8034-4108e9402a90)

#### 4. Transient analysis
Go to simulate, Set the stop time as 1ms and run the simulation.
The below graph shows the output of transient analysis.

![image](https://github.com/user-attachments/assets/c0f8f7c7-ed03-4867-8433-047d7c474862)

### RESULT:

* By adjusting the channel dimensions (L, W) of both MOSFETs (M1 & M2), the desired current was successfully achieved at:
* M1: L = 500nm, W = 950nm
* M2: L = 300nm, W = 1020nm
* The circuit exhibited a gain of 3.8 dB with a phase shift close to 180 degrees, aligning well with theoretical expectations.
* The circuit responded efficiently to input variations, indicating stable operation and reliable performance.
020nm

### INFERENCE:
* The DC sweep analysis provided the input DC voltage.
* By adjusting the MOSFET dimensions, the corresponding drain current values were calculated during simulation.
* Both M1 and M2 were varied to achieve the desired drain current.
* For AC analysis, the AC amplitude was set to 1, ensuring proper evaluation.
* The DC sweep analysis also provided the Voltage Transfer Characteristic (VTC) curve at the output.
