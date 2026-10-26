---
layout: single
title: "Vehicle Dynamics Control at the Tire-Road Interface"
permalink: /research/vehicle-dynamics/
author_profile: true
---

<!--## Research Overview

My research investigates integrated powertrain and vehicle-level
dynamics control, with a focus on tire forces, vehicle stability,
and coordinated motion control.-->

Tire dynamics provides the critical link between powertrain operation and overall vehicle motion, as tire–road forces ultimately determine how propulsion and braking commands translate into vehicle movement. His research investigates transient tire dynamics, tire force estimation, and vehicle controllability to characterize the effects of tire behavior and actuator dynamics on vehicle motion. Building on these foundations, he explores tire-force-informed vehicle motion control and the coordination of powertrain, steering, and braking systems to improve vehicle stability, maneuverability, and motion-tracking performance.

<div style="display:flex; gap:24px; width:100%; align-items:flex-start;">

  <figure style="flex:1; min-width:0; margin:0; display:flex; flex-direction:column;">

    <div style="width:100%; height:300px; display:flex; align-items:center; justify-content:center;">
      <img src="{{ '/images/research/Tire_Force_Estimator.jpg' | relative_url }}"
           alt="Experimental Platform for Transmission Control"
           style="width:100%; height:100%; object-fit:contain; display:block;">
    </div>

    <figcaption style="width:100%; box-sizing:border-box; margin:0px 0 0; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.5;">
      Tire Force Estimator
    </figcaption>

  </figure>

  <figure style="flex:1; min-width:0; margin:0; display:flex; flex-direction:column;">

    <div style="width:100%; height:300px; display:flex; align-items:center; justify-content:center;">
      <img src="{{ '/images/research/ClosedLoopControlDiagram.jpg' | relative_url }}"
           alt="Real Vehicle"
           style="width:100%; height:100%; object-fit:contain; display:block;">
    </div>

    <figcaption style="width:100%; box-sizing:border-box; margin:0px 0 0; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.5;">
      Control diagram
    </figcaption>

  </figure>

</div>

**Highlighted Contributions**
1. Established a vehicle-dynamics framework incorporating transient tire characteristics and actuator dynamics to quantify recoverable vehicle-state regions under varying road and operating conditions.
2. Developed tire-dynamics-based methods for estimating tire forces using distributed in-tire acceleration measurements.
3. Investigated tire-force feedback and coordinated vehicle control strategies to improve path tracking and vehicle controllability, clarifying the role of tire–road interactions in connecting powertrain actuation with vehicle motion.

## Experimental Platform

<div style="display:flex; gap:24px; width:100%; align-items:flex-start;">

  <figure style="flex:1; min-width:0; margin:0; display:flex; flex-direction:column;">

    <div style="width:100%; height:300px; display:flex; align-items:center; justify-content:center;">
      <img src="{{ '/images/research/Tire_testbench.png' | relative_url }}"
           alt="Experimental Platform for Transmission Control"
           style="width:100%; height:100%; object-fit:contain; display:block;">
    </div>

    <figcaption style="width:100%; box-sizing:border-box; margin:0px 0 0; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.5;">
      Tire Force Test Bench
    </figcaption>

  </figure>

  <figure style="flex:1; min-width:0; margin:0; display:flex; flex-direction:column;">

    <div style="width:100%; height:300px; display:flex; align-items:center; justify-content:center;">
      <img src="{{ '/images/research/vehicle-dynamics.jpg' | relative_url }}"
           alt="Real Vehicle"
           style="width:100%; height:100%; object-fit:contain; display:block;">
    </div>

    <figcaption style="width:100%; box-sizing:border-box; margin:0px 0 0; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.5;">
      Real Vehicle
    </figcaption>

  </figure>

</div>

## Video Demonstration

<!-- Replace the video below with a relevant vehicle dynamics demo. -->

<div style="display:grid; grid-template-columns:repeat(2,minmax(0,1fr)); gap:20px 24px; width:100%;">

  <!-- Video 1 -->
  <div style="min-width:0; margin:0; padding:0; display:flex; flex-direction:column;">
    <video controls playsinline preload="metadata"
           style="width:100%; aspect-ratio:16/9; height:auto; display:block; margin:0; padding:0;">
      <source src="{{ '/files/videos/Circle_First.mp4' | relative_url }}" type="video/mp4">
    </video>
    <div style="margin:0 !important; padding:0 !important; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.3;">
      Fixed Circle Test
    </div>
  </div>

  <!-- Video 3 -->
  <div style="min-width:0; margin:0; padding:0; display:flex; flex-direction:column;">
    <video controls playsinline preload="metadata"
           style="width:100%; aspect-ratio:16/9; height:auto; display:block; margin:0; padding:0;">
      <source src="{{ '/files/videos/doublelines_Third.mp4' | relative_url }}" type="video/mp4">
    </video>
    <div style="margin:0 !important; padding:0 !important; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.3;">
      Double Lane Change Test
    </div>
  </div>

  <!-- Video 4 -->
  <div style="min-width:0; margin:0; padding:0; display:flex; flex-direction:column;">
    <video controls playsinline preload="metadata"
           style="width:100%; aspect-ratio:16/9; height:auto; display:block; margin:0; padding:0;">
      <source src="{{ '/files/videos/Rolling_First.mp4' | relative_url }}" type="video/mp4">
    </video>
    <div style="margin:0 !important; padding:0 !important; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.3;">
      Slalom Test
    </div>
  </div>

  <!-- Video 5 -->
  <div style="min-width:0; margin:0; padding:0; display:flex; flex-direction:column;">
    <video controls playsinline preload="metadata"
           style="width:100%; aspect-ratio:16/9; height:auto; display:block; margin:0; padding:0;">
      <source src="{{ '/files/videos/Rolling_Third.mp4' | relative_url }}" type="video/mp4">
    </video>
    <div style="margin:0 !important; padding:0 !important; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.3;">
      Circular Driving Test
    </div>
  </div> 

</div>


<!--## Related Publications

- Add relevant publications and research project links here.-->

[← Back to Research]({{ '/research/' | relative_url }})

