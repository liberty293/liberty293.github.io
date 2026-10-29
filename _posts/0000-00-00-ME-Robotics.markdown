---
permalink: /mechanical-design/
redirect_from: /ME-Robotics/
layout: post
title: Mechanical Design
date: 2000-09-12 00:00:00 +0300
show_date: false
listed: false
pillar: foundations
description: Custom hardware across haptic and autonomous robots, compliant and multi-material design, and CAD and manufacturing. These are the sensing, actuation, and fabrication skills behind my tangible interactions.
img: themes/mechanical-design.webp # Add image post (optional)
tags: [CAD, SolidWorks, 3D Printing, CNC Machining, Laser Cutting, Silicone Molding, Robotics, Mechatronics, Embedded Systems, Experimental Testing, Power Electronics, Motor Control]
---
I design and build custom hardware, from haptic, bio-inspired, and autonomous robots to soft robotics, multi-material 3D printing, CAD modeling, and machining. These skills in sensing, actuation, and fabrication enable custom physical inputs and outputs for tangible interactions.

- [Haptic Robotics](#haptic-robotics)
- [Traditional Robotics](#traditional-robotics)
- [Compliant and Multi-Material Design](#compliant-and-multi-material-design)
- [CAD and Manufacturing](#cad-and-manufacturing)

## Haptic Robotics
### KITE: A Free-Moving Haptic Robot
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.youtube-nocookie.com/embed/JxwKrtG6HAw?rel=0&start=20&end=120" frameborder="0" allowfullscreen></iframe>
</div>
I designed the mechatronics for KITE, a free-moving haptic robot. Gearless motors drive omni wheels so it can move and push in any direction, and a hybrid localization system fuses overhead camera tracking with motor feedback to keep force rendering precise between camera updates. An onboard camera, Raspberry Pi, battery, and buck and boost power converters all fit inside one compact body.

**Tools & techniques:** CAD, 3D printing, omni-wheel drivetrain design, motor integration, power electronics, embedded computing, sensor fusion, and computer vision.

<p align="center">
  <a href="{{site.baseurl}}/kite-kinesthetic-interface/" style="text-align: center;">Link to Page</a>
</p>

## Traditional Robotics
### Flic Flac Spider: A Somersaulting Bio-Inspired Robot
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
<iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://drive.google.com/file/d/1h9IVoKSmx_UT2bt7iiizLdghxeo6r52Q/preview" ></iframe>
</div>
Most bio-inspired robots walk. We built ours to flip. The Flic Flac spider, a species discovered in Morocco, escapes predators by somersaulting with a flic-flac motion of its legs, and we recreated that gait in a robot driven by only four servos.

The challenge was to travel 35 body lengths in 2 minutes. Our robot covered the distance in 6 seconds, 20 times faster than required, and placed **first out of 13 teams**.

**Tools & techniques:** Teensy microcontroller programming, IMU orientation sensing, coordinated servo control, and gait design for a dynamic, non-walking locomotion strategy.

### Mahogany: An Autonomous Ball-Herding Robot
<p align="center">
  <img src="{{site.baseurl}}/assets/img/mechatronics/210.jpeg" width="60%"/>
</p>
Mahogany had to autonomously "herd sheep," carrying balls from a loading area to a scoring area across a field with holes, without losing any along the way. Instead of building a gripper, we solved this mechanically with a laser-cut "playpen" that surrounds five balls at once, so the balls can't escape the robot whatever path it drives.

It navigates with IR line sensors and a state machine that counts field intersections to find the goal.

**Tools & techniques:** Teensy programming, motor control, power electronics, sensor integration, 3D printing, laser cutting, and state-machine design.

<p align="center">
  <a href="https://me210mahogany.weebly.com/mechanical.html" style="text-align: center;">Link to Project Website</a>
</p>

### Over-Sand Vehicle: Autonomous Fluid Sampling
![osv]({{site.baseurl}}/assets/img/mechatronics/enes100.png)
An autonomous robot that crosses sand, clears an obstacle wall, and reaches an acidic pool, where a 3D-printed arm samples the liquid and reads its pH before the robot neutralizes it with baking soda. When the motors couldn't pivot in sand, we solved it in software with a closed-loop "wiggle" turn that keeps the wheels from digging in.

**Tools & techniques:** Arduino programming, closed-loop navigation, servo mechanisms, fluid sampling, pH sensing, and 3D printing.

<p align="center">
  <a href="https://docs.google.com/document/d/1aBzL9z7X1HLJ2TiHQf48vUezOyahv3V6ZAjhfT_bGos" style="text-align: center;">Link to Design Report</a>
</p>

<!-- Hidden for now.
### Modular Robot for Explosive Ordnance Disposal
![cambodia]({{site.baseurl}}/assets/img/mechatronics/cambodia.png)
Unexploded ordnance from the Vietnam War still makes parts of Cambodia uninhabitable. Robots have cleared much of it, but dense forest keeps many sites out of reach of conventional platforms. I designed a small, modular robot that can move through the underbrush.

**Tools & techniques:** Modular robot architecture and compact mechanical design for constrained environments.
-->

## Compliant and Multi-Material Design
### Additive Assembly for 3D-Printed Microfluidics
![bam]({{site.baseurl}}/assets/img/bam.png)
Multi-material 3D printing can produce intricate fluidic devices, but cleaning support material out of enclosed channels is slow and often damages the part. Instead of printing the device closed, we printed it as two open halves with built-in fasteners and seals, then fastened them together. This cut post-processing time by about **98%**, and the assembled devices withstood burst pressures **comparable to or higher than** fully enclosed printed devices from prior work.

**Tools & techniques:** Multi-material 3D printing, SolidWorks, designing integrated fasteners and seals, and empirical testing.

<p align="center">
  <a href="{{site.baseurl}}/3d-printed-microfluidics/" style="text-align: center;">Link to Journal Paper</a>
</p>

### Impact-Absorbing Feet for the Cassie Bipedal Robot
![foot]({{site.baseurl}}/assets/img/manufacture/foot.png)
Cassie's hard feet slammed into the ground with every step. I designed new feet that absorb impact while staying stiff enough for the robot's balance control. After I tested cone, diamond, and honeycomb geometries in silicones, foams, and gels, the best design paired a silicone honeycomb with foam inserts. It cut peak impact force by over **47%** and overall step impact by over **90%**, with no changes to Cassie's controller.

**Tools & techniques:** Silicone and foam manufacturing, material characterization, force-plate testing, and designing within the constraints of an existing control system.

<p align="center">
  <a href="{{site.baseurl}}/cassie-impact-absorbing-feet/" style="text-align: center;">Link to Page</a>
</p>


### Pneumatic Soft Robotic Fingers
![softrobo]({{site.baseurl}}/assets/img/manufacture/softrobo.png)
Soft fingers that bend when inflated with air. I fabricated several designs and measured where and how sharply each one curved at a given pressure, to learn how the geometry controls the motion.

**Tools & techniques:** Silicone mold manufacturing, pneumatic actuation, and parametric empirical characterization.

## CAD and Manufacturing
### Dirt Bike Engine Recreated from Specifications
<div style="display: flex;">
    <div style="flex: .835;">
    <img src="{{site.baseurl}}/assets/img/cad/engine.png" alt="engine" style="max-height: 100%;">
    </div>
    <div style="flex: 1;">
        <iframe src="https://drive.google.com/file/d/1v3xmsTUhEDlkm4o_oAWPu2sqLWQheLOy/preview" width="100%" height="315" frameborder="0" allowfullscreen="true"></iframe>
    </div>
</div>

Our team recreated a Yamaha YZ250F dirt bike from its original technical specifications. I modeled the tailpipe and kickstand (left) and created the animation of the full assembly (right).

**Tools & techniques:** SolidWorks, technical CAD from specifications, large assembly modeling, and animation.

### Human-Powered Washing Machine
<div style="position: relative; padding-bottom: 56.25%; overflow: hidden; max-width: 100%;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://drive.google.com/file/d/1Qw2BKwE6Cvz-prcSErcbpnO3-9WOHrSe/preview" frameborder="0" allowfullscreen></iframe>
</div>
A washing machine that runs on human power instead of electricity, designed as a team entirely in CAD during the COVID-19 pandemic.

**Tools & techniques:** SolidWorks, mechanism design, and remote team-based design.

### CNC-Machined Parts
![CNC]({{site.baseurl}}/assets/img/manufacture/CNC.png)
I designed and CNC machined a working whistle (left) and a magnetic stamp with a fitted cover (right).

**Tools & techniques:** CAD, CNC machining, and designing for tight-fit assemblies.
