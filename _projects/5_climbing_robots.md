---
layout: page
title: Climbing Robots for In Situ Mucus Sensing
description: Millimeter-size soft robots that steer on wet tissue and anchor wireless sensors to measure mucus viscosity in place.
img: assets/img/projects/card_climbing_robot.jpg
importance: 5
related_publications: true
---

| | |
| --- | --- |
| **My role** | First author (mucus sensing) and co-first author (climbing robots) |
| **Team** | Dong Lab, Vanderbilt University |
| **Publications** | {% cite xiao2024mucus xu2023climbing %}; U.S. patent application 18/882,837 |
| **Skills** | Soft robot design, Cosserat rod modeling, electromagnet and permanent-magnet actuation, Hall-effect sensing, X-ray guided testing |

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/mucus_fig1_concept.jpg" title="Soft climbing robot delivering wireless viscosity sensors" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Concept: a capsule releases a soft climbing robot that peels its footpads off the tissue to move and leaves wireless viscosity sensors on the colon wall for imaging-guided readout. Adapted from Xiao et al., <em>Advanced Functional Materials</em>, 2024.
</div>

### The problem

Mucus viscosity in the gut reflects hydration and disease, but today it can only be measured on samples taken out of the body. A sensor has to reach and stay on slippery, folded tissue without wires.

### What I built

- **Climbing robots**: rod-shaped magnetic soft robots with adhesive footpads that peel and re-attach, giving omnidirectional steering on wet tissue. I modeled them with Cosserat rod theory.
- **Sensor delivery**: a peel-and-load motion that places a wireless magnetic viscosity sensor (or a drug patch) on the tissue.
- **Readout**: under an applied field, the sensor's magnetic disk turns against the surrounding mucus. Its response across shear rates gives the local viscosity.
- **Actuation hardware**: a coil electromagnet array with a Hall-effect field sensor, and a permanent magnet on motorized stages.

### Results

- Measured mucus viscosity on porcine colon tissue ex vivo, and tracked how it changed as the mucus was dehydrated or diluted.
- Drove the robot and placed sensors under X-ray guidance.

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/mucus_actuation_setups.jpg" title="Actuation and sensing setups" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Electromagnet array with a Hall-effect sensor, and a permanent-magnet system on a linear stage, each operating a soft robot with a viscosity sensor on porcine colon tissue. Adapted from Xiao et al., <em>Advanced Functional Materials</em>, 2024.
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/mucus_xray_setup.jpg" title="X-ray guided operation" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  A rotating magnet drives the climbing robot inside a colon-tissue phantom under X-ray imaging. Adapted from Xiao et al., <em>Advanced Functional Materials</em>, 2024.
</div>

