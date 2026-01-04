---
layout: default
---


<div align="center">
  <h2 class="no-underline">Electric Outboard Motor - University of Michigan Electric Boat Team</h2>
</div>
  
<div align="center">
  <h2 class="no-underline">Custom 3D Printer Build</h2>
</div>

<img src="/assets/images/printerCad.png" alt="Screenshot of 3D Printer CAD" class="center-image">

<div align="center">
  <h3><span class="subheader-underline">Overview</span></h3>
</div>

<div align="center">
  <h5 class="no-underline">
The inspiration for this project came from the first 3D printer I owned: a Creality Ender 3. I bought that machine for $150, and it taught me much about 3D printing and additive manufacturing. However, the machine was often inconsistent. The products were not always dimensionally accurate, print quality fluctuated, and the printer could not reliably operate at speeds above 60mm/s. I searched to create a custom 3D printer that addresses all of these issues, and has an even larger build volume. The final product leverages the strengths of several different commerically available 3D printers, while addressing many of their design weaknesses.
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
  <div>
    <img src="/assets/images/printerComplete2.png" style="width: 300px;">
    <img src="/assets/images/printerComplete3.png" style="width: 300px;">
  </div>

<div align="center">
  <h3><span class="subheader-underline">Issues</span></h3>
</div>

<div align="center">
  <h3><span class="subheader-underline">Conculsion</span></h3>
</div>
