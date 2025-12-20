---
layout: project
title: ENGRD 2210 Portfolio Project: Heat Exchanger
description: Thermodynamic analysis of a liquid–liquid heat exchanger under different flow configurations
technologies: [Thermodynamics, Heat Transfer, Energy Balances]
image: /assets/images/heat_exchanger.jpg
---

<img src="/assets/images/heat_exchanger.jpg" alt="Heat exchanger setup" style="max-width:100%; height:auto;">

In this project, I analyzed the performance of a small-scale liquid–liquid heat exchanger used in ENGRD 2210. The goal was to understand how heat exchanger effectiveness depends on flow configuration (parallel flow vs. counterflow) and operating conditions such as flow rate. Using temperature measurements collected during the experiment, I applied mass and energy balance relationships to evaluate heat transfer performance and connect experimental results to thermodynamic theory.

---

## Device Description and Real-World Context

Heat exchangers are widely used in engineering applications such as automotive radiators, HVAC systems, power plants, and electronics cooling systems. Their purpose is to transfer thermal energy between two fluid streams without allowing the fluids to mix. While the heat exchanger used in this experiment is lab-scale, it operates based on the same physical principles as industrial heat exchangers.

---

## Qualitative Description of the System

The experimental setup consisted of a heat exchanger connected to two closed water loops: a hot loop and a cold loop. The hot loop circulated water from a reservoir heated using an immersion heater, while the cold loop circulated water from an insulated reservoir containing cold water and ice. Each loop was driven by a pump, allowing the flow rates to be adjusted between fast and slow conditions.

As the fluids flowed through the heat exchanger, heat was transferred from the hot stream to the cold stream through the exchanger walls. No mass transfer occurred between the streams.

---

## System Modeling and Assumptions

The heat exchanger was modeled as a steady-state control volume. Mass flow rates were assumed constant for each trial, and changes in kinetic and potential energy were neglected. No shaft work was performed. Heat loss to the surroundings was assumed to be small relative to the heat exchanged between the two fluid streams.

---

## Governing Relationships

**Mass balance (steady state):**  
Mass flow in = mass flow out

**Energy balance:**  
Heat lost by hot fluid = heat gained by cold fluid

**Effectiveness:**  
Effectiveness = (actual heat transfer) / (maximum possible heat transfer)

---

## Experimental Data

### Parallel Flow — Fast
- Hot inlet: 43.0 °C  
- Hot outlet: 31.8 °C  
- Cold inlet: 17.5 °C  
- Cold outlet: 29.3 °C  

### Parallel Flow — Slow
- Hot inlet: 42.8 °C  
- Hot outlet: 30.5 °C  
- Cold inlet: 21.6 °C  
- Cold outlet: 28.9 °C  

### Counterflow — Fast
- Hot inlet: 44.8 °C  
- Hot outlet: 28.2 °C  
- Cold inlet: 18.0 °C  
- Cold outlet: 31.8 °C  

### Counterflow — Slow
- Hot inlet: 45.6 °C  
- Hot outlet: 25.3 °C  
- Cold inlet: 13.8 °C  
- Cold outlet: 33.4 °C  

---

## Temperature Change Calculations

### Parallel Flow — Fast
ΔTₕ = 43.0 − 31.8 = **11.2 °C**  
ΔT𝚌 = 29.3 − 17.5 = **11.8 °C**

### Parallel Flow — Slow
ΔTₕ = 42.8 − 30.5 = **12.3 °C**  
ΔT𝚌 = 28.9 − 21.6 = **7.3 °C**

### Counterflow — Fast
ΔTₕ = 44.8 − 28.2 = **16.6 °C**  
ΔT𝚌 = 31.8 − 18.0 = **13.8 °C**

### Counterflow — Slow
ΔTₕ = 45.6 − 25.3 = **20.3 °C**  
ΔT𝚌 = 33.4 − 13.8 = **19.6 °C**

---

## Heat Exchanger Effectiveness

Parallel flow (fast):  
Effectiveness = 11.2 / (43.0 − 17.5) = **0.44**

Parallel flow (slow):  
Effectiveness = **0.58**

Counterflow (fast):  
Effectiveness = **0.62**

Counterflow (slow):  
Effectiveness = **0.64**

---

## Discussion

Counterflow operation consistently produced larger temperature changes and higher effectiveness than parallel flow. Slower flow rates also increased heat transfer by increasing the residence time of the fluids inside the exchanger. These trends align well with heat exchanger theory and explain why counterflow designs are commonly used in engineering applications.

---

## Reflection

This project demonstrated how thermodynamic principles such as energy balances and effectiveness can be applied to real systems. Working with experimental data highlighted the importance of assumptions and steady-state operation when analyzing physical devices.
