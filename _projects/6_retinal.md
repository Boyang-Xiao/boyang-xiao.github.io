---
layout: page
title: Precision Calibration for Retinal Surgical Robotics
description: Calibration and compensation for Eye Robot 3.0 that cut residual tool-tip error to under 20 micrometers.
img: assets/img/projects/retinal_sher.jpg
importance: 6
related_publications: true
---

| | |
| --- | --- |
| **My role** | Graduate researcher and first author, AMIRo Lab, Johns Hopkins University |
| **Publication** | {% cite xiao2022delta %} |
| **Skills** | Kinematic calibration, error modeling, C++, ROS, CISST, precision testing |

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/retinal_sher.jpg" title="Steady-Hand Eye Robot with Delta robot base in a clinical setup" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  The Steady-Hand Eye Robot (SHER) on its Delta robot base, set up with a surgical microscope and an eye phantom. Fig. 1 from Xiao et al., ISMR 2022 (author manuscript, PMC9484559; &copy; IEEE).
</div>

### The problem

Reducing positioning error in Eye Robot 3.0, a cooperative robot for robot-assisted retinal surgery (AMIRo Lab, Johns Hopkins University).

### What I built

- Calibrated the Delta robot and tilting mechanism with a 21-parameter kinematic error model and calibration workflow.
- Applied Bernstein polynomial compensation to correct the remaining nonlinear error.
- Implemented inverse kinematics, Cartesian position control, and experimental data logging using ROS and CISST.
- Developed cooperative control with a remote-center-of-motion constraint for hands-on instrument manipulation.

### Results

Residual tool-tip position error under 20 micrometers after calibration and compensation.


