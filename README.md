# EE301 Analog Circuits Course Project

## Project Title
**Design of Beta Multiplier, Cascode Current Mirror, and Cascode Amplifier in 22nm (0.8 V Supply) and 180nm (1.8 V Supply) Technologies**

## Project Description
This project involves the design and analysis of three fundamental analog circuit blocks:
1. **Beta Multiplier Circuit**
2. **Cascode Current Mirror**
3. **Cascode Amplifier**

The circuits were designed and implemented using two different CMOS technologies:
- **180nm technology** with a supply voltage of 1.8 V
- **22nm technology** with a supply voltage of 0.8 V

The goal was to achieve specified design parameters, including required gain, bandwidth, power dissipation, and proper biasing.

---

## Key Features
- **DC Analysis**:
  - Verified DC offset, output voltage swing, and input signal voltage.
- **AC Analysis**:
  - Analyzed frequency response, gain, and bandwidth.
- **Low Power Consumption**:
  - Ensured power dissipation remained under 5 mW in both technologies.

## Design Procedures
The project followed a structured design methodology:
1. Each circuit was designed individually, ensuring all MOSFETs operated in the saturation region.
2. Bias voltages were calculated and fine-tuned to meet performance requirements.
3. The circuits were cascaded and tested to ensure proper integration without undesirable cascading effects.

## Tools and Techniques
- **Simulation Tools**:
  - MAGIC layout for CMOS designs.
  - .spice simulations for DC and AC analysis.
- **Technology Specifications**:
  - 180nm technology: `VDD = 1.8 V`
  - 22nm technology: `VDD = 0.8 V`

---

## Performance Summary

### 180nm Technology
- **Gain**: 26 dB
- **Bandwidth**: 3.347 MHz
- **Unity Gain Bandwidth**: 86.909 MHz
- **Power Dissipation**: 0.3667 mW

### 22nm Technology
- **Gain**: 26 dB
- **Bandwidth**: 856.66 KHz
- **Unity Gain Bandwidth**: 22.069 MHz
- **Power Dissipation**: 5.44 µW

---

## Team
- **Submitted By**: Komal(2022EEB1182)
- **Supervised By**: Prof. Mahendra Sakare
- **Date of Submission**: 9th November 2024

---

## Acknowledgments
This project was completed as part of the EE301 Analog Circuits course. We extend our gratitude to our supervisor for guidance and support throughout the project.
