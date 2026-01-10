---
layout: default
---


<div align="center">
  <h2 class="no-underline">Electric Outboard Motor - University of Michigan Electric Boat Team</h2>
</div>

<img src="/assets/images/outboardCad.png" alt="Screenshot outboard motor CAD" class="center-image">

<div align="center">
  <h3><span class="subheader-underline">Overview</span></h3>
</div>

<div align="center">
  <h5 class="no-underline">
This project is a part of the University of Michigan Electric Boat Team's 2025/26 competition boat. Our team entered the 2026 PEP Workforce Development Competition, an electric boat race hosted by the American Society of Naval Engineers (ASNE) in Pourtsmouth, VA. This coming April, our team will compete in the crewed, planing hull division, which is a 5 mile race geared towards top-end speed (there are only 9 turns in the course). The competition enforces strict rules regarding what boats are allowed to compete. This impacted our design greatly, and caused us to place a large emphasis on efficiency and weight-redudction. I worked on the outboard motor sub-team, and we were responsible for creating a fully electric outboard motor with a continuous power output of atleast 40 horsepower and an operating voltage under 55V per the competition rules. This voltage regulation was extremely limiting, and it greatly shaped our motor design. 
    </h5>
</div>

<div align="center">
  <h3><span class="subheader-underline">Constraints</span></h3>
</div>

<div align="center">
  <h5 class="no-underline">
There were two key constraints limiting the design of the outboard motor and the boat as a whole. Per the competition rules, our boat's battery had to have a voltage at or below 55.5V and a capacity at or below 500Ah. Our team also imposed additional constraints, as we aimed to create the fastest boat possible. For the outboard, we were to make a unit capable of outputting atleast 40 horsepower continuous. This goal, combined with the voltage limit, made it very difficulty to select an electric motor to power our outboard. At such a low voltage we were not able to find motors capable of producing the power necessary. This resulted in us choosing three smaller motors and linking them through a custom gearbox. The gearbox was another major design challenge, as we had to design it completely from scratch while taking into consideration weight and reliability.
    </h5>
</div>




<div align="center">
  <h2 class="no-underline">Custom 3D Printer Build</h2>
</div>

<img src="/assets/images/frontView2.jpeg" alt="Screenshot of 3D Printer CAD" class="center-image">

<div align="center">
  <h3><span class="subheader-underline">Overview</span></h3>
</div>

<div align="center">
  <h5 class="no-underline">
The inspiration for this project came from the first 3D printer I owned: a Creality Ender 3. I bought that machine for $150, and it taught me much about 3D printing and additive manufacturing. However, the machine was often inconsistent. The finished prints were not always dimensionally accurate, and the printer could not reliably operate at speeds above 60mm/s. I searched to create a custom 3D printer that addresses all these issues, and also offers a larger build volume. My initial designs took inspiration from several popular models of 3D printers, including the Creality CR-10 and Prusa i3 MK3s. I looked to replicate the CR-10's massive build volume, while retaining the excellent print quality of the Prusa i3. To do this, I borrowed strengths from each machine's design, while engineering new solutions to their weaknesses.
    </h5>
</div>

<div align="center">
  <h3><span class="subheader-underline">Constraints</span></h3>
</div>

<div align="center">
  <h5 class="no-underline">
This project was limited by several key constraints. First, it had a total budget of $1000. All material and development costs were not able to exceed that figure. Next, the 3D printer must be able to be built without the use of advanced machining processes (mill, lathe, CNC). Since I did not have access to a machine shop, it was necessary that all custom parts on the machine are able to be 3D printed rather than machined. Additionally, the finished product must be able to print at 100mm/s while retaining tolerances of +/- 0.5mm. At speeds of 50mm/s, it must have tolerances of +/- 0.2mm or better. Finally, the printer must be able to be easy to operate, with a screen that displays relevant information about print time and temperature readings.
     </h5>
</div>

<div align="center">
  <h3><span class="subheader-underline">The Build</span></h3>
</div>

