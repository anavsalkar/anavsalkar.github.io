---
layout: page
title: Vector Field Guidance for Fixed-Wing UAVs
description: This work was carried out under Prof. Sikha Hota, IIT Kharagpur. I developed a new time-optimal guidance algorithm for fixed-wing UAVs that could closely match the performance of the discontinuous bang-bang controller. 
img: assets/img/icc-thumbnail.png
importance: 6
category: fun
---

<h1 align="center">
Vector Field Guidance for Fixed-Wing UAVs
</h1>

<br />


**This work was presented at Indian Control Conference 2021:** 
**[Minimum-time Path Convergence for UAVs in Wind Using Vector Field Guidance](https://ieeexplore.ieee.org/document/9703128).**



<p align="justify">
<!-- <b><b>Abstract</b></b>:  -->
This work introduces a novel guidance algorithm for unmanned aircraft to converge to a smooth path optimizing time in the presence of wind. A Lyapunov vector field based method is used to achieve convergence and tracking. The proposed framework performs better in comparison with the similar work existing in literature. The presented approach modifies the vector field according to the velocity of the wind, facilitating faster convergence. A customised optimisation algorithm is then used to find a suitable design parameter for vector fields. To demonstrate the efficacy of the proposed approach, numerical simulations are shown and the results are compared with the optimal time paths obtained using optimal control theory.
</p>
<iframe width="770" height="400" src="https://www.youtube.com/embed/tiW4wwchpHw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />

**Combined Vector Field**: Two vector fields, conservative and solenoidal are combined with appropriate weight functions such that the converging field dominates at larger distances and the tracking field dominates when the UAV is closer to the curve. The weighting parameter is then optimized to ensure fast convergence to desired path.    

<div class="row" align="center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/icc-conservative.png" title="Conservative Field" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/icc-solenoidal.png" title="Solnoidal Field" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/icc-combined.png" title="Combined Field" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<br />

**Time-optimal Convergence in Wind**: Additional modifications are introduced that factor in the windspeed and directions to change the vector field for near-optimal performance compared to discontinuous min-max controller.   


<div class="row" align="center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/icc-quiver.gif" title="Quiver plot" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/icc-stream.gif  " title="Streamline plot" class="img-fluid rounded z-depth-1" %}
    </div>
</div>