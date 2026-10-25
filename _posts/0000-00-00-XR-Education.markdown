---
layout: post
title: Tangible Learning Experiences
date: 2017-04-06 13:32:20 +0300
show_date: false
listed: false
pillar: experiences
description: Classroom and field studies on augmenting real experiments, specimens, and environments, rather than replacing them, to deepen scientific reasoning and engagement.
img: themes/tangible-learning.webp # Add image post (optional)
tags: []
---
I run classroom and field studies to evaluate how digital augmentation deepens hands-on experiences. They cover an AR-enhanced pendulum lab, an AR yeast fermentation lab, and AR for outdoor field learning.

- [Augmenting Physical Labs](#augmenting-physical-labs)
- [Augmenting the Outdoors](#augmenting-the-outdoors)

## Augmenting Physical Labs
### AR-Enhanced Physics Lab
<p align="center">
  <img src="{{site.baseurl}}/assets/img/pendulum-interface.jpg" alt="AR interface overlaid on a real pendulum experiment" width="80%"/>
</p>
A real pendulum experiment augmented with AR measurement tools: a protractor anchored at the pivot, a live graph of energy flowing between potential, kinetic, and dissipated forms, and an automatic period counter. Instead of replacing the experiment, the overlays take over tedious measurement so students can focus on reasoning about their data. In a study with 52 students, the AR lab improved scientific reasoning over the traditional lab (Cohen's d = 0.63, Bayes factor 18.11) while maintaining interest and content mastery.

**Tools & techniques:** Augmented reality, computer vision, real-time data visualization, laser cutting, between-subjects user study, and Bayesian analysis.

<p align="center">
  <a href="{{site.baseurl}}/pendulum" style="text-align: center;">Link to Page</a>
</p>

### Visualizing Biological Mechanisms
<video autoplay muted loop playsinline preload="metadata" poster="{{site.baseurl}}/assets/img/enzyme/enzyme-app.jpg" style="width: 100%; height: auto; border-radius: 12px;">
  <source src="{{site.baseurl}}/assets/video/enzyme-dynamics.mp4" type="video/mp4">
</video>
An AR app that runs alongside a real high school biology lab on yeast fermentation. As students' balloons inflate, the app shows enzymes splitting sugar into alcohol and CO₂, and the CO₂ rising into each balloon. The app uses computer vision to track the volume of each real balloon and converts it into how many reactions the enzymes have catalyzed, so the animation, including how enzymes speed up or slow down with temperature, reflects the students' own experiment and shows the mechanism behind their observations. It has been tested at 5 institutions with over 100 students.

**Tools & techniques:** Unity, OpenCV, augmented reality, computer-vision volume tracking, and classroom deployment.

<p align="center">
  <a href="{{site.baseurl}}/enzyme-dynamics" style="text-align: center;">Link to Page</a>
</p>

## Augmenting the Outdoors
### AR for Outdoor Field Learning
![Kiki's Adventure outdoor AR app]({{site.baseurl}}/assets/img/kiki/teaser.png)
A narrative mobile app that turns a real eucalyptus tree into a hands-on science lesson for children. Computer vision recognizes the tree with over 96% accuracy, then AR activities anchor to it: children place virtual koalas in its branches, measure its height with AR perspective lines, and plant a virtual seedling that grows in the soil. In a study with 44 children in grades 4–6, the AR activities were among their favorite parts of the lesson, sparking curiosity and engagement outdoors.

**Tools & techniques:** Augmented reality, mobile app development, anchoring AR content in real-world locations, and field studies with children.

<p align="center">
  <a href="{{site.baseurl}}/kiki" style="text-align: center;">Link to Page</a>
</p>
