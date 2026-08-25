---
layout: default
title: Zachary Salloum
role_line: "Mechanical Engineering Portfolio"
lede: "I am a sophomore MechE at the University of Michigan and I love to build. Feel free to get in touch!"
headshot: /assets/images/ZachHeadshot.jpg
spec_strip:
  - key: Focus
    value: Powertrain & drivetrain design
  - key: Tools
    value: Siemens NX, Mill, Lathe, MIG/TIG
  - key: Based in
    value: Birmingham, MI
---

<div class="dim-divider">About</div>

<section class="project" id="about-more" markdown="1">

<p class="tldr">Since I was a kid, I've always enjoyed learning by doing. In engineering, this has meant getting involved in project teams, internships, and personal projects where I've been able to take my ideas from design to prototype. Outside of engineering, it has meant engaging in several different enriching hobbies</p>

<div class="body-grid" markdown="1">

<div class="constraints-col" markdown="1">
### In my free time I love:

- Mountain Biking and Skiing
- Restoring my '88 Ford Bronco
- Finding new fishing spots
- Playing golf and tennis

</div>

<div class="about-photos" markdown="1">

<figure class="log-photo">
  <img src="/assets/images/river.jpg" alt="au sable river">
  <figcaption>The Au Sable River in Grayling, MI</figcaption>
</figure>

<figure class="log-photo">
  <img src="/assets/images/bronco.JPG" alt="1988 Bronco ii">
  <figcaption>My 1988 Ford Bronco ii</figcaption>
</figure>

</div>
</div>
</section>


<div class="dim-divider">Project 01</div>

<section class="project" id="prj-01" markdown="1">

<div class="project-head">
  <div>
    <h1 class="project-title">Electric Outboard Motor <span class="status-badge">In progress</span></h1>
  </div>
  <div class="project-org">University of Michigan Electric Boat Team</div>
</div>

<p class="tldr">This year, my project team is racing a fully electric outboard motor that I helped design — 40+ hp continuous, under 55V, and powered by three motors linked through a gearbox that we machined from scratch.</p>

<div class="hero-shot">
  <img src="/assets/images/hull.jpeg" alt="Team boat hull">
</div>

<div class="stat-row">
  <div class="stat"><div class="num">40+ hp</div><div class="label">continuous output</div></div>
  <div class="stat"><div class="num">&lt;55V</div><div class="label">operating voltage</div></div>
  <div class="stat"><div class="num">3×</div><div class="label">LMT 7065 motors</div></div>
  <div class="stat"><div class="num">D-Stock</div><div class="label">Planing Hull</div></div>
</div>

This ongoing project is a part of the University of Michigan Electric Boat Team's current competition boat. Our team entered the 2026 PEP Workforce Development Competition - an electric boat race hosted by the American Society of Naval Engineers in Pourtsmouth, VA - in the crewed, planing hull division, which is a 5 mile circle-track race geared towards top-end speed. We are utilizing a light-weight D-Stock hull, which is optimized for such events. I worked on the outboard motor sub-team, where we are creating a light-weight electric outboard motor with at least 40 continuous horsepower at an operating voltage under 55V per the competition rules.

<div class="body-grid" markdown="1">

<div class="constraints-col" markdown="1">
### Constraints

- Battery limit 55.5V / 500Ah
- 40+ hp continuous (Team goal)
- 50lbs max weight (Team goal)
- Available motor + inverter
- IP66 water resistance

</div>

<div class="build-col" markdown="1">
### Tri-Motor Powertrain

Given the limit of 55.5V, we decided to build a 48V battery. At this voltage, we couldn't find any real options capable of delivering the necessary 30kW continuous. So, we decided on 3 LMT 7065 motors, each rated at 11.2kW continuous. Running them in tandem pushed us well over the our target output, with the real ceiling ultimately set by cooling, battery capacity, and inverter selection rather than the motors themselves.

</div>

</div>

<div class="build-log">

