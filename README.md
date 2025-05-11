## 🔬 Capstone Project – Tritium Extraction System for Fusion Reactors

As part of a three-member team for our UC Berkeley Capstone Project, we designed a **tritium extraction system** for compact fusion reactors, under the guidance of **Dr. Guanyu Su**. The project was entirely simulation-based and utilized **Star-CCM+** and **SolidWorks**. While we were already experienced in **SolidWorks**, this was our first time working with **Star-CCM+**.

Together, we developed a realistic model simulating **tritium transport from FLiBe to the vacuum**, including **permeation through metallic walls**. After building the core model collaboratively, I led a **sensitivity study** on segment length to analyze how **heat exchanger geometry affects tritium extraction efficiency**.

Through this experience, I gained practical skills in:
- **Meshing complex geometries**
- **Defining custom boundary conditions** using user-defined equations
- Using **passive scalars** to simulate species transport in a multiphysics environment

### 🧾 One-Pager
![Screenshot](onepager.png)

### 🎤 Conference Presentation
We presented our work at the **ANS Student Conference 2025**.  
📎 [View the presentation slides](./ANS.pdf)

### 📄 Full Report
The complete project report is available [here](./Project_Tritium_Extraction_FinalReport_2025.pdf).

# 🔬 Optimizing Tritium Recovery Using Commercial Heat Exchangers (PCHE)

**Team 42**  
**Contributors:** Sean Shitamoto, Esteban Labrador, Sascha Turovskiy  
**Advisors:** Guanyu Su, Ben Li  
**Date:** Spring 2025  
**Tools Used:** STAR-CCM+, SolidWorks, CFD Modeling, Custom Passive Scalar Transport Models

---

## 🌍 Project Objective

Design and optimize a tritium extraction system for fusion reactors using **commercial Printed Circuit Heat Exchangers (PCHEs)**. Our goal was to improve the mass transfer of tritium from FLiBe (a molten salt breeder fluid) into a vacuum using realistic geometries and CFD simulation methods, providing a practical path forward for commercial **fusion fuel recovery**.

---

## ⚙️ Technical Overview

- **Physics Modeled:** Passive scalar tritium diffusion through FLiBe and 316SS into a vacuum.
- **Simulation Platform:** Siemens STAR-CCM+
- **Geometry:** Zigzag microchannel PCHE design
- **Key Performance Metric:** Mass Transfer Coefficient (MTC) in [m/s]
- **Simulation Regimes:** Laminar and Turbulent

---

## 📈 Parametric Studies Conducted

| Study Type               | Key Finding                                                                 |
|--------------------------|------------------------------------------------------------------------------|
| **Channel Size**         | Larger channels slightly improve MTC and reduce pressure drop.               |
| **Channel Orientation**  | "1-1 Vertical" and "Burger" performed best for MTC.                         |
| **Bend Angle**           | Sharper angles (60°) increase MTC, but also drastically increase pressure.  |
| **Segment Length**       | Shorter segments lead to higher MTC by enhancing flow disruption.           |

### 💡 Insight:
An optimal balance between MTC and pressure drop is critical. The **100° bend angle** with **4.75mm segments** performed best when considering both efficiency and power requirements.

---

## 🧪 Key Results

- **Best Average MTC (Turbulent, 60° Bend):** 1.43×10⁻³ m/s  
- **Lowest Pressure Drop (180° Bend, Laminar):** 1.33×10⁷ Pa/(m³/s)
- **Tritium Concentration Used:** 1.52×10⁻⁴ mol/m³  
- **CFD Model Verified with Mesh Sensitivity and Interface Conditions**

---

## 🔄 Next Steps

1. **Experimental Validation:** Build a physical test rig using selected geometry.
2. **Material Studies:** Explore alternative materials like Vanadium, Haynes alloys, etc.
3. **Advanced Modeling:** Implement K-Ω turbulence model and transient boundary conditions.

---

## 📄 Full Report

[📘 Download Final Report (PDF)](./Project_Tritium_Extraction_FinalReport_2025%20(1).pdf)

---

## 🔗 References

Includes foundational papers on tritium transport in FLiBe, heat exchanger design, and ARC fusion system integration. Full citations in the report.

---

> _This project demonstrates how commercial engineering designs can be repurposed for next-generation nuclear fusion applications, combining efficiency, safety, and practicality for tritium recovery systems._
