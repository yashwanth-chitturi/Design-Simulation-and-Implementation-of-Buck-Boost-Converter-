# Buck-Boost Converter Design and Analysis

A hardware implementation and experimental analysis of a **Buck-Boost DC-DC Converter** developed as part of the **Electrical Machines, Power Electronics Laboratory (EMPEL)** course. The project investigates converter operation in both **Continuous Conduction Mode (CCM)** and **Discontinuous Conduction Mode (DCM)** through hardware implementation and waveform analysis.

![Hardware](https://img.shields.io/badge/Implementation-Hardware-blue)
![Power Electronics](https://img.shields.io/badge/Domain-Power%20Electronics-success)
![Converter](https://img.shields.io/badge/Converter-Buck--Boost-orange)

---

##  Project Overview

The objective of this project was to design, implement, and experimentally validate a Buck-Boost DC-DC converter capable of operating in both buck and boost modes.

The converter was tested under various duty cycles to study its electrical characteristics, switching behavior, and efficiency. Experimental measurements were performed using laboratory instruments to verify theoretical converter operation.

---

##  Key Features

- Designed and implemented a hardware Buck-Boost DC-DC Converter.
- Operated the converter in both Buck and Boost modes.
- Analyzed converter performance under Continuous Conduction Mode (CCM) and Discontinuous Conduction Mode (DCM).
- Measured Inductor Current (IL), Switch Current (ISW), and Inductor Voltage (VL) waveforms.
- Evaluated converter efficiency through experimental testing.
- Validated theoretical analysis using hardware implementation.

---

##  Specifications

| Parameter | Value |
|------------|--------|
| Input Voltage | 15 V |
| Output Voltage | 10–20 V |
| Switching Frequency | 7.5 kHz |
| Output Current | 1 A |

---

##  Hardware Components

- MOSFET Switch
- Inductor
- Fast Recovery Diode
- Output Capacitor
- PWM Driver Circuit
- DC Power Supply
- Digital Oscilloscope
- Resistive Load

---

##  Experimental Analysis

### Buck Mode (CCM)

- Output Voltage: **−7.33 V**
- Duty Cycle: **0.37**
- Efficiency: **65.84%**

Observed Waveforms:

- Inductor Current (IL)
- Switch Current (ISW)
- Inductor Voltage (VL)

---

### Boost Mode (CCM)

- Output Voltage: **−17.1 V**
- Duty Cycle: **0.62**
- Efficiency: **68.91%**

Observed Waveforms:

- Inductor Current (IL)
- Switch Current (ISW)
- Inductor Voltage (VL)

---

### DCM Operation

The converter transitions from Continuous Conduction Mode to Discontinuous Conduction Mode when the switching frequency is reduced, causing the inductor current to become discontinuous.

---

##  Results

- Successfully implemented a hardware Buck-Boost converter.
- Verified Buck and Boost converter operation experimentally.
- Observed CCM and DCM operating characteristics.
- Validated switching waveforms using oscilloscope measurements.
- Compared practical results with theoretical analysis.

---

##  Tools Used

- Power Electronics Laboratory Kit
- Digital Oscilloscope
- DC Power Supply
- Function Generator

---


##  Report

The complete project report, including hardware setup, waveform analysis, experimental observations, and conclusions, is available in the **Report** folder.

---

##  Author

**Yashwanth Sri Sai Chitturi**
**Mamindlapelly Sai Krishna**

B.Tech Electrical Engineering

Interests: Power Electronics • Embedded Systems • FPGA Design • Computer Architecture • AI Hardware Accelerators
