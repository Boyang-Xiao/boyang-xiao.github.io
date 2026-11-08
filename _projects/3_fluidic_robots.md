---
layout: page
title: Microfluidic Miniature Soft Robots
description: 10 mm soft robots with on-board magnetic pumps and valves that crawl, walk, and climb on tissue, then sample or deliver liquid on command.
img: assets/img/projects/device_graphical_abstract.jpg
importance: 3
related_publications: true
---

| | |
| --- | --- |
| **My role** | First author. Co-conceived the idea; designed, fabricated, and tested the robots; co-wrote the paper |
| **Team** | Dong Lab with Vanderbilt University Medical Center Urology and the University of Tennessee |
| **Publication** | {% cite xiao2025device %} |
| **Skills** | Microfluidic design, layer-by-layer fabrication, magnetic valve design, locomotion control, ultrasound and X-ray guided testing |

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/fluidic_fig1_concept.jpg" title="Soft robot with integrated wireless fluidic modules" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Concept: a swallowable capsule releases a two-module soft robot. Each module has a magnetic inlet valve, an outlet valve, and a pump, so the robot can sample biofluid, deliver liquid, or eject bioadhesive while climbing, walking, or crawling. From Xiao et al., <em>Device</em>, 2025 (CC BY-NC-ND 4.0).
</div>

### The problem

Millimeter-scale magnetic robots can reach places that endoscopes cannot, but they cannot handle liquid on command. The same magnetic field that deforms the robot to move it would also squeeze or open any on-board pump.

### What I built

- **A two-module robot** (about 10 × 3 × 2 mm) joined by an elastic hinge. Each module holds a fluidic chamber, magnetic inlet and outlet valves, and a spiked, bioadhesive footpad.
- **Wireless pumping**: superabsorbent fiber swells to drive liquid through a soft membrane piston. It absorbs 20 µL of water in two minutes and swells about 20×.
- **Decoupled control.** I designed the valve-opening thresholds (about 55 to 60 mT) well above the fields used for walking (10 to 30 mT), so the robot can move without triggering its fluidics.
- **Fabrication**: laser-machined PDMS and magnetic-elastomer layers bonded layer by layer, with hydrogel-coated channels.
- **Actuation**: a permanent magnet positioned by a robot arm or by motorized stages, driven with joysticks.

### Results

- Crawled, walked, and climbed on porcine tissue, with motion tracked under ultrasound and X-ray imaging.
- Sampled liquid at a chosen spot when the field was raised to 60 mT, then sealed the sample for retrieval.
- Released liquid cargo on demand. Ejecting bioadhesive kept the footpads from slipping while climbing.

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/fluidic_fig4_locomotion.jpg" title="Multimodal locomotion on tissue" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Crawling gait and speed prediction, crawling on porcine tissue and under ultrasound imaging, climbing, and a multimodal route on tissue. From Xiao et al., <em>Device</em>, 2025 (CC BY-NC-ND 4.0).
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/fluidic_fig5_sampling.jpg" title="Targeted liquid sampling" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  The robot crawls and walks to a target, opens its inlet valve to sample, then seals. Shown under optical and X-ray imaging, with sample recovery by deswelling the fiber. From Xiao et al., <em>Device</em>, 2025 (CC BY-NC-ND 4.0).
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/fluidic_actuation_setup.jpg" title="Magnetic actuation systems" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Actuation hardware: a permanent magnet on motorized stages with joystick control (a), and a permanent magnet carried by a robot arm (b). From the supplementary information of Xiao et al., <em>Device</em>, 2025.
</div>

