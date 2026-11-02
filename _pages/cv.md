---
layout: default
title: Curriculum Vitae
permalink: /cv/
---

<style>
  /* Force CV container to take up 80% of laptop screen width */
  .cv-page-container {
    width: 80vw;
    max-width: 1400px;
    margin-left: calc(-40vw + 50%);
    margin-right: calc(-40vw + 50%);
    padding: 0 10px;
    box-sizing: border-box;
  }

  /* On mobile phones, adapt cleanly to screen edges */
  @media screen and (max-width: 768px) {
    .cv-page-container {
      width: 100%;
      margin-left: 0;
      margin-right: 0;
      padding: 0 15px;
    }
  }

  /* Professional Download Button Styling */
  .cv-download-container {
    margin: 20px 0 35px 0;
  }

  .btn-download-cv {
    display: inline-flex;
    align-items: center;
    gap: 10px;
    background-color: #0f172a;
    color: #ffffff !important;
    padding: 12px 24px;
    border-radius: 6px;
    font-size: 14px;
    font-weight: 600;
    letter-spacing: 0.02em;
    text-decoration: none !important;
    border: 1px solid #1e293b;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.08);
    transition: all 0.2s ease-in-out;
  }

  .btn-download-cv:hover {
    background-color: #1e293b;
    border-color: #334155;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    transform: translateY(-1px);
  }

  .btn-download-cv svg {
    width: 18px;
    height: 18px;
    stroke-width: 2.2;
  }

  /* Resume Row Layout for Right-Aligned Dates */
  .resume-row {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    gap: 1rem;
    width: 100%;
  }

  .resume-title {
    font-weight: 700;
    color: #0f172a;
  }

  .resume-date {
    font-family: monospace;
    font-size: 0.85rem;
    color: #475569;
    white-space: nowrap;
  }
</style>

<div class="cv-page-container">

## Curriculum Vitae

<div class="cv-download-container">
  <a href="{{ '/assets/Resume_FA26.pdf' | relative_url }}" download="Resume_FA26.pdf" class="btn-download-cv">
    <svg fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path stroke-linecap="round" stroke-linejoin="round" d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
    </svg>
    <span>Download Resume (PDF)</span>
  </a>
</div>

---

### Education
<div class="resume-row">
  <div><strong>Cornell University</strong>, Ithaca NY &mdash; <em>B.S. in Mechanical Engineering</em>, GPA: 3.98</div>
  <div class="resume-date">Expected Dec 2027</div>
</div>
<p style="margin-top: 6px; font-size: 0.9em; color: #475569;">
  <strong>Relevant Coursework:</strong> Statics & Mechanics of Solids, Mechanics of Engineering Materials, Dynamics, Flight Dynamics, System Dynamics, Mechatronics, Thermodynamics, Heat Transfer, Fluid Mechanics, Spacecraft Dynamics
</p>

---

### Technical & Leadership Experience

<div class="resume-row">
  <div class="resume-title">SPACEX &mdash; Incoming Engineering Intern (Launch Mechanisms and Structures)</div>
  <div class="resume-date">Spring 2027</div>
</div>
<ul style="margin-top: 4px;">
  <li>Supporting the development of ground support and pad infrastructure for Starship on the Launch Mechanisms and Structures team.</li>
</ul>

<div class="resume-row" style="margin-top: 16px;">
  <div class="resume-title">CORNELL UNIVERSITY UNMANNED AIR SYSTEMS &mdash; Structures and Payloads Lead</div>
  <div class="resume-date">Nov 2024 – Present</div>
</div>
<ul style="margin-top: 4px;">
  <li>Lead a 10-engineer structures and payloads subgroup on a 35 lb autonomous search-and-rescue VTOL aircraft (70+ person team, 2nd of 6 at CUASC), directing implementation of the team's first tilt-rotor VTOL system as an alternative to the 4-motor-plus-pusher layout; bench-tested and preparing for flight trials.</li>
  <li>Supervise 6–8 concurrent projects (tilt rotors, airdrop, gimbal, landing gear, bay doors, imaging test platform) through four formal design reviews, coordinating mechanical interfaces with the electrical and software subteams.</li>
