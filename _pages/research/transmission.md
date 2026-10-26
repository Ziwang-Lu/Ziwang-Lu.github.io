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

<div style="display:flex; gap:24px; width:100%; align-items:flex-start;">

  <figure style="flex:1; min-width:0; margin:0; display:flex; flex-direction:column;">

    <div style="width:100%; height:300px; display:flex; align-items:center; justify-content:center;">
      <img src="{{ '/images/research/Transmission_testbench.jpg' | relative_url }}"
           alt="Experimental Platform for Transmission Control"
           style="width:100%; height:100%; object-fit:contain; display:block;">
    </div>

    <figcaption style="width:100%; box-sizing:border-box; margin:0px 0 0; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.5;">
      Test Bench
    </figcaption>

  </figure>

  <figure style="flex:1; min-width:0; margin:0; display:flex; flex-direction:column;">

    <div style="width:100%; height:300px; display:flex; align-items:center; justify-content:center;">
      <img src="{{ '/images/research/RealVehicle_final.png' | relative_url }}"
           alt="Real Vehicle"
           style="width:100%; height:100%; object-fit:contain; display:block;">
    </div>

    <figcaption style="width:100%; box-sizing:border-box; margin:0px 0 0; text-align:center; font-family:inherit; font-size:0.9em; font-weight:600; line-height:1.5;">
      Real Vehicle
    </figcaption>

  </figure>

</div>





<!--*Experimental platform for powertrain shift control.*-->

<!--## Related Publications

- Add your relevant journal articles here.
- Add links to patents or experimental demonstrations here.-->

[← Back to Research]({{ '/research/' | relative_url }})

