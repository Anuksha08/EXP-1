## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** |ANUKSHA S | **Reg. No.:** |26016254|
|---|---|---|---|
| **Date:** |11.11.26 | **Batch / Section:** |260DJ121|

---

## AIM

a. To verify Kirchhoff's Voltage Law (KVL) for the given circuit.

b. To verify Kirchhoff's Current Law (KCL) for the given circuit.

## APPARATUS REQUIRED

| S. No. | Component | Range / Rating | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Resistor | 1 kΩ | 3 |
| 2 | DC Voltmeter | 0–30 V | 3 |
| 3 | DC Ammeter | 0–0.2 A | 3 |
| 4 | Breadboard | — | 1 |
| 5 | Regulated Power Supply (RPS) | 0–30 V | 1 |
| 6 | Connecting wires | As required | As required |
| 7 | Simulation software | Proteus Design Suite | 1 |

## THEORY

**Kirchhoff's Voltage Law (KVL):** The algebraic sum of all voltage rises and voltage drops around any closed loop in an electrical circuit is zero.

**Kirchhoff's Current Law (KCL):** The algebraic sum of currents at any node is zero. In other words, the total current entering a node is equal to the total current leaving the node.

## PROCEDURE

### A. Verification of KVL

1. Connect the circuit as shown in the KVL circuit diagram.
2. Ensure that the RPS output is set to zero volts before switching it on.
3. Check that all meters are correctly connected and set to their zero positions.
4. Switch on the RPS and gradually set the required input voltage within the specified range.
5. Measure and record the voltage across each resistor using the voltmeters.
6. Repeat the measurements for different input-voltage values and tabulate the readings.

### B. Verification of KCL

7. Connect the circuit as shown in the KCL circuit diagram.
8. Ensure that the RPS output is set to zero volts before switching it on.
9. Check that all meters are correctly connected and set to their zero positions.
10. Switch on the RPS and gradually set the required input voltage within the specified range.
11. Measure and record the current in each branch using the ammeters.
12. Repeat the measurements for different input-voltage values and tabulate the readings.

## CIRCUIT DIAGRAMS

### A. KVL circuit diagram

<img width="1600" height="1109" alt="image" src="https://github.com/user-attachments/assets/c0d26498-b54d-4d5e-9092-ec3e4235347a" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1600" height="895" alt="image" src="https://github.com/user-attachments/assets/3016d6bd-2870-49fb-8d3f-f8a04548e85f" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1495" height="862" alt="Screenshot 2026-10-07 154413" src="https://github.com/user-attachments/assets/e01340c0-8d0a-4089-bdfd-410d34cd263a" />


**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1177" height="832" alt="image" src="https://github.com/user-attachments/assets/3115fe70-528e-4ff3-8e11-623af5732705" />


**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

<img width="1042" height="215" alt="image" src="https://github.com/user-attachments/assets/0beb7092-244c-4857-9237-90bebdec304d" />


### B. KCL – Current measurements

<img width="1036" height="222" alt="image" src="https://github.com/user-attachments/assets/95954e9f-954d-4297-8629-4686e449895b" />


## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="1052" height="1600" alt="image" src="https://github.com/user-attachments/assets/43c77326-7a48-439b-8c1c-be708985b7bc" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="1068" height="1600" alt="image" src="https://github.com/user-attachments/assets/0b6618a3-1225-4f36-89aa-9eb7fa8d0cf5" />
<img width="1600" height="1274" alt="image" src="https://github.com/user-attachments/assets/19279a1b-04e1-470f-9b84-a1c90eca78af" />



**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
