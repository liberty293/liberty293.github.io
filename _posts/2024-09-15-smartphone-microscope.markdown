---
layout: post
title: Smartphone-Enabled Microscope
subtitle: Elizabeth Childs, Isha Jain, Josephine Miko, Trisha El Chemaly, Ashley Neall
date: 2024-09-15 00:00:00 +0300
description: A low-cost, 3D-printed microscope whose real focus knob, objective turret, and slide stage drive high-resolution biological imagery on a connected smartphone.
img: microscope/micro.png
tags: [CAD, 3D Printing, Embedded Systems, Sensor Integration & Fusion, Mobile App Development, Mentorship, Classroom Deployment, User Studies, Mechatronics]
pillar: interfaces
glance:
  - label: Role
    value: Project lead. Designed and built the device and its mobile app, and mentored an undergraduate researcher on the project.
  - label: Deployment
    value: Tested with students in classrooms
  - label: Tools & techniques
    value: CAD, 3D printing, microcontroller programming, sensor integration (encoders, magnetic detents, potentiometers), mobile app development, and designing for low cost.
---
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://drive.google.com/file/d/17hLX-6uEKsp1sqATgGSKgOgYhiyKpDla/preview" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>

In many classrooms, students learn about cells and microorganisms from static textbook images because microscopes are expensive to buy and maintain. This microscope keeps the physical practice of microscopy (focusing, changing magnification, and moving the slide) but replaces the fragile optics with a smartphone. Students turn real knobs on a low-cost, 3D-printed device, and the connected phone shows high-resolution biological imagery that responds to every adjustment.

## Why a Hybrid Microscope?
- **Tactile learning matters.** Real lab work builds muscle memory and spatial reasoning that simulations rarely capture, so the design keeps those physical controls at the center.
- **Smartphones are everywhere.** The phone serves as the display, the computing platform, and the connection for the whole experience.
- **Accessible hardware.** Off-the-shelf microcontrollers and 3D-printed parts cut the cost to a fraction of a commercial microscope, making it practical for resource-constrained schools.

## Technical Overview
- **Focus knob:** A rotary encoder tracks the focus knob, mirrored as fine-grained focus changes on the smartphone display.
- **Objective turret:** Magnetic detents signal changes in magnification, swapping the image set to reveal zoomed-in structures.
- **Slide stage:** Two-axis potentiometers track how the specimen moves, so the virtual slide pans smoothly with each student's input.
