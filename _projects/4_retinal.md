---
layout: page
title: Precision Calibration for Retinal Surgical Robotics
description: Calibration and compensation for Eye Robot 3.0 that cut residual tool-tip error to under 20 micrometers.
importance: 4
related_publications: true
---

**Challenge.** Reducing positioning error in Eye Robot 3.0, a cooperative robot for robot-assisted retinal surgery (AMIRo Lab, Johns Hopkins University).

**What I did.**

- Calibrated the Delta robot and tilting mechanism with a 21-parameter kinematic error model and calibration workflow.
- Applied Bernstein polynomial compensation to correct the remaining nonlinear error.
- Implemented inverse kinematics, Cartesian position control, and experimental data logging using ROS and CISST.
- Developed cooperative control with a remote-center-of-motion constraint for hands-on instrument manipulation.

**Validation.** Residual tool-tip position error under 20 micrometers after calibration and compensation.

**Skills.** Kinematic calibration, C++, ROS, CISST, precision testing.

**Publication.** {% cite xiao2022delta %}
