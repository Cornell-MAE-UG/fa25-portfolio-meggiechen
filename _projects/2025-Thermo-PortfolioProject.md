---
layout: project
title: ENGRD 2210 Portfolio Project: Heat Exchanger
description: Thermodynamic analysis of a liquid–liquid heat exchanger under different flow configurations
technologies: [Thermodynamics, Heat Transfer, Energy Balances]
image: /assets/images/heat_exchanger.jpg
---

In this project, I analyzed the performance of a small-scale liquid–liquid heat exchanger used in ENGRD 2210. The goal was to understand how heat exchanger effectiveness depends on flow configuration (parallel flow vs. counterflow) and operating conditions such as flow rate. Using temperature measurements collected during the experiment, I applied mass, energy, and effectiveness relationships to evaluate heat transfer performance and connect experimental results to thermodynamic theory.

---

## Device Description and Real-World Context

Heat exchangers are widely used in engineering applications such as automotive radiators, HVAC systems, power plants, and electronics cooling systems. Their purpose is to transfer thermal energy between two fluid streams without allowing the fluids to mix. While the heat exchanger used in this experiment is lab-scale, it operates based on the same physical principles as industrial heat exchangers.

In this experiment, a water-to-water heat exchanger was used to compare parallel flow and counterflow configurations and to study how changes in flow rate influence heat transfer. These comparisons provide insight into why counterflow heat exchangers are often preferred in real-world designs.

---

## Qualitative Description of the System

The experimental setup consisted of a heat exchanger connected to two closed water loops: a hot loop and a cold loop. The hot loop circulated water from a reservoir heated using an immersion heater, while the cold loop circulated water from an insulated reservoir containing cold water and ice. Each loop was driven by a pump, allowing the flow rates to be adjusted between fast and slow conditions.

As the fluids flowed through the heat exchanger, heat was transferred from the hot stream to the cold stream through the exchanger walls. No mass transfer occurred between the streams. The system was operated in both parallel flow, where the two streams enter the exchanger from the same end, and counterflow, where the streams enter from opposite ends. Temperatures were measured at the inlets and outlets of each stream to quantify heat transfer.

---

## System Modeling and Assumptions

For analysis, the heat exchanger was modeled as a steady-state control volume. Each fluid stream was assumed to have constant mass flow rate, and changes in kinetic and potential energy were neglected. No shaft work was performed. Although the heat exchanger was not perfectly insulated, heat loss to the surroundings was assumed to be small compared to the heat exchanged between the two fluid streams. These assumptions are consistent with standard heat exchanger analyses.

---

## Governing Equations

**Mass Balance (steady state):**
\[
\dot{m}_{in} = \dot{m}_{out}
\]

**Energy Balance (heat exchanger control volume):**
\[
\dot{m}_h c_p (T_{h,in} - T_{h,out}) = \dot{m}_c c_p (T_{c,out} - T_{c,in})
\]

**Effectiveness Definition:**
\[
\varepsilon = \frac{Q_{\text{actual}}}{Q_{\text{max}}}
\]

For equal heat capacity rates, this simplifies to:
\[
\varepsilon = \frac{T_{h,in} - T_{h,out}}{T_{h,in} - T_{c,in}}
\]

---

## Experimental Data

### Parallel Flow

**Fast Flow**
- \(T_{h,in} = 43.0^\circ\text{C}\)
- \(T_{h,out} = 31.8^\circ\text{C}\)
- \(T_{c,in} = 17.5^\circ\text{C}\)
- \(T_{c,out} = 29.3^\circ\text{C}\)

**Slow Flow**
- \(T_{h,in} = 42.8^\circ\text{C}\)
- \(T_{h,out} = 30.5^\circ\text{C}\)
- \(T_{c,in} = 21.6^\circ\text{C}\)
- \(T_{c,out} = 28.9^\circ\text{C}\)

---

### Counterflow

**Fast Flow**
- \(T_{h,in} = 44.8^\circ\text{C}\)
- \(T_{h,out} = 28.2^\circ\text{C}\)
- \(T_{c,in} = 18.0^\circ\text{C}\)
- \(T_{c,out} = 31.8^\circ\text{C}\)

**Slow Flow**
- \(T_{h,in} = 45.6^\circ\text{C}\)
- \(T_{h,out} = 25.3^\circ\text{C}\)
- \(T_{c,in} = 13.8^\circ\text{C}\)
- \(T_{c,out} = 33.4^\circ\text{C}\)

---

## Temperature Change Calculations

### Parallel Flow

**Fast Flow**
\[
\Delta T_h = 43.0 - 31.8 = 11.2^\circ\text{C}
\]
\[
\Delta T_c = 29.3 - 17.5 = 11.8^\circ\text{C}
\]

**Slow Flow**
\[
\Delta T_h = 42.8 - 30.5 = 12.3^\circ\text{C}
\]
\[
\Delta T_c = 28.9 - 21.6 = 7.3^\circ\text{C}
\]

---

### Counterflow

**Fast Flow**
\[
\Delta T_h = 44.8 - 28.2 = 16.6^\circ\text{C}
\]
\[
\Delta T_c = 31.8 - 18.0 = 13.8^\circ\text{C}
\]

**Slow Flow**
\[
\Delta T_h = 45.6 - 25.3 = 20.3^\circ\text{C}
\]
\[
\Delta T_c = 33.4 - 13.8 = 19.6^\circ\text{C}
\]

---

## Heat Exchanger Effectiveness

### Parallel Flow

**Fast Flow**
\[
\varepsilon = \frac{11.2}{43.0 - 17.5} = 0.44
\]

**Slow Flow**
\[
\varepsilon = \frac{12.3}{42.8 - 21.6} = 0.58
\]

---

### Counterflow

**Fast Flow**
\[
\varepsilon = \frac{16.6}{44.8 - 18.0} = 0.62
\]

**Slow Flow**
\[
\varepsilon = \frac{20.3}{45.6 - 13.8} = 0.64
\]

---

## Discussion

The results show that counterflow operation consistently produced larger temperature changes and higher effectiveness than parallel flow. Additionally, reducing the flow rate increased heat transfer by allowing more time for thermal energy exchange. These trends match theoretical expectations and help explain why counterflow heat exchangers are commonly used in real engineering systems.

---

## Reflection

This project reinforced how thermodynamic principles such as energy balances and effectiveness can be applied to real systems. Working with experimental data also highlighted the importance of assumptions, steady-state operation, and measurement limitations when analyzing physical devices.
