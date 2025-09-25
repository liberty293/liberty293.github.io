---
layout: post
title: All Robotics Projects
date: 2000-09-12 00:00:00 +0300
show_date: false
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: mechatronics.png # Add image post (optional)
tags: [Robotics, Design, Robotics, 3D Printing] # add tag
---
- [Traditional Robotics](#traditional-robotics)
- [Soft Robotics](#soft-robotics)

## Traditional Robotics
### Bio-Inspired
Elizabeth Childs, Nicholas Kim, Gamitha Wijekoon, Jacob Twig
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
<iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://drive.google.com/file/d/1h9IVoKSmx_UT2bt7iiizLdghxeo6r52Q/preview" ></iframe>
</div>
The Flic Flac Spider is a newly discovered spider species in Morocco that moves by somersaulting away from its enemies. This is achieved by moving its legs in a flic flac motion, giving it the name: Flic Flac Spider. 

Using only four servos, I worked on a team with three other engineers to recreate this bio-inspired robot. The goal was to travel 35 body lengths in 2 minutes. In the end, we traveled 35 body lengths in 6 seconds, scoring first out of 13 teams.

### Autonomous Collection and Retrieval 
<p align="center">
  <img src="{{site.baseurl}}/assets/img/mechatronics/210.jpeg" width="60%"/>
</p>
Mahogany was tasked with autonomously "herding sheep" (transporting balls) from a designated loading area to a scoring area with the ability to navigate holes in the playing field without losing any sheep. The robot needed to secure the balls throughout its journey so we designed a "playpen" structure that did not allow for the balls to leave the manipulation space of the robot. The robot also had a two-tier chassis that allowed us to carefully store the batteries on the bottom and the electronic components (microcontroller, motor driver, LEDs, potentiometer, voltage regulators, switch). The motors are attached via mounts secured underneath the bottom plate.

<p align="center">
  <a href="https://me210mahogany.weebly.com/mechanical.html" style="text-align: center;">Link to Project Website</a>
</p>

### Fluid Sampling
![osv]({{site.baseurl}}/assets/img/mechatronics/enes100.png)
The purpose of this project is to make an Over Sand Vehicle (OSV) that can navigate over sand and complete several tasks. The robot must navigate from a random spot with a random orientation behind a wall. After clearing the wall, it must first maneuver itself within 250 mm of an acidic chemical pool, take a sample, read the pH, and neutralize the acid.

<p align="center">
  <a href="https://docs.google.com/document/d/1aBzL9z7X1HLJ2TiHQf48vUezOyahv3V6ZAjhfT_bGos" style="text-align: center;">Link to Design Report</a>
</p>

### Explosive Ordinance Disposal
![cambodia]({{site.baseurl}}/assets/img/mechatronics/cambodia.png)
As a result of the Vietnamese War many unexploded ordinances were dangerously left in Cambodia. While the majority of the ordinances have been found thanks to robotics, much of the area is still uninhabitable due to the ordinances that are unreachable due to the dense forest. To combat these challenges, I created a small, modular robot to navigate the underbrush. 

## Soft Robotics
### Additive Manufacturing
![bam]({{site.baseurl}}/assets/img/bam.png)
PolyJet-based additive manufacturing (or “threedimensional (3D) printing”) techniques allow for micro-tomesoscale fluidic systems to be produced with multiple, fully integrated materials and unparalleled geometric versatility (due to the use of sacrificial support materials). Although the PolyJet 3D printing process is autonomous and fast, the post-processing methods required to remove the sacrificial materials can be exceedingly time-intensive for systems with enclosed channels, often resulting in device degradation. To bypass such issues, here we present a novel “additive assembly” strategy for realizing PolyJet-printed multi-material microfluidic components. In this work, we print a microfluidic capacitor as two separate halves to enable facile support material removal, and then fasten the parts together via designed integration features. Fabrication results revealed a significant reduction in post-processing time by approximately 98% compared to enclosed control designs. Experimental results for burst-pressure testing – a measure of component integrity – revealed that the additively assembled microfluidic capacitors retained a maximum internal pressure in excess of 189 kPa before failure. The results suggest that the presented additive assembly strategy holds promise for greatly extending the utility of PolyJet 3D printing for micro- and millifluidic applications.

<p align="center">
  <a href="{{site.baseurl}}/bam-lab" style="text-align: center;">Link to Page</a>
</p>

### Silicon Molding for Bipedal Locomotion
![foot]({{site.baseurl}}/assets/img/manufacture/foot.png)
This project redesigned Cassie’s bipedal robot feet to reduce the loud, high-impact forces caused by its original hard feet, which stressed mechanical parts and hindered safe human–robot interaction. By exploring different geometries (collapsible cones, Purple Mattress–style diamonds, and honeycomb patterns) and materials (silicones, foams, and gels), the team tested prototypes on force plates, simulations, and Cassie itself. The hexagonal honeycomb design with foam inserts proved most effective, reducing peak impact forces by over 47%, increasing time to peak force by more than 600%, and cutting overall step impact by more than 90%, all while remaining compatible with Cassie’s locomotion controls. This balance of compliance and stiffness allowed the robot to absorb impacts without sacrificing stability, demonstrating how structural and material innovations can dramatically improve robotic locomotion performance.

<p align="center">
  <a href="{{site.baseurl}}/osu" style="text-align: center;">Link to Page</a>
</p>


### Robotic Fingers
![softrobo]({{site.baseurl}}/assets/img/manufacture/softrobo.png)
Created soft robotic fingers which curved based on pressurized air. Various designs were fabricated to manipulate analyze the point and radius of curvature for a given input pressure




