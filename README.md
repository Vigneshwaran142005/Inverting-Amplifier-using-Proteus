# Inverting-Amplifier-using-Proteus
## Experiment 1
Design and Simulation of Inverting Amplifier using Op-Amp (μA741) in Proteus
## Aim
To design and simulate an Inverting Amplifier using μA741 Op-Amp in Proteus Design Suite and verify the voltage gain experimentally.
## Apparatus / Components Required
S.No	Component	Specification	Quantity
1	Op-Amp IC	μA741	1
2	Resistor R1	10 kΩ	1
3	Resistor Rf	100 kΩ	1
4	Signal Generator	Sine wave, 1 kHz	1
5	Dual DC Power Supply	+15V, -15V	1
6	CRO / Oscilloscope	Virtual (Proteus)	1
7	Connecting Wires	—	As required
## Theory
An Inverting Amplifier is a closed-loop amplifier configuration where the input signal is applied to the inverting terminal (-) of the op-amp through resistor R1, and feedback resistor Rf is connected between output and inverting terminal.
The non-inverting terminal (+) is grounded.
## Circuit Description
•	Pin 2 → Inverting input
•	Pin 3 → Non-inverting input (Grounded)
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → -15V
The input sine wave is applied through R1 and output is taken from pin 6.
## Circuit Diagram
![WhatsApp Image 2026-02-23 at 8 46 51 AM](https://github.com/user-attachments/assets/12d7359b-94f3-4105-a0c4-f04142ede0de)

## Tabulation
       | S.No | Input Voltage (Vin) | Theoretical Gain (Av) | Theoretical Vout (Av × Vin) | Practical Vout (Proteus) |
       | ---- | ------------------- | --------------------- | --------------------------- | ------------------------ |
       |   1    | 0.5 V               | -10                   | -5 V                        | -4.95 V                  |
       |   2    | 1 V                 | -10                   | -10 V                       | -9.8 V                   |
       |   3    | 1.5 V               | -10                   | -15 V                       | -14.5 V                  |
       |   4    | 2 V                 | -10                   | -20 V                       | **Saturates ≈ -13 V**    |
Input Voltage (Vin)	Theoretical Gain (Av)	Theoretical Vout	Practical Vout (Proteus)
## Simulation Procedure (Proteus)
1.	Open Proteus Design Suite
2.	Select components:
o	μA741
o	Resistors
o	AC Signal Generator
o	Oscilloscope
3.	Connect circuit as per inverting amplifier configuration.
4.	Set:
o	R1 = 10kΩ
o	Rf = 100kΩ
o	Input = 1V, 1kHz sine wave
5.	Apply ±15V power supply.
6.	Run simulation.
7.	Observe input and output waveforms on CRO.
##  Waveform Observation
![WhatsApp Image 2026-02-23 at 8 46 51 AM (1)](https://github.com/user-attachments/assets/3d5fdc3d-e4b1-4f95-856b-9d09fb89c9e6)

•	Input: Sine wave
•	Output: Amplified sine wave
•	Phase Shift: 180°
•	Gain ≈ -10
## Result
The Inverting Amplifier using μA741 Op-Amp was successfully designed and simulated in Proteus.
The practical output voltage closely matches the theoretical value.
The gain obtained is approximately -10, and the output waveform is inverted with respect to the input waveform.

