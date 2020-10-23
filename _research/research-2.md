---
title: "Adaptive and Scalable Control of Buildings' HVAC System"
excerpt: "Buildings, especially the heating, ventilation and air-conditioning systems, accounts for a large proportion of energy consumption. How to improve its efficiency is a critical issue, which relies a computationally efficient control method for the operation of HVAC system to improve energy efficiency while providing comfortable indoor environment. "
collection: research
---
<p>&nbsp;</p>

To facilitate energy-efficient buildings, three challenges are required to address regarding the control and optimization of HVAC systems: i) support the uncertain thermal demand of occupants; ii) overcome computational challenge at coordinating zone cooling demand and interactions, especially commercial HVAC system; iii) Lack indoor air quality (IAQ) management. To address such challenges, we have applied reinforcement learning (RL) and decentralized optimization techniques to achieve adaptive and scalable control HVAC systems for saving energy and providing an enhanced indoor environment. 

<p align="center">
	<img src='/images/research/architecture.png'>
</p>
We show that these input convex networks can be trained to obtain accurate models of complex physical systems. In particular, we design input convex recurrent neural networks to capture temporal behavior of dynamical systems. Then optimal controllers can be achieved via solving a convex model predictive control problem. Experiment results demonstrate the good potential of the proposed input convex neural network based approach in a variety of control applications. In particular we show that in the MuJoCo locomotion tasks [1], we could achieve over 10\percent higher performance using 5× less time compared with state-of-the-art model-based reinforcement learning method; and in the building HVAC control [2] example, our method achieved up to 20\percent energy reduction compared with classic linear models.

## References:

[1] Yize Chen\*, Yuanyuan Shi\*, and Baosen Zhang, ["Optimal Control Via Neural Networks: A Convex Approach''](https://openreview.net/forum?id=H1MW72AcK7), International Conference on Learning Representations (ICLR), 2019.  (*equal contribution). [[PDF]](https://arxiv.org/pdf/1805.11835.pdf) [[Code]](https://github.com/chennnnnyize/Optimal-Control-via-Neural-Networks)

[2] Yize Chen, Yuanyuan Shi, and Baosen Zhang. ["Modeling and Optimization of Complex Building Energy Systems with Deep Neural Networks''](https://arxiv.org/abs/1711.02278), Asilomar Conference, 2017. [[PDF]](https://arxiv.org/pdf/1711.02278.pdf)
