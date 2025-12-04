#**EX.NO:** 1  # EXPERIMENTAL VERIFICATION OF AMPLIFIER INVERTING, NON INVERTING , DIFFERENTIAL AMPLIFIER AND INSTRUMENTATION AMPLIFIERS
**DATE:**  
---

## AIM
To design and construct an Inverting, Non-Inverting, Differential and Instrumentation amplifiers.

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K, 10K, 2.2K | 2 |
| 7 | Connecting wires and probes | As required | — |

---

## THEORY

Op-amp in open-loop configuration has limited application due to its enormous open-loop gain. Controlled gain can be achieved by taking a part of the output signal to the input through feedback.  
This is called a **Closed-Loop Configuration**.

The four basic types of closed-loop amplifier configurations are:
- Inverting amplifier  
- Non-inverting amplifier  
- Differential amplifier
- Instrumentation amplifier 

The entire configuration can operate with either AC or DC input.
		
 

---

### **Inverting Amplifier**

This is the most widely used op-amp configuration.  
The output voltage Vo  is fed back to the inverting input terminal through the  Rf - R1 network.  
The negative sign in gain indicates a **phase shift of 180°**.


Acl = -RF/R1

PIN DIAGRAM

![20251203_222442](https://github.com/user-attachments/assets/d56f9220-bf7a-499f-ad4f-60cfb2a43e30)

CIRCUIT DIAGRAM: INVERTING AMPLIFIER:

![20251203_222447](https://github.com/user-attachments/assets/6ebc9fa8-fdde-4e18-8d83-5085230be350)

MODEL GRAPH 

![20251203_222631](https://github.com/user-attachments/assets/8798e315-1eea-4699-94f6-ac9665239069)

DESIGN:

![20251203_222649](https://github.com/user-attachments/assets/371ae962-5db8-4d29-ae0e-1b5230a86f6b)

Inverting amplifier:

A = -Rf/R1
Take  A = 10
Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

PROCEDURE:
Inverting amplifier:

1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1 & compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.


## TABULATION

![20251203_222452](https://github.com/user-attachments/assets/d8e84041-0a37-46fe-b79a-d59e84bdc8bc)

---

## OUT PUT WAVEFORM AND DISCUSSION 

![20251203_222512](https://github.com/user-attachments/assets/3536bd5c-35ae-4038-94af-b71bfcb2b991)


---
### **Non-Inverting Amplifier**

If the signal is applied to the non-inverting input terminal without inversion, it is called a **non-inverting amplifier**.  
Here, the output is fed back to the inverting terminal, and **no phase shift** occurs.


ACL = 1 + RF/R1


---

## CIRCUIT DIAGRAM

![20251203_222819](https://github.com/user-attachments/assets/7b616318-acea-4469-84ef-2cd5f3d25ec7)

---

## MODEL GRAPH

![20251203_222836](https://github.com/user-attachments/assets/7686eb91-d8c5-44b3-bb04-e115a44300db)

---
## DESIGN

![20251203_222649](https://github.com/user-attachments/assets/b6964574-c0fc-40e6-8dcd-9cc3f9fd7782)

---
PROCEDURE:
### **For  Non-Inverting Amplifier**
1. Select R1  as a constant value and choose a value for Rf .  
2. Connect the circuit as per the diagram.  
3. Apply constant amplitude input voltage.  
4. Measure the output voltage amplitude for different V1 using DSO.  
5. Compare practical and theoretical values of Vo .  
6. Verify that practical gain ≈ theoretical gain.  
7. Plot the input vs. output waveform for one practical case.

## TABULATION

![20251203_222908](https://github.com/user-attachments/assets/3b98ee4f-5ac6-4dcf-a0b3-f2a43d088104)

---

## OUT PUT WAVEFORM AND DISCUSSION 

![20251203_222924](https://github.com/user-attachments/assets/c256afee-5830-4b0c-af42-2e27e131b0f3)

---
## DIFFERENTIAL AMPLIFIER

A circuit that amplifies the **difference** between two input signals is called a **Differential Amplifier**.  
It is useful in instrumentation applications.  
If the two input signals are identical, the output is ideally **zero**.


A = Vo/{V2 - V1} = -Rf/R1
## CIRCUIT DIAGRAM

![20251203_223020](https://github.com/user-attachments/assets/42d7b192-4feb-4599-9758-79217df1f592)

## MODEL GRAPH

![20251203_223029](https://github.com/user-attachments/assets/63ea7862-2a0c-4362-889d-e858d267bcff)

---

## DESIGN

![20251203_223141](https://github.com/user-attachments/assets/d851754a-80d4-4330-a3e6-38716f251be6)


### **Differential Amplifier**

AV = Vo/{V1 - V2} = -Rf/R1


Take  A = 10 
⇒  Rf = 10R1   
Choose  R1 = 1kOhm, Rf = 10kOhm

---



## PROCEDURE (Differential Amplifier)
1. Select  R1, R2, R3, Rf  such that R1 = R2  and  R3 = Rf .  
2. Connect the circuit as per the circuit diagram.  
3. Apply constant inputs Vin1 and  Vin2 .  
4. Measure output voltage using DSO.  
5. Compare theoretical and practical  Vo .  
6. Verify practical ≈ theoretical output.  
7. Plot the input vs. output waveform.

---

## TABULATION (Differential Amplifier)

![20251203_223038](https://github.com/user-attachments/assets/51686b93-d203-4e65-b690-3927289858b0)

---
## OUT PUT WAVEFORM AND DISCUSSION 

![20251203_223220](https://github.com/user-attachments/assets/cc9c3701-c640-4cc8-90b5-ad22859e8315)

---
## INSTRUMENTATION AMPLIFIER

THEORY:

An instrumentation amplifier is the intermediate stage of a instrumentation system. The signal source of the instrumentation amplifier is the output of the transducer. Many transducers output do not have the ability or sufficient strength to drive the next following stages. Therefore, instrumentation amplifiers are used to amplify the low-level output signal of the transducer so that it can drive the following stages such as indicator or displays.
The major requirements of a instrumentation amplifier are precise, low-level signal amplification where low-noise, low thermal and time drifts, high input resistance & accurate closed-loop gain, low power consumption, high CMRR & high slew rate for superior performance.
The output of Instumentation amplifier is given by
Vo = RF/R1[1+ 2R’/R][V2-V1]
 

## CIRCUIT DIAGRAM: INSTRUMENTATION AMPLIFIER

![20251203_223322](https://github.com/user-attachments/assets/034c4492-eac0-4303-b375-f710b49f562d)

PROCEDURE:

1.	Select the entire resistor with the same value. Let R be the gain varying resistor with different values of resistance for simplicity let R be a constant value.
2.	Connect the circuit as shown in the circuit diagram.
3.  + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
4.	Give the input V1 and V2 to the non-inverting terminals of first & second op-amp respectively.
5.	By varying the value of RG, measure the output voltage for common mode and differential mode operation. Since RG is selected as constant value, provide different input value of V1 and V2.
6.	Check the theoretical value with the experimental value.
7.	The output voltage is obtained in the Multimeter and the input and output voltage waveforms are plotted in a graph sheet

---

## TABULATION (Instrumentation Amplifier)

![20251203_223442](https://github.com/user-attachments/assets/1d45dbfb-53b4-4eba-aff4-5e805b84b685)

---

## DESIGN

![20251203_223457](https://github.com/user-attachments/assets/916be23e-cc3b-4482-8679-a0337f7462ad)

---

## OUT PUT WAVEFORM AND DISCUSSION 


![20251203_223518](https://github.com/user-attachments/assets/a69b5bad-c122-4098-879d-9caddb3289de)

---

## RESULT

![20251203_223536](https://github.com/user-attachments/assets/5ff058f6-18b2-41b8-b4dc-7d9bbf96ae96)


![20251203_223526](https://github.com/user-attachments/assets/25006dc0-6e8b-4c7f-9d8f-1158dd9e9290)


Thus, the **Inverting**, **Non-Inverting**, **Differential**, and **Instrumentation Amplifiers** were designed and their performance successfully tested using Op-Amp IC 741.

---