<div style="display: flex; align-items: center; gap: 20px;">
  <div>
    <img src="/assets/images/printerFrame.png" style="width: 250px;">
  </div>

<div style="flex: 1;">
  <h5 class="no-underline">
The first step in the build was assembling the frame. 2020 and 2040 aluminum extrusions stood out as the most effective material for several reasons. First, they are affordable and readily available at a multitude of different sizes. Additionally, they are lightweight, stiff, and able to be fastened together easily. Aluminum profiles can be quickly fixed together with brackets, screws, and t-nuts. This allows for quick assembly and prototyping. It also makes the process of fastening components to the frame simple, as t-nuts can be inserted directly into the extrusions, eliminating the need to tap threads.</p>
    </h5>
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px;">
  <div>
    <img src="/assets/images/printerFrame2.png" style="width: 250px;">
  </div>
  
<div style="flex: 1;">
  <h5 class="no-underline">
After the assembly of the frame, the next step was mounting the Y and Z axis linear rods This was accomplished by fabricating custom parts that were 3D printed and mounted to the frame to secure the rods in place. Additionally, custom motor mounts were designed and mounted to attach the Y and Z axis stepper motors. The 2 Z-axis stepper motors received shaft couplers so that leadscrews can be attached, and the Y-axis motor received a belt pulley. Various other parts were also fabricated and attached during this step, including mounts for endstop sensors and the Y axis belt tensioner pulley. 
    </h5>
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px;">
  <div>
    <img src="/assets/images/frameComplete.png" style="width: 250px;">
  </div>

<div style="flex: 1;">
  <h5 class="no-underline">
Next, the X-axis gantry was assembled. It consists of 2 linear rods that attach to a custom 3D printed piece on each end. Those plastic pieces also contain bearings and leadscrew nuts, allowing the entire X-axis to be moved vertically. A stepper motor is mounted to the plastic bracket on the left, and the belt pulley is fixed to the bracket on the right. Another 3D printed piece is attached to the bearings on the X-axis linear rods. This will serve as the mount for the hot-end and part cooling fan. 
    </h5>
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px;">
  <div>
    <img src="/assets/images/printerHotend.png" style="width: 250px;">
  </div>

<div style="flex: 1;">
  <h5 class="no-underline">
After the assembly of the X, Y, and Z axis movement systems, the heated bed and hot-end assemblies were then built and installed. The heated bed rests on top of an aluminum plate that clamps onto the linear rod bearings with the use of custom parts. The bed is suspended above the carriage plate by 4 springs with long screws going through them. This allows for height adjustment of the heated bed, and it is the standard design for nearly every FDM 3D printer available. The hot-end assembly consists of a 3D printed mounting plate that clamps onto the X-axis bearings. The hot-end is attached directly to the mounting plate, and a cooling fan and duct are also screwed on. The drive belt is also fixed to the rear of the mounting plate so that the entire assembly can be moved. 
    </h5>
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px;">
  <div>
    <img src="/assets/images/printerExtruder.png" style="width: 250px;">
  </div>

<div style="flex: 1;">
  <h5 class="no-underline">
Next, the extruder assembly was made. It consists of a stepper motor, custom mounting bracket, and extruder. I used an off-the-shelf extruder due to its affordability and design complexity. A Bowden style extruder was chosen for this build, due to this printer's emphasis on printing speed. Bowden extruders push filament through a tube, into the hot-end. This allows the stepper motor and extruder to be mounted to the frame of the printer, rather than directly to the hot-end. Direct-feed extruding systems often create an effect known as "ringing" at higher print speeds, due to too much weight being placed on the hot-end. Additionally, since weight is not a consideration, a bigger stepper motor can be used. This further enables high-speed printing, as larger motors overheat less.
    </h5>
  </div>
</div>

<div style="display: flex; align-items: center; gap: 20px;">
  <div>
    <img src="/assets/images/printerElectronics.png" style="width: 250px;">
  </div>

<div style="flex: 1;">
  <h5 class="no-underline">
