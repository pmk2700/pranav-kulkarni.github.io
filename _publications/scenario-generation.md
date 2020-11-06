---
title: "Multi-Vehicle Interaction Scenarios Generation & Interpretable Traffc Primitives and Gaussian Process Regression"
collection: publications
permalink: /publication/scenario-generation
excerpt: "Wenshuo Wang, Weiyang Zhang, Ding Zhao. International Conference on Robotics and Automation 2020. **[**[arxiv](https://arxiv.org/pdf/1910.03633.pdf)**]** **[**[code](https://github.com/agnihotriakhil/turtlebot3_aruco_control)**]** <br/> <br/> <br/>"
date: 2019-09-01
venue: 'ICRA 2020'
paperurl: 
citation:
teaser: 'scenario-generation'
--- 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Generating multi-vehicle interaction scenarios can benefit motion planning and decision making of autonomous vehicles when on-road data is insufficient. This paper presents an efficient approach to generate varied multi-vehicle interaction scenarios that can both adapt to different road geometries and inherit the key interaction patterns in real-world driving. Towards this end, the available multi-vehicle interaction scenarios are temporally segmented into several interpretable fundamental building blocks, called traffic primitives, via the Bayesian nonparametric learning. Then, the changepoints of traffic primitives are transformed into the desired road to generate collision-free interaction trajectories through a sampling-based path planning algorithm. The Gaussian process regression is finally introduced to control the variance and smoothness of the generated multi-vehicle interaction trajectories. Experiments with simulation results of three typical multi-vehicle trajectories at different road conditions are carried out. The experimental results demonstrate that our proposed method can generate a bunch of human-like multi-vehicle interaction trajectories that can fit different road conditions remaining the key interaction patterns of agents in the provided scenarios, which is import to the development of autonomous vehicles. **[**[arxiv](https://arxiv.org/pdf/1910.03633.pdf)**]** **[**[code](https://github.com/agnihotriakhil/turtlebot3_aruco_control)**]**

<br/>
<div align="center"><img src="/images/publications/scenario-generation-1.png" alt="scenario-generation-1" width="285"> &nbsp; &nbsp; &nbsp; <img src="/images/publications/scenario-generation-2.png" alt="scenario-generation-2" width="285"> </div>