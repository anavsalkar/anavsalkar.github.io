---
layout: page
title: Revolute Robotics 
description: Revolute Robotics is a US-based startup working on hybrid rolling-flying robots for inspection and surviellance in complex environments. As a part-time Controls Engineer, I developed controllers for rolling on uneven terrains and autopilot software for aerial-terrestrial mobility. 
img: assets/img/rr-mars.png
importance: 3
category: 
---
<h1 align="center">
Controls @ <a href="https://www.revoluterobotics.com/">Revolute Robotics</a>
</h1>

<br />
<p align="justify">
Flying robots are incrasingly used for their high manoeuvrability and accessibility to difficult areas, but they falter in terms of flight time and are extrememly sensitve to collisions. The hybrid spherical robot consists of a multi-rotor aerial robot connected to a rolling spherical cage on the outside via gyroscopic gimbal. It saves energy by rolling on ground, while switching to aerial mode to overcome any obstacles. This has great applications such as exploration, mapping, search and rescue, monitoring in subterranean environments and agricultural fields. We were mentored by <a href="https://aliagha.site/">Dr. Ali Agha</a>, Research Technologist at NASA, JPL. 
</p>

<br />

### My Contributions

**Trajectory Tracking for Spherical Robot**: While controllers for multirotors have matured and widely available, my task was to develop controller for spherical rolling robots, based on a multirotor for traversing uneven terrains. The current literature on trajectory control of spherical rolling robots is limited to flat surfaces with no or minimal gradient. Leveraging on attitude control of the thrust by the multirotor, I designed a controller for stable performance even for high slopes with accurate trajectory tracking.  

<div class="row" align="center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/rr-diff_terrain.gif" title="uneven terrain in Gazebo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/rr-terrain_graph.png" title="tracking" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<iframe width="750" height="400" src="https://www.youtube.com/embed/sTh8RsQv6h0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br />

**Autopilot Software**: There exist multiple modes such as rolling, flying, takeoff, land, stablise for the hybrid robot. For this purpose, I develped a finite-state machine autopilot software for smooth transitions between various modes which can interface with high-level commands by human operator. This is also currently being used in testing physical prototype.    



<div class="row" align="center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/rr-hybrid.gif" title="hybrid trajectories" class="img-fluid rounded z-depth-1" %}
    </div>
</div>