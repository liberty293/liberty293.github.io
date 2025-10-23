---
layout: post
title: Smartphone-Enabled Microscope for Scalable Training
subtitle: Elizabeth Childs · Stanford HCI Group
date: 2024-09-15 00:00:00 +0300
description: Designing a low-cost, tactile microscope that pairs smartphones with situated bio workflows so cross-functional teams can interpret live cellular mechanisms together.
img: microscope/micro.png
tags: [Education Technology, Tangible Interfaces]
---

Training on physical equiptment is costly and often limited for many institutions. Taking educational microscopy as the research context, we investigate how we can scale physical training scenarios for a fraction of the cost. Instead of fully digitizing the experience, this project reimagines microscopy as a hybrid tangible–digital experience: learners handle a physical device with real knobs and objectives, while a connected smartphone displays high-resolution biological imagery synchronized to their actions. The aim is to preserve the embodied practices (e.g., focusing, changing magnification, and exploring slides) without the cost and fragility of traditional lab equipment.

## Why a Hybrid Microscope?
- **Tactile insight matters.** Expertise depends on muscle memory and spatial reasoning that pure screen-based tools flatten. Our design keeps those gestures at the center.
- **Smartphones are everywhere.** With more than 80% global adoption, a phone becomes the display, computation platform, and connectivity backbone for the experience.
- **Accessible hardware.** Off-the-shelf microcontrollers and 3D-printed components reduce per-unit cost, ubiquitizing access even in resource-constrained situations.


## Technical Overview
- **Focus knob:** A rotary encoder adjusts the objective carriage, mirrored as fine-grain focal changes on the smartphone display.
- **Objective turret:** A magnetic detent array signals changes in magnification, dynamically swapping the image set and revealing zoomed-in microstructures.
- **Slide stage:** Two-axis potentiometers track lateral specimen movement, enabling virtual slides to pan smoothly with each operator’s input.
- **Illumination:** Programmable LEDs mimic condenser adjustments, revealing how lighting shifts affect contrast and signal-to-noise.

## Demo
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://drive.google.com/file/d/17hLX-6uEKsp1sqATgGSKgOgYhiyKpDla/preview" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>

<p align="center"><em>Demo video of microscope.</em></p>


