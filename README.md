## EXPERIMENT NO. 1 – VERIFICATION OF KIRCHHOFF'S LAWS

| **Name:** | | **Reg. No.:** | |
|---|---|---|---|
| **Date:** | | **Batch / Section:** | |

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

<img width="1600" height="824" alt="image" src="https://github.com/user-attachments/assets/f8ed2c46-aa68-4657-8ae3-6cc78245a1da" />


**Figure 1:** KVL verification circuit

### B. KCL circuit diagram

<img width="1600" height="895" alt="image" src="https://github.com/user-attachments/assets/a3c8a4da-53ac-4db3-a416-acdef25a60fc" />


**Figure 2:** KCL verification circuit

## SIMULATION USING PROTEUS

Build the KVL and KCL circuits in Proteus using the same resistor values and supply voltage as the hardware circuit. Place DC voltmeters and DC ammeters from the Virtual Instruments mode, run the simulation, and paste a screenshot showing the meter readings for each circuit.

### A. KVL simulation

<img width="1495" height="862" alt="Screenshot 2026-10-07 154413" src="https://github.com/user-attachments/assets/12d13363-3ffc-459b-8fba-5a408e50a6da" />

**Figure 3:** Proteus simulation of KVL circuit

### B. KCL simulation

<img width="1495" height="862" alt="Screenshot 2026-10-07 154413" src="https://github.com/user-attachments/assets/1974b1c2-bd72-4ac1-899c-885347d88e74" />

**Figure 4:** Proteus simulation of KCL circuit

## OBSERVATION AND TABULATION

### A. KVL – Voltage measurements

<img width="1042" height="215" alt="image" src="https://github.com/user-attachments/assets/b391ebbb-471f-4a45-b379-3990d527e97e" />


### B. KCL – Current measurements

<img width="1036" height="222" alt="image" src="https://github.com/user-attachments/assets/123616be-e8bb-4100-bc76-c1417a0ae7ff" />


## CALCULATIONS

### A. KVL

According to KVL, **Vs = VR1 + VR2 + VR3**.

Substitute the observed values and verify that the algebraic sum of the voltage drops is approximately equal to the supply voltage.

<img width="1052" height="1600" alt="image" src="https://github.com/user-attachments/assets/f073c684-3797-4a4e-ad17-57c6ed6db747" />


**Figure 5:** KVL calculation

### B. KCL

According to KCL, **It = I1 + I2 + I3**.

Substitute the observed values and verify that the total current entering the node is approximately equal to the sum of the branch currents.

<img width="1068" height="1600" alt="image" src="https://github.com/user-attachments/assets/6e79e5c5-c83d-46b9-8593-f70f4e132996" />
<img width="1600" height="1274" alt="image" src="https://github.com/user-attachments/assets/eeb19ac5-df0d-4a05-913b-a9f3ff2f4276" />


**Figure 6:** KCL calculation

## RESULT

Thus, Kirchhoff's Voltage Law (KVL) and Kirchhoff's Current Law (KCL) were verified experimentally and through Proteus simulation for the given circuits.
