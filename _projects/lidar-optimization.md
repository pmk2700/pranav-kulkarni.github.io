---
title: "Min-max Optimization of a LiDAR Sensor"
collection: projects
permalink: /projects/lidar-optimization
excerpt: "CARLA simulator, Weighted convex optimization, Object detection.<br/> <br/> <br/>"
date: 2017-02-01
venue: 
paperurl: 
citation:
teaser: 'lidar-optimization'
---
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A LiDAR provides accurate 3D views and precise distance measurements under uncertain driving conditions. However, its implementation remains costly. To tackle this issue an effort to maximize the utility of the LiDAR is made. Since, at a high-level, the task of a LiDAR is to detect objects, an easy-to-evaluate cost function which minimizes the maximally undetected subspace is used. Different LiDAR configurations in the CARLA simulator are used and for each, depth camera images are converted to LiDAR point clouds since CARLA’s LiDARs are not accurate. The perception area is used to construct a design procedure to solve the optimization problem described above based on weighted region of interests around the vehicle. The weighted regions are obtained when a subspace cuts a cube and the cube's weight is incremented by 1. Now, the task becomes to maximize for all LiDAR configurations and find the optimum for a particular number of LiDARs.
<br/>
<div align="center"><img src="/images/projects/lidar-optimization-1.png" alt="lidar-optimization-1" width="325"> &nbsp; &nbsp; &nbsp; <img src="/images/projects/lidar-optimization-2.png" alt="lidar-optimization-2" width="285"> </div>