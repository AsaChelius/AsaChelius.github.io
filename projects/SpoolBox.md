---
layout: project
type: project
image: img/Screenshot 2024-09-04 104249.png
title: "Filament Monitoring System"
date: 2024
published: true
labels:
  - 3D Printing
  - Arduino
  - 3D Modeling
summary: "I developed a 3D filament monitoring and isolation system for the Applied Research Laboroatory at UH Manoa."
---
  While interning at the ARL at UH Manoa, I was tasked with developing a 3D filament monitoring system that would isolate the filament from humidity. Humidity is known to be absorbed easily into 3D printing filament and result in a much worse print quality and resolution. I was tasked with 
isolating filament that is being used to print parts from humidity to prevent this problem. Additionally, ARL tasked me with monitoring the amount of 3D filament being used for a project, so I developed a weight monitoring system for the 3D filament that could track the change in mass of the 
filament spool over time. Combining both of these requirements, I designed and manufactured a working prototype. Following the design requirements that were given to me by the engineers that worked in the 3D printing lab, I fully CADed the prototype according to the real materials that I was
going to use, I created a bill of materials, and finally presented my design in a detailed design review in front of ARL's engineers. Once my design was approved, I ordered the materials and began manufacturing. 
  I used an Adafruit Feather M0 with RFM capabilites, 2 load cells, a variety of Adafruit sensors, and various other necessary electronic components to measure and record both the humidity of the box and mass of the 3D filament. The software required to record and transmit this information was
extensive, but for CUI purposes, I am not allowed to present it here. The project has a button and OLED user interface that allows the user to manage and record data with ease. Manufacturing the project was not simple and required a lot of redesign. Machining the plexiglas proved to be problematic
because we did not have a laser cutter on hand. Additionally, the plexiglas that was used was also warped in such a way that initailly prevented an airtight seal along the box's edge and required extra sealant to sufficiently dehumidify the box. The physical configuration of the load cells had to be redesigned 
five times to prevent a load cell drift that was more than 200g/hr. By the completion of my internship, however, the project was completed and met all design requirements.
  The msot well developed part of the project happened to be the software and electronics used to record and transmit the data about the humidity and weight inside the box. I was able to get the laod cells to read within an accuracy of 5 grams and the humidity within an accuracy of 1% relative. Currently, ARL
plans to build on the prototype that I created and expand it to all the printers that they have in their rapid prototyping unit.
<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

