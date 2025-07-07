---
layout: single
title: "Switching Devices"
permalink: /research/switching_devices/
author_profile: true
---

## 💡 Overview

Switching devices are the cornerstone of modern power electronics. They determine the performance, efficiency, and compactness of power conversion systems. Key technologies include:

- **IGBTs (Insulated-Gate Bipolar Transistors)** for medium- to high-voltage applications  
- **SiC MOSFETs** for high-efficiency, high-frequency systems  
- **GaN HEMTs** for ultra-fast switching and compact converter designs

---

## ⚙️ Device Comparison

| Device Type | Switching Speed | Voltage Rating | Efficiency | Typical Use Case |
|-------------|------------------|----------------|------------|------------------|
| IGBT        | Medium           | 600V–1700V     | Moderate   | Inverters, motor drives |
| SiC MOSFET  | High             | 650V–3300V     | High       | EV inverters, DC-DC converters |
| GaN HEMT    | Very High        | 100V–650V      | Very High  | Fast chargers, RF, telecom |

---

## 🔬 Testing and Measurement

### 1. Power Loss Analysis
- **Double Pulse Testing (DPT)** for switching loss evaluation  
- **Conduction and switching loss separation**  
- **Waveform acquisition** using isolated voltage and current probes

### 2. Thermal Modelling
- **Thermal impedance measurement** (Z<sub>th</sub>) via step-response or structure function  
- **Cauer and Foster model fitting**  
- Analysis of **dead-time**, parasitics, and layout impacts on heat dissipation

---

## 🧠 Research Focus

### 🔍 ANN-based Device Modelling for Converter Optimisation

My ongoing research includes the development of an **ANN-based switching device library** that supports:

- Fast loss and thermal prediction for IGBTs, SiC, and GaN devices  
- Device selection and optimisation in AI-driven converter design workflows  
- Integration with buck, DAB, and LLC converter topologies

---

> 📩 Interested in collaborative modelling or sharing measurement data? [Email me](mailto:fulong.li@ieee.org)