<div class="log-step">
  <figure class="log-photo">
    <img src="/assets/images/motor.png" alt="LMT 7065 electric motor">
    <figcaption>One of the three LMT 7065 motors we selected</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 01 — Motor selection</h4>
    <p>Once it was clear three motors were needed, we started thinking about how to use a gearbox to link the motors together to one output shaft. The biggest issue initially was trying to come up with a compact motor-gearbox assembly that fits in the powerhead with space remaining for the inverters.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/outboardExploded.png" alt="Outboard exploded view">
    <figcaption>Early outboard CAD assembly</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 02 — Designing the Gearbox</h4>
    <p>We picked our target shaft RPM by looking at propellers on similar-output D-Stock boats. Then, we calculated the minimum gear face width our output power would need. From there we determined the optimal gear pitch while also accounting for the positioning of the motors in the limited space of the powerhead. We held a design review with our industry partner Weismann Transmissions to get feedback and answer specific questions on tolerances and shaft seals.</p>
  </div>
</div>

<div class="log-step">
  <figure class="log-photo">
    <img src="/assets/images/gearbox bottom.jpeg" alt="Gearbox housing, bottom view">
    <figcaption>The machined gearbox housing, with bearings</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 03 — Machining and assembly</h4>
    <p>Once we finalized our gearbox design and ran FEA simulations on the predicted load, we entered the assembly phase. The gearbox housing was machined on a 5-axis mill. While that was machined, we created the shafts by cutting round stock to length and milling key slots into it. We also broached the purchased gears and press-fit the bearings into the housing. The motor and encoder plates were fabricated on a water jet, and a mount for the 3 motor inverters was designed and 3D printed.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/outboard1.jpeg" alt="Full outboard assembly on lower unit">
    <figcaption>The early-stage outboard bolted to the hull.</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 04 — Outboard assembly</h4>
    <p>After final assembly of the gearbox, we then mounted the gearbox, motors, and inverters to a midsection and lower unit that we purchased. This comprised the entire outboard assembly, less the cowl, which will be made out of carbon fiber. We bolted the assembly to the D-Stock hull, and worked with the High Voltage sub-team to test the powertrain, validating the total output using a load disk. </p>
  </div>
</div>

</div>

<div class="gallery-strip">
  <img src="/assets/images/outboard2.jpeg" alt="Outboard side detail">
  <img src="/assets/images/outboardCad.png" alt="Outboard CAD model">
  <img src="/assets/images/gearbox assembled.jpeg" alt="Fully assembled gearbox">
</div>

<p>Now, our team is moving forward with more system integration, dry tests, and troubleshooting as we prepare to start our 2026-27 season with a float test.</p>
</section>






<div class="dim-divider">Project 02</div>

<section class="project" id="prj-02" markdown="1">

<div class="project-head">
  <div>
    <h1 class="project-title">Custom 3D Printer Build</h1>
  </div>
  <div class="project-org">Personal project</div>
</div>

<p class="tldr">The inspiration for this project came from the first 3D printer I owned: a Creality Ender 3. I bought that machine for $150, and it taught me much about 3D printing and additive manufacturing. However, it left a ton on the table in terms of performance. </p>

<div class="hero-shot">
  <img src="/assets/images/frontView2.jpeg" alt="Completed custom 3D printer, front view">
</div>

<div class="stat-row">
  <div class="stat"><div class="num">±0.05mm</div><div class="label">dimensional accuracy</div></div>
  <div class="stat"><div class="num">300°C</div><div class="label">max hot-end temp</div></div>
  <div class="stat"><div class="num">280³mm</div><div class="label">build volume</div></div>
  <div class="stat"><div class="num">$600</div><div class="label">total build cost</div></div>
</div>

