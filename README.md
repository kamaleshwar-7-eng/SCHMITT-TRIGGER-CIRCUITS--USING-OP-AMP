# SCHMITT-TRIGGER-CIRCUITS--USING-OP-AMP
# AIM:
To design the Schmitt trigger circuit using Op-amp IC 741.
# APPARATUS REQUIRED:
| S.No | Name of the Apparatus                          | Range        | Quantity |
|------|-----------------------------------------------|-------------|----------|
| 1    | Function Generator                            | 3 MHz       | 1        |
| 2    | DSO                                           | 30 MHz      | 1        |
| 3    | Dual RPS                                      | (0 – 30) V  | 2        |
| 4    | Op-Amp (µA741)                                | —           | 1        |
| 5    | Bread Board                                   | —           | 1        |
| 6    | Resistors (1K, 1k, 39K,)                      | —           | 1 each   |
| 7    | Connecting wires and probes                   | As required | —        |

# THEORY:

The circuit shows an inverting comparator with positive feedback. This circuit converts irregular shaped wave forms to a square wave or pulse. The circuit is known as the Schmitt trigger (or) squaring circuit. The input voltage Vin changes the state of the output Vo every time it exceeds certain voltage levels called the upper threshold voltage VUT and lower threshold voltage VLT.
When Vo= - Vsat, the voltage across R1 is referred to as lower threshold voltage, VLT. When Vo=+Vsat, the voltage across R1 is referred to as upper threshold voltage VUT. The comparator with positive feedback is said to exhibit hysteresis, a dead band condition.
 
# DESIGN:

1.	Select the desire value of Vut & Vlt with same magnitude & opposite polarity. Let VUT = 0.3V & VLT = -0.3V.
2.	For Op-amp 741C ± Vsat ≡ ±12V. And assume Vref = 0, Since the another end of R1 is grounded.
3.	If Vo = +Vsat the voltage at the positive terminal will be (voltage from potential divider R1 & R2).
VUTP = [R1/(R1+R2 )](+Vsat)
VLTP = [R1/(R1+R2 )](-Vsat) 0.3=[R1/(R1+R2 )](+12)
0.3/12=[R1/(R1+R2 )]
0.025(R1+R2)=R1
0.025R2=(1-0.025)R1 R2=(0.975/0.025)R1 R2 = 39 R1
Assume R1=1KΩ
R2=39 KΩ
# PROCEDURE:
1.	Design the value of circuit components and select VUT & VLT as given in the design procedure.
2.	Connect the circuit as shown in the circuit diagram.
3.	Apply the input signal to the input terminal of op-amp & set VUT & VLT values.
4.	Note down the readings from the output waveform.

# CICUIT DIAGRAM:
<img width="596" height="422" alt="image" src="https://github.com/user-attachments/assets/8a8c3132-5c84-41ea-965e-e5ebd23c1eda" />

# MODEL GRAPH:
<img width="548" height="416" alt="image" src="https://github.com/user-attachments/assets/f741280b-b7e5-4dfb-8fb2-5f4c28cfb968" />


# PRACTICAL GRPAH:
<img width="600" height="770" alt="WhatsApp Image 2026-05-21 at 10 47 30 PM" src="https://github.com/user-attachments/assets/751a396e-7de0-4a0e-a018-3d34f4d3d5e2" />



# TABULATION:

| Signal Type          | Amplitude (V) | Time Period (ms) | Frequency (KHz) |
|----------------------|--------------|------------------|----------------|
| Sine Wave Input      |    5.40      |        0.33      |        3       |
| Square Wave Output   |    13.20     |        0.33      |        3       |

  # RESULT:
Thus a Schmitt trigger is designed and tested using op-amp IC 741.



