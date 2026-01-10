<div class="section">
  <h2 class="section-title no-underline">
    Electric Outboard Motor – University of Michigan Electric Boat Team
  </h2>

  <img src="/assets/images/outboardCad.png"
       alt="Outboard motor CAD"
       class="center-image">

  <h3 class="section-title">
    <span class="subheader-underline">Overview</span>
      </h3>

<h5 class="about-text">     
This project is a part of the University of Michigan Electric Boat Team's 2025/26 competition boat. Our team entered the 2026 PEP Workforce Development Competition, an electric boat race hosted by the American Society of Naval Engineers (ASNE) in Pourtsmouth, VA. This coming April, our team will compete in the crewed, planing hull division, which is a 5 mile race geared towards top-end speed (there are only 9 turns in the course). The competition enforces strict rules regarding what boats are allowed to compete. This impacted our design greatly, and caused us to place a large emphasis on efficiency and weight-redudction. I worked on the outboard motor sub-team, and we were responsible for creating a fully electric outboard motor with a continuous power output of atleast 40 horsepower and an operating voltage under 55V per the competition rules. This voltage regulation was extremely limiting, and it greatly shaped our motor design.
  </h5>
</div>

  <h3 class="section-title">
    <span class="subheader-underline">Constraints</span>
  </h3>

  <p class="about-text">
    There were two key constraints limiting the design of the outboard motor and the boat as a whole. Per the competition rules, our boat's battery had to have a voltage at or below 55.5V and a capacity at or below 500Ah. Our team also imposed additional constraints, as we aimed to create the fastest boat possible. For the outboard, we were to make a unit capable of outputting atleast 40 horsepower continuous. This goal, combined with the voltage limit, made it very difficulty to select an electric motor to power our outboard. At such a low voltage we were not able to find motors capable of producing the power necessary. This resulted in us choosing three smaller motors and linking them through a custom gearbox. The gearbox was another major design challenge, as we had to design it completely from scratch while taking into consideration weight and reliability.
  </p>
</div>



<div class="section">
  <h2 class="section-title no-underline">
    Custom 3D Printer Build
  </h2>

  <img src="/assets/images/frontView2.jpeg"
       alt="Custom 3D printer front view"
       class="center-image">

  <h3 class="section-title">
    <span class="subheader-underline">Overview</span>
  </h3>

  <p class="about-text">
The inspiration for this project came from the first 3D printer I owned: a Creality Ender 3. I bought that machine for $150, and it taught me much about 3D printing and additive manufacturing. However, the machine was often inconsistent. The finished prints were not always dimensionally accurate, and the printer could not reliably operate at speeds above 60mm/s. I searched to create a custom 3D printer that addresses all these issues, and also offers a larger build volume. My initial designs took inspiration from several popular models of 3D printers, including the Creality CR-10 and Prusa i3 MK3s. I looked to replicate the CR-10's massive build volume, while retaining the excellent print quality of the Prusa i3. To do this, I borrowed strengths from each machine's design, while engineering new solutions to their weaknesses.
  </p>

  <h3 class="section-title">
    <span class="subheader-underline">Constraints</span>
  </h3>

  <p class="about-text">
This project was limited by several key constraints. First, it had a total budget of $1000. All material and development costs were not able to exceed that figure. Next, the 3D printer must be able to be built without the use of advanced machining processes (mill, lathe, CNC). Since I did not have access to a machine shop, it was necessary that all custom parts on the machine are able to be 3D printed rather than machined. Additionally, the finished product must be able to print at 100mm/s while retaining tolerances of +/- 0.5mm. At speeds of 50mm/s, it must have tolerances of +/- 0.2mm or better. Finally, the printer must be able to be easy to operate, with a screen that displays relevant information about print time and temperature readings.
  </p>

  <h3 class="section-title">
    <span class="subheader-underline">The Build</span>
  </h3>

  <div class="about-row">
    <img src="/assets/images/printerFrame.png" alt="Printer frame assembly">

  <p class="about-text">
The first step in the build was assembling the frame. 2020 and 2040 aluminum extrusions stood out as the most effective material for several reasons. First, they are affordable and readily available at a multitude of different sizes. Additionally, they are lightweight, stiff, and able to be fastened together easily. Aluminum profiles can be quickly fixed together with brackets, screws, and t-nuts. This allows for quick assembly and prototyping. It also makes the process of fastening components to the frame simple, as t-nuts can be inserted directly into the extrusions, eliminating the need to tap threads.
    </p>
  </div>

  <div class="about-row">
    <img src="/assets/images/printerFrame2.png" alt="Printer frame assembly">

  <p class="about-text">
After the assembly of the frame, the next step was mounting the Y and Z axis linear rods This was accomplished by fabricating custom parts that were 3D printed and mounted to the frame to secure the rods in place. Additionally, custom motor mounts were designed and mounted to attach the Y and Z axis stepper motors. The 2 Z-axis stepper motors received shaft couplers so that leadscrews can be attached, and the Y-axis motor received a belt pulley. Various other parts were also fabricated and attached during this step, including mounts for endstop sensors and the Y axis belt tensioner pulley.
    </p>
  </div>
