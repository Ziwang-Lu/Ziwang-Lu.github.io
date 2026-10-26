---
layout: single
title: "Transmission Optimization and Control"
permalink: /research/transmission/
author_profile: true
---


## Key Research Topics

### Transmission Parameter Optimization

Investigating the effects of gear ratios, motor characteristics,
and transmission configurations on electric vehicle system efficiency.

### Time-Optimal Gear-Shifting Control

Developing coordinated motor speed synchronization and
angular alignment strategies for synchronizer-free transmissions.

<video controls preload="metadata" width="100%">
  <source src="{{ '/files/videos/shift-control-demo.mp4' | relative_url }}"
          type="video/mp4">
</video>

**Highlighted Contributions**
1. The maximum error of system modeling is less than 2%.
2. Speed and angle are synchronized simultaneously, eliminating shift impacts.
3. Eliminating the neutral-gear waiting time, the gear shifting time is reduced to 210 ms.
4. The gear-shifting time is reduced within 230 ms in the vehicle-start stage, effectively solving the problem of sliding down on the slope.


<!--poster="{{ '/images/research/shift-demo-poster.jpg' | relative_url }}"-->
## Experimental Demonstration

<video controls preload="metadata" width="100%">
  <source src="{{ '/files/videos/shift-control-testbench.mp4' | relative_url }}"
          type="video/mp4">
</video>

## Experimental Platform

<!--<img src="{{ '/images/research/Transmission_testbench.jpg' | relative_url }}"
     alt="Transmission_testbench"
     style="width:50%; max-width:800px;">-->     
<!--<img src="{{ '/images/research/RealVehicle_final.jpg' | relative_url }}"
     alt="RealVehicle_final"
     style="width:50%; max-width:800px;">-->

<div style="display:flex; justify-content:center; align-items:flex-start; gap:24px; flex-wrap:wrap;">

  <figure style="flex:1; min-width:250px; max-width:48%; margin:0;">
    <img src="{{ '/images/research/Transmission_testbench.jpg' | relative_url }}"
         alt="Electric powertrain experimental platform"
         style="width:100%; height:auto; display:block;">
    <figcaption style="text-align:center; margin-top:8px; font-size:0.9em; color:#666;">
      Test Bench
    </figcaption>
  </figure>

  <figure style="flex:1; min-width:250px; max-width:48%; margin:0;">
    <img src="{{ '/images/research/RealVehicle_final.png' | relative_url }}"
         alt="Transmission control experimental setup"
         style="width:100%; height:auto; display:block;">
    <figcaption style="text-align:center; margin-top:8px; font-size:0.9em; color:#666;">
      Real Vehicle
    </figcaption>
  </figure>

</div>


<!--*Experimental platform for powertrain shift control.*-->

<!--## Related Publications

- Add your relevant journal articles here.
- Add links to patents or experimental demonstrations here.-->

[← Back to Research]({{ '/research/' | relative_url }})

