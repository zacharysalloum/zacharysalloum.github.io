---
layout: default
title: Zachary Salloum
role_line: "Mechanical Engineering Portfolio"
lede: "I am a sophomore MechE at the University of Michigan and I love to build. Interested in anything that has wheels, wings, or props. Feel free to get in touch!"
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

<p class="tldr">Since I was a kid, I've always enjoyed doing. In engineering, this has meant getting involved in project teams, internships, and personal projects where I've been able to take my ideas from design to prototype. Outside of engineering, it has meant staying busy with several different hobbies</p>

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

<p class="tldr">This year, my project team is racing a fully electric outboard motor I helped design — 40+ hp continuous, under 55V, and powered by three motors linked through a gearbox that we machined from scratch.</p>

<div class="hero-shot">
  <img src="/assets/images/hull.jpeg" alt="Team boat hull">
</div>

<div class="stat-row">
  <div class="stat"><div class="num">40+ hp</div><div class="label">continuous output</div></div>
  <div class="stat"><div class="num">&lt;55V</div><div class="label">operating voltage</div></div>
  <div class="stat"><div class="num">3×</div><div class="label">LMT 7065 motors</div></div>
  <div class="stat"><div class="num">D-Stock</div><div class="label">Planing Hull</div></div>
</div>

This ongoing project is a part of the University of Michigan Electric Boat Team's current competition boat. Our team entered the 2026 PEP Workforce Development Competition - an electric boat race hosted by the American Society of Naval Engineers in Pourtsmouth, VA - in the crewed, planing hull division, which is a 5 mile circle-track race geared towards top-end speed. We are utilizing a D-Stock hull, which is light-weight and optimized for such events. I worked on the outboard motor sub-team, where we are creating a light-weight electric outboard motor with at least 40 continuous horsepower at an operating voltage under 55V per the competition rules.

<div class="body-grid" markdown="1">

<div class="constraints-col" markdown="1">
### Constraints

- Battery capped at 55.5V / 500Ah
- 40+ hp continuous (Team goal)
- 50lbs max weight (Team goal)
- Comercially available motor + inverter
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
    <figcaption>One of the three LMT 7065 motors we settled</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 01 — Motor selection</h4>
    <p>Once it was clear no single motor could hit 40+ hp under 55V, we pivoted to three in tandem. It meant more complexity downstream — namely, a gearbox that didn't exist yet — but it was the only path to the power we needed.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/outboardExploded.png" alt="Outboard exploded view">
    <figcaption>Early gearbox housing — this is where all three motors had to come together onto one shaft.</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 02 — Designing the Gearbox</h4>
    <p>We picked our target shaft RPM by studying propellers on similar-class boats, then ran the numbers to find the minimum gear face width our output power would need. From there we worked out gear pitch while juggling how tight the powerhead really was for space. We also sat down with our industry partner, Weismann Transmissions, for a design review on tolerances and shaft seals — a genuinely useful reality check before we committed to machining anything.</p>
  </div>
</div>

<div class="log-step">
  <figure class="log-photo">
    <img src="/assets/images/gearbox bottom.jpeg" alt="Gearbox housing, bottom view">
    <figcaption>The finished gearbox, machined on a 5-axis mill and press-fit with bearings.</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 03 — Machining</h4>
    <p>After FEA validated the load case, we moved into assembly: the housing was machined on a 5-axis mill, shafts were cut from round stock and key-slotted, gears were broached, and bearings were press-fit into place. Motor and encoder plates came off the water jet, and the inverter mount was 3D printed to save weight.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/outboard1.jpeg" alt="Full outboard assembly on lower unit">
    <figcaption>The complete outboard — gearbox, motors, and inverters mounted to the lower unit and bolted to the hull.</figcaption>
  </figure>
  <div class="log-text">
    <h4>Step 04 — Putting it all together</h4>
    <p>With the gearbox finished, we mounted it along with the motors and inverters onto a purchased midsection and lower unit, then bolted the whole assembly to our D-Stock hull. From there we worked with the High Voltage sub-team to validate total output using a load disk — the moment all the earlier math either held up or didn't. It held up.</p>
  </div>