My Ender 3 printer was often inconsistent. The finished prints were not always dimensionally accurate, and the printer could not reliably operate at speeds above 60mm/s. I worked to create a custom 3D printer that addresses all these issues, while having a larger build volume. My initial design took inspiration from several popular models of 3D printers, including the Creality CR-10 and Prusa i3 MK3s. I looked to replicate the CR-10's massive build volume and capture the excellent print quality of the Prusa i3. To do this, I borrowed strengths from each machine's design, while engineering new solutions to their weaknesses.

<div class="body-grid" markdown="1">

<div class="constraints-col" markdown="1">
### Constraints

- $1,000 total budget
- No mill, lathe, or CNC access
- 100mm/s at ±0.1mm, ±0.05mm at 50mm/s
- As easy to use as off-the-shelf printers

</div>

<div class="build-col" markdown="1">
### Starting off

Before any design could begin, I researched existing 3D printers to determine certain characteristics and features mine should have. For example, I determined a cartesian-style movement system with a fixed-Z-axis bed would be a good platform for the goals I had in mind. Additionally, running a 24V system would be optimal as it would let the system get up to temperature quickly. Lastly, I wanted my printer to feature linear rods for precise movement.
</div>

</div>

<div class="build-log">

<div class="log-step">
  <figure class="log-photo">
    <img src="/assets/images/printerFrame.png" alt="Printer frame assembly">
    <figcaption>The complete 2020/2040 extrusion frame</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 01 — Building the Frame</h4>
    <p>The first step in the build was assembling the frame. Aluminum extrusions stood out as the most effective material for their affordability, availability, and stiffness. Additionally, they are lightweight and can be quickly fixed together with brackets, screws, and t-nuts. This allows for quick assembly and prototyping, as using t-nuts eliminates the need to drill holes and tap threads.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/printerFrame2.png" alt="Y and Z axis rods mounted">
    <figcaption>Y and Z axis linear rods and motors</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 02 — Y and Z motion system installation</h4>
    <p>The next step was mounting the Y and Z axis linear rods and stepper motors. This was accomplished by designing and 3D printing custom mounts to secure the rods and motors to the frame. The mount designs went through several iterations to ensure optimal rod rigidity and spacing. Various other parts were also integrated during this step, including endstop mounts, Z-axis leadscrews, and the Y-axis belt pulleys.</p>
  </div>
</div>

<div class="log-step">
  <figure class="log-photo">
    <img src="/assets/images/frameComplete.png" alt="X-axis gantry assembled">
    <figcaption>The X-axis gantry, without the toolhead </figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 03 — Building the X-axis gantry</h4>
    <p>Next, the X-axis gantry was assembled. It consists of 2 linear rods joined by a custom 3D printed piece on each end. Those end pieces also contain bearings and leadscrew nuts, allowing the gantry to move vertically. The X-stepper motor is mounted to the left bracket, and the belt pulley is fixed to the bracket on the right. Another 3D printed piece rides on the X-axis bearings; it will serve as the mount for the hot-end and part cooling fan. Designing this assembly was extremely difficult, as everything had to fit together with virtually zero slop.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/printerHotend.png" alt="Hot-end and heated bed assembly">
    <figcaption>Heated bed and hot-end integration</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 04 — Heated bed and hot-end installation</h4>
    <p>Next, the heated bed and hot-end assemblies were built and installed. The heated bed sits above an aluminum carriage plate that clamps onto the linear rod bearings. The two plates are separated by 4 springs and screws to allow for height adjustment of the heated bed. The hot-end assembly consists of a 3D printed mounting plate that clamps onto the X-axis bearings, the hot-end itself, as well as a cooling fan and duct. At this point, the X and Y drive belts were installed and tensioned.</p>
  </div>
</div>