Finally, 4 key electronics were selected. First, a 24V 350W power supply was chosen to power the printer. Then, a BigTreeTech SKR Mini E3 was chosen to be this printer's mainboard. This mainboard is extremely affordable at around $40, and it allows all of the stepper motors and sensors to be plugged in and controlled. It's also a very robust option, with a 32-bit processor, silent TMC2209 motor drivers, and a multitude of fan ports. It also meshes well with the BTT TFT35 LCD screen, which I chose to be the screen for this printer due to its affordability, clean UI, and touchscreen function. Finally, I chose a 25A mosfet to control the heated bed, as the main-board's built-in mosfet was not adequate. Custom enclosures were designed and 3D printed to hold all of these parts, as well as cooling fans where necessary.
    </h5>
  </div>
</div>

<div style="display: flex; justify-content: center;  align-items: center; gap: 20px; flex-wrap: nowrap;">
    <img src="/assets/images/printerComplete2.png" style="width: 400px;">
    <img src="/assets/images/printerComplete3.png" style="width: 400px;">
  </div>
  
<div style="display: flex; justify-content: center;  align-items: center; gap: 20px; flex-wrap: nowrap;">
    <img src="/assets/images/sideView.jpeg" style="width: 400px;">
    <img src="/assets/images/rearView.jpeg" style="width: 400px;">
  </div>

<div style="display: flex; justify-content: center;  align-items: center; gap: 20px; flex-wrap: nowrap;">
    <img src="/assets/images/extruder.jpeg" style="width: 400px;">
    <img src="/assets/images/xCarriageSide.jpeg" style="width: 400px;">
  </div>

<div style="display: flex; justify-content: center;  align-items: center; gap: 20px; flex-wrap: nowrap;">
    <img src="/assets/images/mainboard.jpeg" style="width: 400px;">
    <img src="/assets/images/mosfet.jpeg" style="width: 400px;">
  </div>
  
<p>
<div align="center">
  <h3><span class="subheader-underline">Conculsion</span></h3>
</div>
</p>

<div align="center">
  <h5 class="no-underline">
<p>This project was very successful. The finished printer achieved almost all of the goals I had in mind. It was able to print roughly 20mm/s faster than my Creality Ender-3 while retaining the same print quality. However, speed was not ultimately this printer's greatest strength, due to the large print surface. While the X-axis was set up to be light weight, the sliding bed assembly was relatively heavy. Moving it at overly high speeds resulted in the stepper motor overheating and worsened print quality. A major success of this printer was its large build volume of 280mm x 280mm x 300mm, compared to the Ender 3's build volume of 220mm x 220mm x 250mm. Additionally, the machine offers excellent dimensional accuracy due to the linear rod bearing system. While many cheaper 3D printers use v-slot wheels that slide along the aluminum extrusions, my machine utilized linear rods and bearings. This system is superior as it offers less rolling resistance and better reliability (plastic v-slot wheels often wear out easily). The result was dimensional accuracy of around +/- 0.1mm in all of my tests, which was the greatest success of this project. Another unintended perk of this 3D printer is its capacity for high temperature printing. While many 3D printers are typically rated up to 240 degree Celcius, this one has an all-metal hot-end, and can achieve temperatures up to 300 Celcius. This enables it to print a multitude of different filaments. Finally, I am proud of the machine's form factor and usability. The frame of the machine was extremely stiff and lightweight, and it is extremely easy to mount accessories to it in the future. The heated bed is magnetic, allowing build surfaces to be quickly swapped. Additionally, the LCD touchscreen I added makes using the machine very straightforward and easy.</p>

<p>Overall, this project was very enjoyable and informative. I learned much about how FDM 3D printers work, and how to design them in order to meet certain criteria. The result was not perfect but it was an improvement in many ways compated to my first 3D printer. Additionally, at around $600, I spent less than I had budgeted. In this project, I also increased my CAD skills, as I modeled many different custom parts in Onshape and Fusion 360. I then created a full assembly of the machine in CAD, in order to ensure everything would fit together properly.</p>
    </h5>
</div>
