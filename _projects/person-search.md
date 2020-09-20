---
title: "Reinforcement Learning for Person Search"
collection: projects
permalink: /projects/person-search
excerpt: "Online search, Detection and re-identification, Q-learning.<br/> <br/> <br/>"
date: 2017-01-01
venue: 
paperurl: 
citation:
teaser: 'person-search'
---
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Joint top-down search of a specific instance of a class which is under interaction with other instances, e.g. person of interest conversing with another prson, often leads to inaccurate detection. To solve this problem, in this task, deep reinforcement learning is used to localize the person in an image by changing the bounding box position and dimension. This leads to the the agent Locating a person in an image using natural language description and epsilon-greedily updating the bounding box dimensions based on Intersection over Union (IoU). Initially, the bounding box is randomly initialized and at each action its position and dimensions are changed. Once the agent believes that the bounding box is covering the person, the agent will trigger as shown below.
<br/>
<div align="center"><img src="/images/projects/person-search-1.png" alt="person-search-1" width="325"> &nbsp; &nbsp; &nbsp; <img src="/images/projects/person-search-2.png" alt="person-search-2" width="285"> </div>