<div class="log-step">
  <figure class="log-photo">
    <img src="/assets/images/printerExtruder.png" alt="Bowden extruder assembly">
    <figcaption>The Bowden extruder, mounted to the frame</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 05 — Extrusion system installation</h4>
    <p>This printer's extrusion system consists of a stepper motor, custom mounting bracket, extruder, and bowden tube. I used an off-the-shelf extruder due to its affordability and effectiveness. A Bowden style extruder was chosen for this build, due to this printer's emphasis on printing speed. Bowden extruders push filament through a tube, into the hot-end. This allows the stepper motor and extruder to be mounted to the frame of the printer, rather than directly to the hot-end. This prevents the "ringing" effect seen at higher print speeds when too much weight is placed on the hot-end. Additionally, a larger, cooler-running motor can be used.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/printerElectronics.png" alt="Printer electronics enclosure">
    <figcaption>Custom-enclosed electronics bay: mainboard, drivers, and the touchscreen controller.</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 06 — Electronics installation</h4>
    <p>Finally, 4 key electronics were installed. First, a 24V 350W power supply was chosen to power the printer. Then, a BigTreeTech SKR Mini E3 mainboard was chosen due to its affordability and robustness, as it has a 32-bit processor, silent TMC2209 motor drivers, and a multitude of fan ports. It also meshes well with the BTT TFT35 LCD screen, which I chose to be the screen for this printer due to its clean UI, and touchscreen function. Finally, I installed a 25A mosfet to control the heated bed, as the main-board's built-in mosfet was not adequate. Custom enclosures were designed and 3D printed to house these parts, with cooling fans used where necessary.</p>
  </div>
</div>

</div>


<div class="gallery-strip">
  <img src="/assets/images/printerComplete2.png" alt="Completed printer, angled view">
  <img src="/assets/images/sideView.jpeg" alt="Completed printer, side view">
  <img src="/assets/images/rearView.jpeg" alt="Completed printer, rear view">
</div>
<div class="gallery-strip">
  <img src="/assets/images/extruder.jpeg" alt="Extruder close-up">
  <img src="/assets/images/xCarriageSide.jpeg" alt="X-carriage close-up">
  <img src="/assets/images/mainboard.jpeg" alt="Mainboard close-up">
</div>

<div class="conclusion" markdown="1">
### What I learned

Overall, this project was very successful. I learned much about how FDM 3D printers work, and made real improvements in my design. The finished printer, while not perfect, achieved many of the goals I had in mind, and performed significantly better than my Creality Ender 3. And, at around $650, I spent less on this project than I had budgeted. Ultimately, the machine I built was able to print roughly 40mm/s faster than my Creality Ender-3 while retaining the same print quality. However, speed was not ultimately this printer's greatest strength, due to the large print surface. While the X-axis was set up to be light weight, the sliding bed assembly was relatively heavy. Moving it at overly high speeds resulted in the stepper motors overheating, which produces worsened print quality. This demonstrates the fundamental trade-off between speed and build capacity on printers with moving beds: as the size of the build surface increases, the harder it is to move quickly and accurately. That said, this machine's build volume was very satisfactory: 280mm x 280mm x 300mm, compared to the Ender 3's build volume of 220mm x 220mm x 250mm.

Additionally, the machine offers excellent dimensional accuracy due to the linear rod bearing system. While many cheaper 3D printers use v-slot wheels that slide along the aluminum extrusions, my machine utilized linear rods and bearings. This system is superior as it offers less rolling resistance and more precise movement. This style of bearing also wears out less over time. The result was dimensional accuracy of around +/- 0.05mm in all of my tests, which was the greatest success of this project. Another strength of this 3D printer is its capacity for high temperature printing. While many 3D printers are typically rated up to 240 degree Celcius, this one has an all-metal hot-end from E3D, and can achieve temperatures up to 300 Celcius. This enables it to print a multitude of different filaments. Finally, I am proud of the machine's form factor and usability. The frame of the machine was extremely stiff and lightweight, and it is very easy to build onto to it in the future. The heated bed is magnetic, allowing build surfaces to be quickly swapped, and the LCD touchscreen I installed makes using the machine very straightforward and easy. 

The final result was a versatile printer that produces quality results and is as easy to use as most other 3D printers on the market.
</div>

</section>
