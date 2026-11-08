---
layout: page
title: Robotic Catheter Navigation
description: A 1.75 mm soft magnetic catheter steered by a robot-arm actuation platform through ducts as narrow as 2 mm.
img: assets/img/projects/catheter.jpg
importance: 1
---

| | |
| --- | --- |
| **My role** | Lead engineer: actuation platform, catheter design and fabrication, modeling, tracking, and testing |
| **Team** | Dong Lab, Vanderbilt, with a gastroenterologist collaborator |
| **Status** | Ongoing, not yet published |
| **Skills** | Magnetic actuation, Franka Panda integration, Cosserat rod modeling, vision-based tracking, phantom and ex vivo testing |

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/catheter.jpg" title="Wheel-based soft magnetic robotic catheter" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Concept: a tethered wheel-based robotic catheter and an untethered wheel-based robot navigating the biliary tract (left); magnetic wheels on a soft back beam (right).
</div>

### The problem

Endoscopic procedures in the biliary tract (ERCP) must reach narrow, branching ducts. Conventional catheters struggle to turn sharply and pick a branch, which limits access and increases procedure time and risk.

### What I built

- **Actuation platform.** A Franka Panda robot arm carrying a permanent magnet, with magnetic-field prediction, robot tracking, and position control.
- **Catheter.** A 1.75 mm-wide wheel-based soft magnetic catheter. Magnetic wheels on a soft back beam roll along the duct wall, and Cosserat rod models predict its deformation and locomotion.
- **Tracking.** AprilTag- and color-segmentation-based tracking of the actuation system and the catheter during navigation.
- **Clinical workflow.** An ERCP-compatible delivery catheter for deploying and retrieving the robot.

### Results

- Navigated ducts as narrow as **2 mm** and turns up to **150°**, and selected target branches at bifurcations.
- Tested in a 3D-printed biliary-tract phantom and in ex vivo porcine anatomy with a gastroenterologist.

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include video.liquid path="assets/video/robot_locomotion.mp4" class="img-fluid rounded z-depth-1" controls=true muted=true loop=true poster="/assets/img/video_poster_locomotion.jpg" %}
  </div>
</div>
<div class="caption">
  A wheel-based magnetic soft robot driven and steered by external magnetic fields, shown in two camera views.
</div>
