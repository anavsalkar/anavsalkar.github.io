---
layout: page
title: Aerial Robotics Kharagpur
description: ARK is a student research group at IIT Kharagpur, mentored by Prof. Somesh Kumar. I am a part of the Controls team from my first year where I was introduced to robotics for the first time. Here, I have worked on various independent and colaborative projects. 
img: assets/img/ark-ark_cropped.png
importance: 5
category: 
---
<h1 align="center">
<a href="https://arl-kgp.github.io/">Aerial Robotics Kharagpur</a>
</h1>
<br />
As a member of **Controls** team, I have contribured to various projects mainly on control and path planning algorithms. Some of the projects are listed below.
<br />

### Vaccine delivery using drone
Important operations of search, rescue, medication distribution and incident response which are constrained by human accessibility, can be rapidly improved by aerial robotics. Believing in the same, Aerial Robotics Kharagpur in collaboration with ICMR developed a drone for Vaccine delivery. Mainly focused on delivering vaccines for geographically remote locations inaccessible by road, the drone is capable of reaching speeds up to 15 m/s mid-air and fly for about 50 minutes without payload on a single charge. The drone can easily fly up to a distance of up to 12 km round trip in flat regions and up to 10km in hilly regions. It can deliver a payload as heavy as 5kg. The video shows a test flight conducted in IIT Kharagpur campus on 01-05-2021. In this video, the drone - named "Merlin" - delivered a vaccine container from Mahatma Gandhi Stadium, IIT Kharagpur to Helipad, IIT Kharagpur.

<iframe width="750" height="400" src="https://www.youtube.com/embed/C1ndVA5SE-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br />

### Tilt-rotor quadrotor
I modelled dynamics and aerodynamics on the vectored-thrust quadrotor using Simulink for numerical simulation. Subsequently, a PID controller for decoupled motion of pitch angle control and forward velocity using servo motor was developed. Using in-house 3D printing facilities, we developed a prototype for 5 degree of freedom drone.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ark-simulink.png" title="Simulink Model" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ark-5dof.gif" title="5DoF drone" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<br />

### Crazyflie Nanodrones
We setup a [Crazyflie](https://www.bitcraze.io/products/crazyflie-2-1/) nanodrone setup with local positioning system in the lab. Further, I implemented timed-elastic band and potential field algorithms for obstacle avoidance.  
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ark-pot.gif" title="Obstacle Avoidance" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/ark-formation.gif" title="ARK Formation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>



