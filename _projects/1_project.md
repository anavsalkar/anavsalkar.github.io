---
layout: page
title: Data-Driven Risk-sensitive MPC for Multi-agent Systems
description: I worked on this project with Prof. Ashish Hota, for my Bachelors and Masters thesis. I developed a data-driven optimization-based controller (MPC) to constrain the risk associated with the motion plans for multi-agent systems.
img: assets/img/thesis_bg.png
importance: 1
category: 
# github: https://github.com/anavsalkar/cvar_dist_mpc
---
<h1 align="center">
Data-Driven Risk-sensitive MPC for <br /> Multi-agent Systems
</h1>

<br />

    This project was awarded "Most Innovative Project" in Student Innovation Grant Program.
    

**Preprint of this work is available [here](https://arxiv.org/pdf/2209.07793.pdf).** <br>
**Parts of this work were submitted as [Bachelors](/assets/pdf/web-btp.pdf) thesis and ongoing [Masters](/assets/pdf/web-mtp-I.pdf) thesis (part I) at IIT Kharagpur.**

<p align="justify">
<!-- <b><b>Abstract</b></b>:  -->
Safe navigation is a fundamental challenge in multi-robot systems due to the uncertainty surrounding the future trajectory of the robots that act as obstacles for each other. In this work, I propose a principled <b><b>data-driven</b></b> approach based on receding horizon optimization subject to collision avoidance constraints formulated as distributionally robust <b><b>conditional value-at-risk (CVaR)</b></b> of the distance between the agent and a polyhedral obstacle geometry. CVaR-based constraints capture the uncertainty against errors in the predictions of surrounding objects providing user the ability to dictate the risk-appetite. Additionally, tractable finite-dimensional approximations of this class of constraints are derived for <b><b>Wasserstein distributionally robust optimization</b></b> problems for low sample size. The effectiveness of the proposed approach is illustrated in a multi-drone navigation setting implemented in Gazebo platform.
</p>

Three key features of the project are:

**Handling Uncertainty**:  Risk-sensitive behaviour of the agent depends on how the uncertainty in handled by the MPC. Based on predictions of other agents and collected state data, I developed techniques to formulate the data-driven risk constraints for collision avoidance under uncertainty.

<div class="row" align="center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/icra_alpha.gif" title="changing alpha" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="row" align="center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/icra_noise.gif" title="changing noise" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<br />

**Collision Avoidance for Polyhedral Obstacles**: . I represent the surrounding in term of 3D polyhedrons to formulate collision avoidance constraints. This is more accurate representation, instead of circular or spherical assumption prevalent in prior works.


<div class="row" align="center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/icra_obs_rep.png" title="obstacle representation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<br />

**Distributed Computation**: A single centralized problem has a large size and is computationally infeasible for real-time deployment. Therefore, I present a distributed approach that effectively exploits the parallel computation and inter-agent communication.

<div class="row" align="center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/icra_gazebo.gif" title="gazebo simulations" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/icra_rpi.png" title="rpi implementation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>










