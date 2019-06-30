---
permalink: /
title: "Computer Science Researcher, with interests in Distributed Systems"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am currently pursuing my PhD at the [DREAM Lab](http://dream-lab.cds.iisc.ac.in) in the [Department of Computational and Data Sciences](http://cds.iisc.ac.in/) at the [Indian Institute of Science](https://iisc.ac.in/). 

Broadly, my research revolves around distributed video analytics for Smart Cities and Internet of Things. Video streams from surveillance cameras deployed across a smart city can be used to track Objects of Interest such as emergency vehicles or missing people in real time. My work involves addressing system-side challenges involved in distributed wide area tracking.
Existing surveillance systems are *proprietary and monolithic*; they lack the composability required to keep pace with the rapid advancements in Deep Learning. They also lack approaches to mitigate the high computational requirement of Deep Neural networks.
We have designed Anveshak, a programming model that captures the building blocks of object tracking to facilitate composability. We have also deigned heuristics based batching and data dropping logic that is guided by a user defined max latency. This allows Anveshak to process only those events that can meet the requested latency and avoid wasting compute.
We have scaled Anveshak to *1000* cameras on 10, 8 core VMs which is a *25x* improvement over the baseline.


*The DREAM:Lab team, led by me, wins the IEEE TCSC SCALE Challenge 2019. [Read more](http://dream-lab.cds.iisc.ac.in/scale-2019/)*
