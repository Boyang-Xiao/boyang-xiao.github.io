---
layout: page
title: Robotic Catheter Navigation
description: A 1.75 mm soft magnetic catheter steered by a robot-arm actuation platform through ducts as narrow as 2 mm. (Ongoing)
img: assets/img/projects/catheter.jpg
importance: 1
---

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/catheter.jpg" title="Wheel-based soft magnetic robotic catheter" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  Concept: a tethered wheel-based robotic catheter and an untethered wheel-based robot navigating the biliary tract (left); magnetic wheels on a soft back beam (right).
</div>

**Challenge.** Navigating narrow, branching anatomical ducts with a miniature flexible device.

**What I did.**

- Built a Franka Panda-based magnetic actuation platform with magnetic-field prediction, robot tracking, and position control.
- Designed and fabricated a 1.75 mm-wide wheel-based soft magnetic catheter, and used Cosserat rod models to predict its deformation and locomotion.
- Developed AprilTag- and color-segmentation-based tracking of the actuation system and robot during endoluminal navigation.
- Designed an ERCP-compatible delivery catheter and validated robot delivery and retrieval in an anatomical phantom.

**Validation.** Navigated ducts as narrow as 2 mm, turns up to 150°, and targeted branches at bifurcations. Tested in a 3D biliary-tract phantom and in ex vivo porcine anatomy with a gastroenterologist.

**Skills.** Magnetic actuation, robot integration, Cosserat rod modeling, vision-based tracking, experimental validation.

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include video.liquid path="assets/video/robot_locomotion.mp4" class="img-fluid rounded z-depth-1" controls=true muted=true loop=true poster="/assets/img/video_poster_locomotion.jpg" %}
  </div>
</div>
<div class="caption">
  A wheel-based magnetic soft robot driven and steered by external magnetic fields, shown in two camera views.
</div>
