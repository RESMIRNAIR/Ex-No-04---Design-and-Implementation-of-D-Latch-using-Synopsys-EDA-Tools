# Ex No: 04 - Design and Implementation of D Latch using Synopsys EDA Tools

## Aim
The aim is to design, implement, and analyze a D Latch using Synopsys EDA tools, ensuring accurate sequential logic operation through waveform analysis and performance verification.

## Tools Required

### Synopsys EDA Suite
- Synopsys Custom Compiler – For CMOS schematic design.
- Synopsys PrimeWave Design Environment – For simulation setup and waveform analysis.
- Synopsys PrimeSim HSPICE / PrimeSim – For circuit simulation and analysis.

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**
- Linux-based operating system compatible with the installed Synopsys tools.

## Procedure:
### 1. Launch Synopsys Custom Compiler Environment :
     Open Synopsys Custom Compiler and set up the working library.
     Create a new design library and associate it with the appropriate CMOS technology PDK.
     Create a new schematic cell view for the CMOS circuit design.
### 2. Schematic Design:
    Launch Synopsys Custom Compiler and create a new design library associated with the appropriate CMOS technology PDK.
    Create a new schematic cell view for the required CMOS complex gate.
    Select the required NMOS and PMOS transistors from the technology library based on the given Boolean expression.
    Connect the NMOS and PMOS transistors appropriately to implement the required pull-down and pull-up networks.
    Connect the transistor gate terminals to the corresponding input signals.
    Connect the supply terminals to VDD and GND, ensuring that the bulk terminals are connected to the appropriate supply potentials.
    Connect DC voltage sources (VDC) to provide the required supply voltage and pulse voltage sources (VPULSE) to apply the input signals.
    Connect the output terminal to the common node of the pull-up and pull-down networks.
### 3. Simulation:
    Check the schematic for errors and verify the electrical connections.
    Create a testbench for the CMOS design.
    Launch Synopsys PrimeWave Design Environment.
    Select the appropriate simulator, such as PrimeSim HSPICE.
    Configure transient analysis to study the time-domain response.
    Set the simulation parameters, including supply voltage, input pulse period, rise time, fall time, and simulation stop time.
    Run the simulation and verify the simulation results.


## Circuit Diagram

### 1. D Latch
![image](https://github.com/user-attachments/assets/ddf3603b-bdfd-41f2-8a98-4ad93862fd9f)

### 2. Schematic of D Latch

<img width="1188" height="708" alt="WhatsApp Image 2026-11-03 at 11 21 13 AM" src="https://github.com/user-attachments/assets/661d7a95-d2ac-4ea0-a48c-7e53568ae59f" />

### 3. Transient Response Setup

<img width="1600" height="596" alt="WhatsApp Image 2026-11-03 at 11 22 46 AM" src="https://github.com/user-attachments/assets/99b95e2e-1770-4be0-8aa6-da0f60e871ca" />

## Output

### 1. Transient Analysis Output

<img width="1600" height="659" alt="WhatsApp Image 2026-11-03 at 11 21 42 AM" src="https://github.com/user-attachments/assets/1d44e4ec-c39d-4bd1-8b6d-db0b405c3a8a" />

## Results
1. Successfully designed the D Latch using Synopsys EDA tools.
2. The simulation results verified the correct sequential logic behavior, ensuring that the Q output correctly follows the D input during the positive half cycle of the clock.
3. The waveform analysis demonstrated the expected timing behavior and performance of the D Latch circuit.
