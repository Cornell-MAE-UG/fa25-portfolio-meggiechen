---
layout: project
title: ENGRD 2210 Portfolio Project: Heat Exchanger
description: Thermodynamic analysis of a liquid–liquid heat exchanger under different flow configurations
technologies: [Thermodynamics, Heat Transfer, Energy Balances]
image: /assets/images/heat_exchanger.jpg
---

<img src="/assets/images/heat_exchanger.jpg" alt="Heat exchanger setup" style="max-width:100%; height:auto;">

In this project, I analyzed the performance of a small-scale liquid–liquid heat exchanger used in ENGRD 2210. The goal was to understand how heat exchanger performance depends on flow configuration (parallel flow versus counterflow) and operating conditions such as flow rate. Using temperature measurements collected during the experiment, I applied energy balance concepts to compare heat transfer between different configurations.

---

## Device Description and Real-World Context

Heat exchangers are devices designed to transfer thermal energy between two fluid streams without allowing the fluids to mix. They are commonly used in automotive radiators, HVAC systems, power plants, and electronics cooling systems. Although the heat exchanger used in this experiment is lab-scale, it operates according to the same thermodynamic principles as industrial heat exchangers.

This experiment focused on comparing parallel flow and counterflow configurations and examining how changes in flow rate affect heat transfer effectiveness.

---

## Qualitative Description of the System

The experimental setup consisted of a heat exchanger connected to two closed water loops: a hot loop and a cold loop. The hot loop circulated water from a reservoir heated using an immersion heater. The cold loop circulated water from an insulated reservoir containing cold water and ice. Each loop was driven by a pump, allowing the flow rate to be adjusted between fast and slow settings.

As the fluids flowed through the heat exchanger, thermal energy was transferred from the hot stream to the cold stream through the exchanger walls. No mass transfer occurred between the two streams. The system was operated in both parallel flow and counterflow configurations.

---

## System Modeling and Assumptions

For analysis, the heat exchanger was treated as a steady-state control volume. Mass flow rates were assumed constant during each trial, and changes in kinetic and potential energy were neglected. No shaft work was performed. While the system was not perfectly insulated, heat losses to the surroundings were assumed to be small relative to the heat transferred between the two fluid streams.

---

## Governing Relationships

- Mass balance: mass flow into the system equals mass flow out
- Energy balance: heat lost by the hot fluid equals heat gained by the cold fluid
- Performance comparison based on temperature change and effectiveness

---

## Experimental Data

### Parallel Flow — Fast
- Hot inlet temperature: 43.0 °C  
- Hot outlet temperature: 31.8 °C  
- Cold inlet temperature: 17.5 °C  
- Cold outlet temperature: 29.3 °C  

### Parallel Flow — Slow
- Hot inlet temperature: 42.8 °C  
- Hot outlet temperature: 30.5 °C  
- Cold inlet temperature: 21.6 °C  
- Cold outlet temperature: 28.9 °C  

### Counterflow — Fast
- Hot inlet temperature: 44.8 °C  
- Hot outlet temperature: 28.2 °C  
- Cold inlet temperature: 18.0 °C  
- Cold outlet temperature: 31.8 °C  

### Counterflow — Slow
- Hot inlet temperature: 45.6 °C  
- Hot outlet temperature: 25.3 °C  
- Cold inlet temperature: 13.8 °C  
- Cold outlet temperature: 33.4 °C  

---

## Temperature Change Calculations

### Parallel Flow — Fast
Hot-side temperature change:  
43.0 °C − 31.8 °C = **11.2 °C**

Cold-side temperature change:  
29.3 °C − 17.5 °C = **11.8 °C**

---

### Parallel Flow — Slow
Hot-side temperature change:  
42.8 °C − 30.5 °C = **12.3 °C**

Cold-side temperature change:  
28.9 °C − 21.6 °C = **7.3 °C**

---

### Counterflow — Fast
Hot-side temperature change:  
44.8 °C − 28.2 °C = **16.6 °C**

Cold-side temperature change:  
31.8 °C − 18.0 °C = **13.8 °C**

---

### Counterflow — Slow
Hot-side temperature change:  
45.6 °C − 25.3 °C = **20.3 °C**

Cold-side temperature change:  
33.4 °C − 13.8 °C = **19.6 °C**

---

## Heat Exchanger Effectiveness

Effectiveness was calculated by comparing the actual temperature drop of the hot fluid to the maximum possible temperature difference between the hot and cold inlets.

### Parallel Flow
- Fast flow effectiveness:  
11.2 ÷ (43.0 − 17.5) = **0.44**

- Slow flow effectiveness:  
12.3 ÷ (42.8 − 21.6) = **0.58**

---

### Counterflow
- Fast flow effectiveness:  
16.6 ÷ (44.8 − 18.0) = **0.62**

- Slow flow effectiveness:  
20.3 ÷ (45.6 − 13.8) = **0.64**

---

## Discussion

The results show that counterflow operation consistently produced larger temperature changes and higher effectiveness than parallel flow. Reducing the flow rate also increased heat transfer by increasing the time the fluids spent inside the heat exchanger. These trends align with heat exchanger theory and explain why counterflow designs are commonly used in real engineering applications.

---

## Reflection

This project demonstrated how thermodynamic principles such as energy balances and effectiveness can be applied to real systems. Working with experimental data emphasized the importance of assumptions, steady-state operation, and measurement limitations when analyzing physical devices.