</ul>

<div class="resume-row" style="margin-top: 12px;">
  <div class="resume-title">Structures and Payloads Mechanical Member</div>
  <div class="resume-date">Nov 2024 – Present</div>
</div>
<ul style="margin-top: 4px;">
  <li>Evaluated landing gear concepts on weight, compliance, and manufacturability, then designed, fabricated, and validated a carbon-fiber leaf-spring gear using SolidWorks and Ansys FEA; verified a 36% weight reduction across physical drop trials (straight, tilted, sustained load) at 1 m/s landing velocity and 15° roll.</li>
  <li>Characterized off-the-shelf strut suspension mechanics by executing static compression testing across incremental loads to extract effective spring stiffness, applying strain energy conservation models to predict peak dynamic deflection and boundary limits under free-fall conditions, giving a conservative upper limit safety margin.</li>
  <li>Reworked a DJI drone airframe to integrate custom hardware mounts and reinforce structurally unsound elements within constrained central-bay geometry, collaborating with electrical and imaging subteams to resolve interface and wiring constraints.</li>
</ul>

<div class="resume-row" style="margin-top: 16px;">
  <div class="resume-title">INTUITIVE SURGICAL &mdash; Manufacturing Process Engineering Intern</div>
  <div class="resume-date">June 2026 – Aug 2026</div>
</div>
<ul style="margin-top: 4px;">
  <li>Engineered and deployed a custom manufacturing line fixture to resolve an active bottleneck, confirmed to cut per-unit build time by 55% (40 seconds saved per unit) via line time studies.</li>
  <li>Executed a 132-run DoE and capability analysis in Minitab, using Cpk metrics and Pareto charts to isolate primary failure modes and reduce future testing scope by 50%.</li>
  <li>Designed and modeled custom machining fixtures, producing shop-ready technical drawings to support fabrication.</li>
  <li>Managed 5 ECOs and created and managed up to 20 parts and documents across Agile PLM and Windchill, maintaining CAD version control under regulated QMS standards.</li>
</ul>

<div class="resume-row" style="margin-top: 16px;">
  <div class="resume-title">SPACE SYSTEMS DESIGN STUDIO (SSDS) &mdash; ASCENT Mechanical Subteam Member</div>
  <div class="resume-date">Jan 2026 – July 2026</div>
</div>
<ul style="margin-top: 4px;">
  <li>Precision-machined a rocket bulkhead on a manual mill and lathe, holding ±0.005 in tolerances to ensure structural interface alignment, and fabricated custom 3D-printed mounting brackets.</li>
  <li>Designed a compact four-bar linkage in Fusion 360 to synchronize dual valve actuation through a 90° sweep with a single servo for liquid bi-propellant rocket, resolving engine-bay clearance constraints and preventing component interference; the linkage survived 2 hot fires and a live takeoff.</li>
</ul>

<div class="resume-row" style="margin-top: 16px;">
  <div class="resume-title">ASTRA LAB &mdash; Undergraduate Researcher</div>
  <div class="resume-date">June 2025 – Aug 2025</div>
</div>
<ul style="margin-top: 4px;">
  <li>Ran 18 Density Functional Theory simulations in CP2K and 8 molecular dynamics simulations in LAMMPS, compiling binding-energy data for 16 ionic liquids to support a machine-learning model for predicting electric-propulsion fuel properties.</li>
</ul>

---

### Skills
* **Fabrication:** Manual Mill, Manual Lathe, Wet Carbon-Fiber Layups, 3D Printing, Rapid Prototyping
* **Software:** SolidWorks, Fusion 360, Ansys Mechanical, Python, MATLAB, Java, Agile PLM, Windchill, Confluence

</div>