---
title: "Dynamic Scaling of Video Analytics for Wide-area Tracking in Urban Spaces"
collection: publications
permalink: /publication/SCALE-ANV
excerpt: 'We design and develop an analytics platform that allows easy composability of these neural networks to solve the problem of wide-area tracking. The platform solves multiple system side challenges that would otherwise hamper or complicate the development of such applications.'
date:  2019-05-15
venue: 'SCALE Challenge 2019, co-hosted with CCGRID'
paperurl: ''
---
Smart City deployments typically have thousands to even hundreds of thousands of Surveillance cameras. Rapid advancements in computer vision techniques due to Deep Neural Networks enable using these camera feeds for performing non-trivial analytics. Tracking a moving object of interest using a large network of cameras, also known as object reidentification, is one such analytic that empowers city administration with capabilities such as finding missing people or prioritizing emergency vehicles. We have built Anveshak, a framework for distributed wide-area tracking. Anveshak fills in the shortcomings of existing Big Data and Deep Learning frameworks by -- exposing an intuitive and composable programming model; automating application deployment and orchestration across edge, fog, and cloud resources and providing knobs to the user for managing the application performance. The knobs lend the application the ability to scale potentially to thousands of cameras. In this proposal we have designed two representative applications; missing person tracking and priority signalling for emergency vehicles.
	We empirically verify that the application scales to 1000 cameras on a Cloud-only deployment of 10 Azure VMs with 8 cores and 32GB RAM each. Alternatively, it scales to 500 cameras on a simulated setup of 100 edge, 30 fog, and 1 Cloud VM. We also highlight the effect of the knobs on the application performance.


