---
title: "Data-Driven Robust Reinforcement Learning for Continuous Control"
excerpt: "An issue that is faced by many state-of-the-art Reinforcement Learning (RL) algorithms is the sensitivity (risk) of the learned policy to model uncertainties. In this project, we proposed a data-driven framework for incorporating robustness to the parametric uncertainties into continuous control RL algorithms. "
collection: research
---

We focus on learning Reinforcement Learning (RL) policies that are robust to perturbations in the environment dynamics, which we refer to as model misspecification. Previous works in robust RL learn robust policies by utilizing techniques such as domain randomization and building uncertainty sets for robust optimization [1]. These techniques require access to a simulator as well as the ability to modify the parameters of the simulator. In real-world applications such as robotics, a simulator is often available which can be used for training an RL agent to solve a particular task. However, in many cases, it is non-trivial or even infeasible to modify the configuration parameters of the proprietary/third-party simulator. Even if the modifications can be made, it is unclear whether these modifications accurately represent realistic real-world scenarios. 
<p align="center">
	<img src='/images/research/DDR_MPO.png'>
</p>
To tackle this problem, we propose a new data-driven algorithm for incorporating robustness into RL called Data-Driven Robust Maximum a-posteriori Policy Optimization (DDR-MPO)[2]. This algorithm first learns transition models with datasets collected from different perturbed environments, corresponding to the real-world systems, and then uses these models along with the provided simulator to learn a robust policy. We show that DDR- MPO outperforms MPO in a variety of MuJoCo domains under different perturbed environments. We further present multiple investigative experiments that provide deeper insight into the robustness performance of DDR-MPO.

## References

[1] Daniel J. Mankowitz, Nir Levine, Rae Jeong, Abbas Abdolmaleki, Jost Tobias Springenberg, Yuanyuan Shi, Jackie Kay, Todd Hester, Timothy Mann, Martin Riedmiller, ["Robust Reinforcement Learning for Continuous Control with Model Misspecification''](https://openreview.net/forum?id=HJgC60EtwB), International Conference on Learning Representations (ICLR), 2020. [[PDF]](https://openreview.net/forum?id=HJgC60EtwB)
	
[2] Yuanyuan Shi, Kai Xiao, Daniel J. Mankowitz, Rae Jeong, Nir Levine, Sven Gowal, Timothy Mann, and Todd Hester, ["Data-Driven Robust Reinforcement Learning for Continuous Control''](https://drive.google.com/file/d/0B3mY6u_lryzddkRrQ0xzQWtpemRUSHBnZ2NHMnctS1B5b01J/view), Safety and Robustness in Decision Making Workshop, Neural Information Processing Systems (NeurIPS), 2019. [[PDF]](https://drive.google.com/file/d/0B3mY6u_lryzddkRrQ0xzQWtpemRUSHBnZ2NHMnctS1B5b01J/view) [[Poster]](https://drive.google.com/file/d/1OSd4GnrEluGX_Vwx8HChREavtdTQTCde/view?usp=sharing)