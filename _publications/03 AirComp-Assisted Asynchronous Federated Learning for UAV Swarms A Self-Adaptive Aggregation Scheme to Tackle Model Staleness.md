---
title: "AirComp-Assisted Asynchronous Federated Learning for UAV Swarms: A Self-Adaptive Aggregation Scheme to Tackle Model Staleness"
collection: publications
permalink: /publication/Model_staleness
excerpt: 'This paper has been submitted to the IEEE Transactions on Wireless Communications and is presently undergoing peer review.'
venue: 'IEEE Transactions on Wireless Communications'
# date: 6 November 2024
paperurl: '../assets/publications/AirComp-Assisted.pdf'
# date: 2024-02-17
# venue: 'GitHub Journal of Bugs'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---
Federated learning (FL) is a promising paradigm for collaborative intelligence in the low-altitude economy, enabling unmanned aerial vehicle (UAV) swarms to perform deep learning tasks (e.g., logistics, emergency rescue) while preserving data sovereignty. However, limited communication channels and heterogeneous computation capabilities among UAVs cause significant FL aggregation delays. To reduce convergence time, we propose an asynchronous FL (AFL) framework for UAV swarms, which integrates over-the-air computation (AirComp) to improve communication efficiency via simultaneous transmission. To address signal distortion in AirComp, we formulate an objective function and solve it using an aggregation scheduling algorithm, which transforms the nonconvex problem into two convex subproblems tackled via alternating optimization, to derive optimal aggregation strategies and beamforming vectors. Moreover, to mitigate model staleness in AFL, which causes gradient divergence and slow convergence, we propose a self-adaptive aggregation scheme with staleness awareness, enabling UAVs to adjust local models autonomously without requiring information from other UAVs. Simulation results show that our scheme reduces staleness impact and leverages stale parameters, helping AFL outperform synchronous FL in convergence speed and accuracy. Overall, our study presents an effective AFL framework, a fast aggregation scheduling algorithm, and a self-adaptive aggregation scheme for UAV swarms, accelerating global model convergence while reducing energy expenditure.