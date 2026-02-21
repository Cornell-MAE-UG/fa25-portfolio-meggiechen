---
layout: project
title: Mitigating Spotted Lanternfly Contamination During Mechanical Grape Harvest
description: Client Proposal for removal of SLFs from grapevines
technologies: [Matlab]
---

**Team:** ZAM 
**Client(s):** Cornell CALS Extension / E&J Gallo Winery / National Grape  

---

## Problem Statement

From August to November, spotted lanternflies (SLFs) mature into their adult form and migrate onto grape crops, with up to 400 insects per vine. During mechanical harvesting, SLFs that cling to grape clusters enter the harvesting machinery along with the grapes.  

There is currently no mechanism in place to prevent SLFs from entering the harvester. Even one or two SLFs can contaminate an entire batch of grapes, making the product unsellable. This leads to wasted resources and increased production costs.  

The core challenge is removing SLFs during harvest without disrupting the mechanical harvesting process or damaging grapes.

---

## Impact

Targeting SLFs during mechanical harvest provides the greatest level of control while minimizing interference with existing vineyard operations. By integrating directly with the harvester, the solution:

- Adds minimal additional labor
- Avoids introducing separate removal steps
- Preserves harvest efficiency
- Reduces contamination-related product loss

Solving this problem directly addresses client needs by improving yield viability and reducing economic losses.

---

## Proposed Direction(s)

### Concept A (Primary): SLF Vacuum System

**What it is:**  
A vacuum attachment integrated into the harvester that removes SLFs from harvested grapes before they enter the main collection reservoir.

**How it would be used:**

- Attach vacuum system to the collector system before the reservoir  
- As grapes enter, SLFs are suctioned away  
- Juice and grapes pass through filtration and remain in the system  
- SLFs are deposited into a separate bin or expelled from the harvester  

**Why it’s better than the status quo:**

- Prevents SLFs from entering the final grape collection  
- Provides automatic sorting without manual labor  
- Fully integrated into existing harvesting workflow  

**End-of-semester proof-of-concept:**  
A tested vacuum prototype that successfully removes SLF models while avoiding grape removal.

---

### Concept B: SLF Removal via Compressed Air System

**What it is:**  
A front-mounted attachment that detects SLF concentration and deploys compressed air to dislodge them before the grape vines are shaken.

**How it would be used:**

- Mount mechanism to the front of the harvester  
- Detect high SLF concentration  
- Pause harvesting  
- Deploy compressed air to dislodge SLFs  
- Resume harvesting once SLF concentration decreases  

**Why it’s better than the status quo:**

- Removes SLFs before they enter the harvester  
- Integrated into the harvesting process  
- Uses relatively inexpensive and reusable compressed air  

**End-of-semester proof-of-concept:**  

- Functional compressed air deployment mechanism  
- Reliable on-demand activation system  
- Demonstrated mounting solution for common harvester models  

---

## Key Risks / Unknowns

- **Vacuum pressure precision** — Too strong may remove grapes or juice; too weak may fail to remove SLFs.  
  *Test:* Develop weight-accurate SLF and grape models to determine optimal suction range.

- **Grape displacement from compressed air** — Air blasts may dislodge grapes along with SLFs.  
  *Test:* Controlled trials measuring grape loss during air deployment.

- **Harvest speed reduction** — Detection and air deployment may slow overall harvesting time.  
  *Test:* Measure response time and reliability over 30 repeated deployments.

---

## Questions for the Client

1. Is there quantitative data on how strongly SLFs grip grape crops?  
   *Decision affected:* Required vacuum strength and compressed air pressure.

2. Can we obtain specifications for the most commonly used harvester models?  
   *Decision affected:* Mounting design and integration constraints.

3. Can SLFs continue gripping crops after death, and for how long?  
   *Decision affected:* Feasibility of chemical or pre-harvest mitigation strategies.



<embed src="{{ '/assets/pdfs/ODP 3_ Client Outline.pdf' | relative_url }}" 
       type="application/pdf" 
       width="100%" 
       height="800px" />