</div>

</div>

<h4>Photos</h4>
<div class="gallery-strip">
  <img src="/assets/images/outboard2.jpeg" alt="Outboard side detail">
  <img src="/assets/images/outboardCad.png" alt="Outboard CAD model">
  <img src="/assets/images/gearbox assembled.jpeg" alt="Fully assembled gearbox">
  
</div>
</section>





<div class="dim-divider">Project 02</div>

<section class="project" id="prj-02" markdown="1">

<div class="project-head">
  <div>
    <h1 class="project-title">Custom 3D Printer Build</h1>
  </div>
  <div class="project-org">Personal project</div>
</div>

<p class="tldr">My first 3D printer was a $150 Ender 3 that taught me a ton — and frustrated me just as much. So I designed and built my own from scratch to fix what it got wrong, on a $1,000 budget and with zero machine-shop access.</p>

<div class="hero-shot">
  <img src="/assets/images/frontView2.jpeg" alt="Completed custom 3D printer, front view">
</div>

<div class="stat-row">
  <div class="stat"><div class="num">±0.05mm</div><div class="label">dimensional accuracy</div></div>
  <div class="stat"><div class="num">300°C</div><div class="label">max hot-end temp</div></div>
  <div class="stat"><div class="num">280³mm</div><div class="label">build volume</div></div>
  <div class="stat"><div class="num">$600</div><div class="label">total build cost</div></div>
</div>

The inspiration was that first Ender 3. It taught me a lot about additive manufacturing, but it was inconsistent — prints weren't always dimensionally accurate, and it couldn't reliably run above 60mm/s. I wanted something that fixed that, with a bigger build volume too. I looked at what I liked about the Creality CR-10 (its huge build volume) and the Prusa i3 MK3s (its print quality), borrowed the strengths of each, and engineered around their weaknesses.

<div class="body-grid" markdown="1">

<div class="constraints-col" markdown="1">
### Constraints

- $1,000 total budget for everything
- No mill, lathe, or CNC access — every custom part had to be 3D printed
- Target: 100mm/s at ±0.5mm, or ±0.2mm at 50mm/s
- Needed a screen showing live print time and temperature, so it stayed easy to use

</div>

<div class="build-col" markdown="1">
### Starting with the frame

2020 and 2040 aluminum extrusion won out for the frame — affordable, widely available in different sizes, and light and stiff enough to hold tolerances. T-nuts slide directly into the extrusion, so I never had to tap a single thread, which made fastening everything else to the frame far quicker than I expected.

</div>

</div>

<div class="build-log">

<div class="log-step">
  <figure class="log-photo">
    <img src="/assets/images/printerFrame.png" alt="Printer frame assembly">
    <figcaption>The 2020/2040 extrusion frame, bolted together with t-nuts and brackets.</figcaption>
  </figure>
  <div class="log-text">
    <span class="step-tag">Step 01 — Frame</span>
    <h4>A stiff, lightweight skeleton</h4>
    <p>The frame had to be rigid enough to hold real tolerances but light enough not to fight the moving axes. Aluminum extrusion made both easy — and made the whole build feel more like assembling furniture than machining metal.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/printerFrame2.png" alt="Y and Z axis rods mounted">
    <figcaption>Y and Z linear rods going in, held by custom 3D-printed mounts.</figcaption>
  </figure>
  <div class="log-text">
    <span class="step-tag">Step 02 — Motion mounts</span>
    <h4>Printing the parts I couldn't machine</h4>
    <p>With no mill or lathe on hand, every custom bracket had to come off my own printer first — the Y/Z rod mounts, stepper motor mounts, endstop brackets, and the belt tensioner for the Y axis. It's a strange, recursive feeling: 3D printing the parts for a better 3D printer.</p>
  </div>
</div>

