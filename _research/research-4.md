---
title: "Joint Optimization of Energy Storage for Multiple Services"
excerpt: "Existing works on energy storage planning focus on using batteries for a single application. Our results suggest that battery can achieve much larger economic benefits than previously thought if they jointly provide multiple services. "
collection: research
---
<p>&nbsp;</p>

Existing works on energy storage planning focused on using batteries for a single application. In this work, we consider using a battery storage system simultaneously for peak shaving and frequency regulation through a joint optimization framework [1], which captures battery degradation, operational constraints, and uncertainties in customer load and regulation signals. Under this framework, we demonstrate that the saving from joint optimization is often larger than the sum of the optimal savings when the battery is used for the two individual applications. A simple threshold real-time algorithm is proposed and achieves this super-linear gain. 

We quantify this superlinear gain using real-world data from two large commercial users [2]: a Microsoft data center and the University of Washing- ton EE & CSE CSE building. The following plot gives an example daily load profile for both cases and summarizes the annual bill saving.
<p align="center">
	<img src='/images/research/superlinear.png'>
</p>
Compared to prior works that focused on using battery storage systems for single applications, our results suggest that batteries can achieve much larger economic benefits than previously thought if they jointly provide multiple services.

## References

[1] Yuanyuan Shi, Bolun Xu, Baosen Zhang, and Di Wang, ["Leveraging energy storage to optimize data center electricity cost in emerging power markets"](https://arxiv.org/abs/1606.01536), Seventh International Conference on Future Energy Systems, ACM (e-Energy), 2016.  [[PDF]](https://arxiv.org/pdf/1606.01536.pdf)

[2] Yuanyuan Shi, Bolun Xu, Di Wang, and Baosen Zhang, ["Using Battery Storage for Peak Shaving and Frequency Regulation: Joint Optimization for Superlinear Gains''](https://ieeexplore.ieee.org/document/8027056), IEEE Transactions on Power Systems, 2017. [[PDF]](https://arxiv.org/pdf/1702.08065.pdf) [[Code]](https://drive.google.com/file/d/18xUOAi9tDGbPQ9hq5nz9ZvaHVgJzVb4M/view?usp=sharing)



	

