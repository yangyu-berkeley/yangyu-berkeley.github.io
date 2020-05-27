---
title: "Optimal Control Via Neural Network: A Convex Approach"
excerpt: "Deep neural networks have proven to be successful in many identification tasks, however, from the model-based control perspective, these networks are difficult to work with because they are typically non-linear and non-convex. In this work, we bridge the gap between model accuracy and control tractability faced by neural networks, by explicitly constructing input convex neural networks (ICNN). It leads to significant energy savings for building HVAC management. "
collection: research
---
<p>&nbsp;</p>

Control of complex systems involves both system identification and controller design. Deep neural networks have proven to be successful in many identification tasks, however, from model-based control perspective, these networks are difficult to work with because they are typically non-linear and non-convex. Therefore many systems are still identified and controlled based on simple linear models despite their poor representation capability. In this work, we bridge the gap between model accuracy and control tractability faced by neural networks, by explicitly constructing networks that are convex with respect to their inputs. 
<p align="center">
	<img src='/images/research/architecture.png'>
</p>
We show that these input convex networks can be trained to obtain accurate models of complex physical systems. In particular, we design input convex recurrent neural networks to capture temporal behavior of dynamical systems. Then optimal controllers can be achieved via solving a convex model predictive control problem. Experiment results demonstrate the good potential of the proposed input convex neural network based approach in a variety of control applications. In particular we show that in the MuJoCo locomotion tasks [1], we could achieve over 10\percent higher performance using 5× less time compared with state-of-the-art model-based reinforcement learning method; and in the building HVAC control [2] example, our method achieved up to 20\percent energy reduction compared with classic linear models.

## References:

[1] Yize Chen\*, Yuanyuan Shi\*, and Baosen Zhang, ["Optimal Control Via Neural Networks: A Convex Approach''](https://openreview.net/forum?id=H1MW72AcK7), International Conference on Learning Representations (ICLR), 2019.  (*equal contribution). [[PDF]](https://arxiv.org/pdf/1805.11835.pdf) [[Code]](https://github.com/chennnnnyize/Optimal-Control-via-Neural-Networks)

[2] Yize Chen, Yuanyuan Shi, and Baosen Zhang. ["Modeling and Optimization of Complex Building Energy Systems with Deep Neural Networks''](https://arxiv.org/abs/1711.02278), Asilomar Conference, 2017. [[PDF]](https://arxiv.org/pdf/1711.02278.pdf)
