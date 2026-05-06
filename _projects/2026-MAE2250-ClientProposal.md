---
layout: project
title: Mitigating Spotted Lanternfly Contamination During Mechanical Grape Harvest
description: Integrated mechanical systems for removing SLFs during harvest
technologies: [Mechanical Design, Prototyping, Testing, MATLAB]
image: /assets/images/slf_project.png
---

## Table of Contents

- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Final Prototype](#final-prototype)

---

# Client Pitch

**Team:** ZAM  
**Clients:** Cornell CALS Extension / E&J Gallo Winery / National Grape  

### Problem Statement

From August to November, spotted lanternflies (SLFs) migrate onto grape crops, reaching densities of up to 400 insects per vine. During mechanical harvesting, SLFs cling to grape clusters and enter the harvester along with the grapes.  

Even one or two SLFs can contaminate an entire batch, making it unsellable. There is currently no reliable method to prevent this.

---

### Impact

Targeting SLFs during harvest provides maximum impact with minimal disruption:

- No added labor  
- No workflow interruption  
- Maintains harvest efficiency  
- Reduces economic losses  

---

### Proposed Direction

We explored integrated mechanical solutions that remove SLFs during harvesting:

- Vacuum-based separation  
- Compressed air dislodging system  

---

# Functional Prototype

**Open Design Project 5 — Team ZAM (F6)**

---

## Purpose

Develop and validate a **mechanism capable of actuating a compressed air canister** to remove SLFs from grape clusters.

---

## Key Components

- Compressed Air Can (McMaster 7437K35)  
- Crank Handle (McMaster 6547N15)  
- 8mm Ball Bearings (2x)  
- 3D Printed Shaft (trigger compressor)  
- 3D Printed Housing + Bracket *(substituted with wood prototype)* 

<img src="assets/images/ODP_DRAWING.png">

---

## Assembly Overview

1. Insert bearings into housing and secure  
2. Assemble housing (leave one side open)  
3. Mount compressed air can (CAC) into bracket  
4. Insert shaft through bearings  
5. Attach sideplate and secure housing  
6. Attach crank handle  

**Note:** Adhesives were used for flexibility in early prototyping.

<img src="assets/images/ODP_CAD1.png">
<img src="assets/images/ODP_CAD2.png">
<img src="assets/images/ODP_CAD3.png">

---

## Design Tests

### Test 1 — Trigger Actuation Mechanism

**Goal:** Ensure shaft can properly engage and actuate trigger  

- Required force: **25–45 N**  
- Measured fit: ~1 mm tolerance  
- Rotation required: ~15–25°  

**Result:**  
- Successfully actuates trigger  
- Shaft deflection observed (2–3 mm)

**Conclusion:**  
- Mechanism works  
- Shaft needs reinforcement  

---

### Test 2 — Structural Stability

**Goal:** Ensure housing supports system and maintains alignment  

**Result:**  
- ~0.5 mm lateral movement observed  

**Conclusion:**  
- Acceptable tolerance  
- Transition to **laser-cut acrylic housing** planned  

---

### Test 3 — SLF Removal Distance

**Goal:** Blow off 1 g SLF models at **0.5 m distance**

**Result:**  
- Effective up to **0.3 m (1 ft)**  

**Conclusion:**  
- Below target distance  
- Improvements needed:
  - Stronger shaft (full trigger force)
  - Better nozzle orientation  

---

## Success Criteria

| Criterion | Target | Result |
|----------|--------|--------|
| Trigger force | 25–45 N | Achieved |
| Removal distance | 0.5 m | 0.3 m |
| Actuation time | < 10 s | Achieved |

---

## Key Takeaways

- Mechanism successfully actuates compressed air  
- Structural design is viable  
- Performance limited by shaft strength and airflow direction  

---

# Final Prototype

### Concept: Compressed Air SLF Removal System

<img src="{{ "/assets/images/air_canister_prototype.png" | relative_url }}" width="70%" alt="Compressed Air Prototype">

---

## What it is

A **mounted compressed air system with directional control** that removes SLFs before they enter the harvester.

---

## Key Features

- Concentrated air stream  
- Two-axis gimbal for aiming  
- Mounted integration with harvester  
- Manual crank actuation  

---

## Performance Highlights

- Removes SLFs at distances up to **2.5 ft (~0.76 m)**  
- Achieves required **45 N trigger force**  
- Average response time: **~5.5 seconds**  

---

## Improvements from Functional Prototype

- Increased removal distance  
- Stronger actuation mechanism  
- Improved targeting via gimbal  
- More stable mounting system  

---

## Remaining Challenges

- Risk of dislodging grapes  
- Disposable air supply  
- Manual operation limits scalability  
- Separate aiming + actuation systems  

---

## Future Work

- Refillable compressed air system  
- Automated actuation (motors)  
- SLF detection (vision/sensors)  
- Integrated control system  

---

## Conclusion

This project demonstrates a **feasible and scalable mechanical approach** to reducing SLF contamination during harvest. The system shows strong performance improvements from early prototypes and provides a clear path toward automation and real-world deployment.