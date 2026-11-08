---
layout: page
title: Wireless Valves for Bladder Drug Delivery
description: A cystoscope-deliverable soft patch whose wireless magnetic valves meter, multiplex, and monitor drug release in the bladder for days.
img: assets/img/projects/valves_fig1.jpg
importance: 2
related_publications: true
---

| | |
| --- | --- |
| **My role** | First author. Co-developed the methods; led the experiments, figures, and manuscript writing |
| **Team** | Dong Lab with Vanderbilt University Medical Center Urology |
| **Publication** | {% cite xiao2026valves %}, selected as Back Cover |
| **Skills** | Soft device design, magnetic valve modeling, multi-valve control, wireless LC sensing, bioadhesives, ex vivo testing |

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/valves_fig1.jpg" title="Magnetic valve-enabled soft robotic patch" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Concept and design: the patch is delivered through a cystoscope and anchored on the bladder wall; magnetic valves gate an osmotic pump; capacitor plates and an inductor coil let release be read out wirelessly. From Xiao et al., <em>Advanced Healthcare Materials</em>, 2026 (CC BY 4.0).
</div>

### The problem

Bladder cancer and interstitial cystitis need drug kept in the bladder for long periods. Catheter instillation washes out quickly, and existing sustained-release implants cannot be switched on and off, carry only one drug, and can irritate the bladder. Running several magnetic valves on one implant is hard because the valves pull on each other.

### What I built

- **Flexible magnetic valves** that seal a soft osmotic pump (superabsorbent fiber in a foldable chamber) and open when an external magnet rotates them.
- **A multi-valve control strategy** that orders the magnet's orientation so each valve opens on its own. This allows two drugs to be released independently or mixed on demand.
- **Wireless dose monitoring**: an LC resonant circuit whose resonant frequency shifts as the chamber empties, read out with a vector network analyzer.
- **A patterned bioadhesive patch** that holds the device on wet bladder tissue, plus a portable magnetic actuation unit for use outside the body.

### Results

- Valves open at about **10 mT**, and every operation stays **below 20 mT**, a field level generally considered safe.
- Release rate is set by the valve duty cycle (about **0.5 µL/s** when open). Doses stayed consistent over **7 days**.
- The patch stayed attached to porcine bladder tissue underwater for up to **10 days**.
- In an ex vivo porcine bladder, the resonance shifted from **7.89 to 6.90 MHz**, and then to **6.60 MHz** after the valves reopened, tracking the released volume under endoscopic view.

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/valves_fig4_multiplexed.jpg" title="Multiplexed release with four valves" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Coordinated control of four valves with a single magnet: independent release of two liquids and on-demand mixing. From Xiao et al., <em>Advanced Healthcare Materials</em>, 2026 (CC BY 4.0).
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-12 mt-3 mt-md-0">
    {% include figure.liquid loading="lazy" path="assets/img/projects/valves_fig6_exvivo.jpg" title="Cystoscope delivery and wireless monitoring in an ex vivo bladder" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
<div class="caption">
  Delivery with a steerable endoscope, anchoring, valve-controlled release, and resonance-frequency tracking of the released volume in an ex vivo porcine bladder, with X-ray views of the valves opening and closing. From Xiao et al., <em>Advanced Healthcare Materials</em>, 2026 (CC BY 4.0).
</div>

