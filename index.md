---
layout: default
title: Zachary Salloum — Portfolio
name: Zachary Salloum
role_line: "Mechanical Engineering · University of Michigan · <span>open to opportunities</span>"
lede: "I design and build electromechanical systems end to end — from spec and CAD through machining, assembly, and testing. Below are two projects that show that process: a 40 hp electric outboard motor built for competition, and a custom 3D printer designed from scratch around a $1,000 budget."
headshot: /assets/images/ZachHeadshot.jpg
spec_strip:
  - key: Focus
    value: Powertrain & drivetrain design
  - key: Tools
    value: SolidWorks, FEA, 5-axis mill
  - key: Team
    value: UM Electric Boat Team
  - key: Based in
    value: Ann Arbor, MI
---

<div class="dim-divider">Project 01</div>

<section class="project" id="prj-01" markdown="1">

<div class="project-head">
  <div>
    <p class="project-id">PRJ-01 / POWERTRAIN</p>
    <h1 class="project-title">Electric Outboard Motor</h1>
  </div>
  <div class="project-org">University of Michigan Electric Boat Team · 2025–26</div>
</div>

<p class="tldr">Built a fully electric outboard motor for a competition boat entering the ASNE PEP Workforce Development race — 40+ hp continuous, under 55V, powered by three motors linked through a custom-machined gearbox designed from scratch.</p>

<div class="stat-row">
  <div class="stat"><div class="num">40+ hp</div><div class="label">continuous output</div></div>
  <div class="stat"><div class="num">&lt;55V</div><div class="label">operating voltage</div></div>
  <div class="stat"><div class="num">3×</div><div class="label">LMT 7065 motors</div></div>
  <div class="stat"><div class="num">5-mile</div><div class="label">planing hull race</div></div>
</div>

<div class="body-grid" markdown="1">

<div class="constraints-col" markdown="1">
### Constraints

- Battery capped at 55.5V / 500Ah per competition rules
- Team goal of 40 hp+ continuous — hard to hit at such low voltage
- No single motor could deliver enough power, so three had to be linked
- Custom gearbox needed to be light, reliable, and built from scratch

</div>

<div class="build-col" markdown="1">
### The build

Selected three LMT 7065 motors (30kW peak each) paired with a 48V battery to clear the 55.5V limit while hitting the horsepower target — output ultimately bounded by cooling, battery capacity, and inverter choice rather than the motors themselves.

Designed a custom gearbox to combine all three motors onto one output shaft: set target shaft RPM from comparable-class propellers, calculated minimum gear face width for the output power, and reviewed tolerances and shaft seals with industry partner Weismann Transmissions before machining on a 5-axis mill.

Validated the finished powertrain with the High Voltage sub-team using a load disk, after mounting the gearbox, motors, and inverters to a purchased midsection and lower unit bolted to the team's D-Stock hull.

</div>

</div>

<figure>
  <div class="fig-pair">
    <img src="/assets/images/gearbox assembled.jpeg" alt="Assembled gearbox">
    <img src="/assets/images/outboard1.jpeg" alt="Outboard assembly mounted to lower unit">
  </div>
  <figcaption><span class="fig-num">FIG. 1–2</span>Machined gearbox housing, and the full outboard assembly mounted to the lower unit.</figcaption>
</figure>

</section>

<div class="dim-divider">Project 02</div>

<section class="project" id="prj-02" markdown="1">

<div class="project-head">
  <div>
    <p class="project-id">PRJ-02 / ADDITIVE MFG</p>
    <h1 class="project-title">Custom 3D Printer Build</h1>
  </div>
  <div class="project-org">Personal project</div>
</div>

<p class="tldr">Designed and built a custom FDM printer from the ground up to fix everything my $150 Ender 3 got wrong — inconsistent prints, low speed, small volume — while staying under a $1,000 budget and needing zero machine-shop access.</p>

<div class="stat-row">
  <div class="stat"><div class="num">±0.05mm</div><div class="label">dimensional accuracy</div></div>
  <div class="stat"><div class="num">300°C</div><div class="label">max hot-end temp</div></div>
  <div class="stat"><div class="num">280³mm</div><div class="label">build volume</div></div>
  <div class="stat"><div class="num">$600</div><div class="label">total build cost</div></div>
</div>

<div class="body-grid" markdown="1">

<div class="constraints-col" markdown="1">
### Constraints

- $1,000 total budget for all parts and materials
- No mill, lathe, or CNC access — every custom part had to be 3D printed
- Target: 100mm/s at ±0.5mm, or ±0.2mm at 50mm/s
- Had to stay easy to operate, with live print/temp readout

</div>

<div class="build-col" markdown="1">
### The build

Framed the machine in 2020/2040 aluminum extrusion for a stiff, lightweight structure that bolts together with t-nuts — no tapping required — then mounted Y/Z linear rods and stepper motors using custom 3D-printed brackets.

Built the X-axis gantry on linear rod bearings rather than v-slot wheels for lower rolling resistance and tighter tolerances, and chose a Bowden-style extruder to keep weight off the hot-end and avoid the "ringing" that direct-drive setups get at speed.

Wired it up with a BigTreeTech SKR Mini E3 mainboard, silent TMC2209 drivers, a BTT TFT35 touchscreen, and an E3D all-metal hot-end rated to 300°C — enclosures for all of it were custom-designed and printed.

</div>

</div>

<figure>
  <div class="fig-pair">
    <img src="/assets/images/printerComplete2.png" alt="Completed 3D printer, front angle">
    <img src="/assets/images/printerElectronics.png" alt="Printer electronics enclosure">
  </div>
  <figcaption><span class="fig-num">FIG. 1–2</span>Finished printer, and the custom-enclosed mainboard/electronics bay.</figcaption>
</figure>

Biggest trade-off: the moving bed's mass limited top speed before the steppers overheated — a reminder that build volume and print speed pull against each other on any moving-bed printer. Biggest win: the linear-rod bearing system held ±0.05mm accuracy, well inside spec.

</section>
