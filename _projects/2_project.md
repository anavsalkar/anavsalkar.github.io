---
layout: page
title: Trajectory Planning for Racing Drones
description: This project was carried out under Prof. David Saussié, Polytechnique Montréal during my summer internship. I developed a simulation frameowrk for drone racing and demonstrated trajectory planning and control algorithms on the same.
img: assets/img/mitacs-traj.png
importance: 4
category: 
---
<h1 align="center">
Trajectory Planning for Racing Drones
</h1>

<br />

<!-- <a href="/assets/pdf/mitacs.pdf"> report </a> -->
**Project report can be accessed [here](../../assets/pdf/mitacs.pdf).**
**Code can be accessed on the GitHub [here](https://github.com/anavsalkar/race_drone).**

<p align="justify">
Research in racing drones is gaining popularity mainly due its immense application in agile drone flights. Previous works can be classified into four categories gate detection, localization, trajectory generation and control. In this project, a realistic simulation framework is set up that can be utilized to focus on all four aspects. Commonly used minimum snap trajectory is used, combined with differential flatness-based control or nonlinear model predictive control, to demonstrate the basic drone racing tasks and effectiveness of the simulation framework. 
</p>
<br />

<div class="row" align="center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mitacs-flightmare_ss.png" title="flighmare" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mitacs-gazebo_ss.png" title="gazebo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/mitacs-rviz_ss.png" title="rviz" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

The above figures depict photorealistic graphics from [Flightmare](https://flightmare.readthedocs.io/en/latest/index.html), dynamics simulation by [Gazebo](https://gazebosim.org/) using Robot Operating System (ROS). 

<br />

<iframe width="750" height="400" src="https://www.youtube.com/embed/mKJUHDs2lqE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


