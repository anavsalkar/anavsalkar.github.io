---
layout: page
title: Multi-Objective Planning in Stochastic Ocean Environments
description: This work was carried out under Prof. Deepak Subramani, Indian Institute of Science, Bangalore during my summer internship. I worked on GPU-based algorithm for policies for autonomous agents in highly advective ocean flows.    
img: assets/img/iisc-thumbnail.png
importance: 2
category: 
---

<h1 align="center">
Multi-Objective Planning in Stochastic Ocean Environments
</h1>

<br />


**This work was published in MDPI Journal of Marine Science and Engineering:** 
**[GPU-Accelerated Multi-Objective Optimal Planning in Stochastic Dynamic Environments](https://www.mdpi.com/2077-1312/10/4/533).**

<p align="justify">
<!-- <b><b>Abstract</b></b>:  -->
The importance of autonomous marine vehicles is increasing in a wide range of ocean science and engineering applications. <b><b>Multi-objective optimization</b></b>, where trade-offs between multiple conflicting objectives are achieved (such as minimizing expected mission time, energy consumption, and environmental energy harvesting), is crucial for planning optimal routes in stochastic dynamic ocean environments. This work extends the end-to-end GPU-accelerated single-objective <b><b>Markov Decision Process</b></b> path planner to compute optimal operating curves for multi-objective optimal planning. MDPs with scalarized rewards for multiple objectives are formulated and solved in idealized stochastic dynamic ocean environments with dynamic obstacles. Two simulated mission scenarios are completed to elucidate our approach and capabilities: (i) an agent moving from a start to target by minimizing travel time and net-energy consumption when harvesting solar energy in an uncertain flow; (ii) an agent attempting to cross a shipping channel with uncertain ship movement and flow. Optimal operating curves are computed in a fraction of the time that would be required for existing solvers and algorithms.
</p>

<iframe width="760" height="400" src="https://www.youtube.com/embed/p7DxnQij01Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br />

### Contributions

**Multi-objective Rewards**: Utilizing a finite horizon, undiscounted, total cost MDP, I devised scalarised multi-objective reward function using weighted rewards for energy comsumption and required time. Solar energy harvested from a scalar field can also be accomodated to optimize net consumption. The GPU-accelerated algorithm was implemented on CUDA.    

<div class="row" align="center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iisc-channel.png" title="shipping channel schematic" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iisc-pareto.png" title="time-energy curve" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<br />



**Operating Curve Analysis and Applications**: I analysed the operating curves for various problem parameters, showing several interesting characteristics and agent behaviors. It developed further applications on unknown obstacle positions and busy shipping channel crossing problem.    


<div class="row" align="center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/iisc-huge.png" title="changing parameters" class="img-fluid rounded z-depth-1" %}
    </div>
</div>








