# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:
<img width="955" height="420" alt="image" src="https://github.com/user-attachments/assets/6decdc47-87f7-4e88-9841-beca2e6b6826" />


## AC INPUT WAVEFORM:
<img width="935" height="472" alt="image" src="https://github.com/user-attachments/assets/79b42ce7-8319-495d-8e16-cf09d24cfad5" />


## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)
<img width="932" height="470" alt="image" src="https://github.com/user-attachments/assets/22516cb9-c11f-40ac-83dd-e9c52edc0b25" />

## SIGNAL OUTPUT(WITH FILTER)
<img width="932" height="471" alt="image" src="https://github.com/user-attachments/assets/5504a10a-b5a0-4fd6-92e2-6bccf6ca5971" />


## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