<div class="log-step">
  <figure class="log-photo">
    <img src="/assets/images/frameComplete.png" alt="X-axis gantry assembled">
    <figcaption>The X-axis gantry — linear rods on both ends, riding on printed carriages.</figcaption>
  </figure>
  <div class="log-text">
    <span class="step-tag">Step 03 — X-axis gantry</span>
    <h4>Getting the gantry moving</h4>
    <p>Two linear rods attach to custom printed end pieces, which also house the bearings and leadscrew nuts that let the whole X-axis travel vertically. A stepper motor sits on one bracket, the belt pulley on the other, with a third printed piece riding the bearings to eventually hold the hot-end.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/printerHotend.png" alt="Hot-end and heated bed assembly">
    <figcaption>Heated bed and hot-end going in — the part where the printer starts looking like a printer.</figcaption>
  </figure>
  <div class="log-text">
    <span class="step-tag">Step 04 — Bed &amp; hot-end</span>
    <h4>Heated bed and hot-end</h4>
    <p>The heated bed clamps to an aluminum plate suspended on four springs — standard FDM design, but satisfying to get right, since it's what lets you dial in bed leveling by hand. The hot-end mounting plate clamps onto the X-axis bearings, with the cooling fan, duct, and drive belt all fixed to the same bracket so the whole assembly moves as one unit.</p>
  </div>
</div>

<div class="log-step">
  <figure class="log-photo">
    <img src="/assets/images/printerExtruder.png" alt="Bowden extruder assembly">
    <figcaption>The Bowden extruder — mounted to the frame instead of the hot-end, to keep weight down.</figcaption>
  </figure>
  <div class="log-text">
    <span class="step-tag">Step 05 — Extruder</span>
    <h4>Choosing Bowden over direct-drive</h4>
    <p>Since speed was the whole point of this build, I went with a Bowden-style extruder — it pushes filament through a tube into the hot-end, so the stepper motor mounts to the frame rather than riding on the gantry. Direct-drive setups get "ringing" at high speed because of the added weight; Bowden avoids that, and lets you run a bigger, cooler-running motor.</p>
  </div>
</div>

<div class="log-step reverse">
  <figure class="log-photo">
    <img src="/assets/images/printerElectronics.png" alt="Printer electronics enclosure">
    <figcaption>Custom-enclosed electronics bay: mainboard, drivers, and the touchscreen controller.</figcaption>
  </figure>
  <div class="log-text">
    <span class="step-tag">Step 06 — Electronics</span>
    <h4>Wiring it all together</h4>
    <p>A BigTreeTech SKR Mini E3 runs the show — a $40 mainboard with a 32-bit processor, silent TMC2209 drivers, and plenty of fan ports, paired with a BTT TFT35 touchscreen for a clean, easy-to-read UI. I added a 25A mosfet for the heated bed since the mainboard's built-in one wasn't enough, and 3D printed enclosures for everything, with cooling fans wherever things ran warm.</p>
  </div>
</div>

</div>

<div class="pull-note">The finished printer runs about 40mm/s faster than my old Ender 3 at the same print quality — and came in around $600, under budget.</div>

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

Overall, this project delivered on most of what I set out to do, and taught me a lot about how FDM printers actually work under the hood. At around $600, I came in under budget, and the finished machine prints roughly 40mm/s faster than my old Ender 3 while holding the same quality.

Speed wasn't its biggest strength, though — the moving bed is heavier than I'd like, and pushing it too fast overheats the steppers and hurts print quality. It's a good reminder that build volume and print speed pull against each other on any printer with a moving bed; the bigger the bed, the harder it is to move quickly and accurately.

Where it really shines is accuracy: the linear rod bearing system (versus the v-slot wheels most budget printers use) gave me roughly ±0.05mm dimensional accuracy across my tests — less rolling resistance, more precise movement, and less wear over time. It also runs hot: the E3D all-metal hot-end handles up to 300°C, well past the ~240°C ceiling on most consumer printers, which opens the door to a lot more filament types. And with a magnetic bed and the touchscreen UI, it's genuinely easy to live with day to day — versatile, and about as simple to operate as anything you'd buy off the shelf.
</div>

</section>
