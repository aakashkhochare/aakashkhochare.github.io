---
title: "A Scalable Platform for Distributed Object Tracking Across a Many-Camera Network"
collection: publications
permalink: /publication/TPDS-ANV
excerpt: 'Advances in deep neural networks (DNN) and computer vision (CV) algorithms have made it feasible to extract meaningful insights from large-scale deployments of urban cameras. Tracking an object of interest across the camera network in near real-time is a canonical problem.'
date:  2021-01-05
venue: 'IEEE Transactions on Parallel and Distributed Systems'
paperurl: ''
---
Advances in deep neural networks (DNN) and computer vision (CV) algorithms have made it feasible to extract meaningful insights from large-scale deployments of urban cameras. Tracking an object of interest across the camera network in near real-time is a canonical problem. However, current tracking platforms have two key limitations: 1) They are monolithic, proprietary and lack the ability to rapidly incorporate sophisticated tracking models, and 2) They are less responsive to dynamism across wide-area computing resources that include edge, fog, and cloud abstractions. We address these gaps using Anveshak, a runtime platform for composing and coordinating distributed tracking applications. It provides a domain-specific dataflow programming model to intuitively compose a tracking application, supporting contemporary CV advances like query fusion and re-identification, and enabling dynamic scoping of the camera network's search space to avoid wasted computation. We also offer tunable batching and data-dropping strategies for dataflow blocks deployed on distributed resources to respond to network and compute variability. These balance the tracking accuracy, its real-time performance, and the active camera-set size. We illustrate the concise expressiveness of the programming model for four tracking applications. Our detailed experiments for a network of 1000 camera-feeds on modest resources exhibit the tunable scalability, performance, and quality trade-offs enabled by our dynamic tracking, batching, and dropping strategies.

