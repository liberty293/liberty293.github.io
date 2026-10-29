---
permalink: /visualizing-biological-mechanisms/
redirect_from: /enzyme-dynamics/
layout: post
title: Visualizing Biological Mechanisms
date: 2026-10-24 00:00:00 -0700
pillar: experiences
description: An AR app, tested at 5 institutions with over 100 students, that runs alongside a real yeast fermentation lab and shows the enzyme activity behind each inflating balloon in sync with the students' own experiment.
img: enzyme/enzyme-app.jpg
fig-caption: The app overlaid on a real yeast lab, with cold, room-temperature, and hot solutions
tags: [Unity, OpenCV, Computer Vision, Augmented Reality, Classroom Deployment, Mentorship, User Studies]
glance:
  - label: Role
    value: Project lead. Designed and built the app, and mentored an undergraduate researcher on the project.
  - label: Team
    value: Elizabeth Childs and Ryan Li (undergraduate researcher)
  - label: Deployment
    value: Tested at 5 institutions with over 100 high school students
  - label: Tools & techniques
    value: Unity, OpenCV, augmented reality, computer-vision volume tracking, and classroom deployment.
---
<video controls muted loop playsinline preload="metadata" poster="{{site.baseurl}}/assets/img/enzyme/enzyme-app.jpg" style="width: 100%; height: auto; border-radius: 12px;">
  <source src="{{site.baseurl}}/assets/video/enzyme-dynamics.mp4" type="video/mp4">
</video>

In a classic high school biology lab on yeast fermentation, students mix yeast and sugar in test tubes, cap each tube with a balloon, and watch the balloons inflate at different rates depending on the water temperature. The observation is easy to see. The mechanism behind it isn't: enzymes break sugar down into alcohol and carbon dioxide, and the CO₂ is what fills the balloon. This app makes that hidden process visible while students run the real experiment, so they can connect what they observe to *why* it happens. It has been tested at **5 institutions with over 100 students**.

## Why Augment a Real Lab?
Simulations can show enzymes clearly, but they replace the experiment students are actually doing. Here the physical lab stays at the center. Students still mix the solutions, control the temperatures, and watch real balloons inflate, and the digital layer explains the mechanism behind what is happening in front of them.

## How It Works
Students set up three test tubes of yeast and sugar solution, one each in cold, room-temperature, and hot water, and cap each with a balloon. They then point a tablet at their own experiment.

- **Computer vision tracks the real balloons.** Students tap each balloon to tell the app which tube is which, and the app then uses computer vision to track each balloon and estimate its volume as it inflates.
- **Enzymes you can watch.** Animated enzymes bind to sugar molecules, split them into alcohol and CO₂, and the CO₂ floats up the tube into the balloon above it.
- **Temperature changes the reaction.** Enzymes move and react at different speeds depending on the temperature of each solution, matching what students see in their three tubes.
- **Synced to the students' own data.** The app converts each balloon's measured volume into how many reactions the enzymes have catalyzed and animates exactly that much activity, so the visualization reflects the students' own experiment, not a scripted one.
- **Multiple views of the same process.** A close-up "enzyme cam" for each tube, a live graph of balloon volume over time, and a bar showing how much of each tube's sugar has turned into CO₂.
- **Guided inquiry.** Prompts walk students through the questions on their lab worksheet as the experiment unfolds.
