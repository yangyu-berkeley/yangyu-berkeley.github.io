---
title: "Optimal Battery Control Under Cycle Aging Mechanisms"
excerpt: "Energy storage offsets renewable fluctuation and is the key to a low-carbon future, but managing these assets at the system level is challenging. A central question is to understand the degradation of storage and reflect this cost in the operations. In this work, we prove that the cycle-based electrochemical degradation model is convex. Based on this cost model, we further develop an optimal online control algorithm for energy storage in a general pay-for-performance market via a novel change of basis. "
collection: research
---
<p>&nbsp;</p>

Energy storage offsets renewable fluctuation and is the key to a low-carbon future, but managing these assets at the system level remains an open question. A central challenge is to understand the degradation of storage and reflect this cost in the storage operations.

Faithful electrochemical degradation models have always been thought of as impractical to use in real-time due to their complexity. In this work [1], we showed that this cost is convex resolving this long-standing algorithmic challenge of supposed impracticality in an elegant fashion. Based on this cost model, we further developed an optimal online control algorithm [2] for energy storage in a general “pay-for-performance” market, e.g. providing frequency regulation services and supporting renewable integration. 
<p align="center">
	<img src='/images/research/battery_controller.png'>
</p>
Real-time control is the cornerstone of all energy storage operations, yet it is seldom addressed due to the complex nature of real-time decision making and the inter-temporal constraints on storage capacity and electrochemical degradation. Surprisingly, we found that including the physics of storage can greatly simplify this problem and yield closed-form optimal solutions that were thought to be unobtainable. Based on a novel change of basis, we derived a simple online control policy [2, 3] and a optimal capacity bidding algorithm [4] that minimizes the operational cost of storage (with time-invariant regret) including the dispatch violation cost and the cost of battery degradation. These algorithms are currently being implemented by Doosan Gridtech in the PJM market.

## References:

[1]. Yuanyuan Shi, Bolun Xu, Yushi Tan, and Baosen Zhang, ["A convex cycle-based degradation model for battery energy storage planning and operation''](https://ieeexplore.ieee.org/document/8431814), American Control Conference (ACC), 2018  [[PDF]](https://arxiv.org/pdf/1703.07968.pdf)

[2]. Yuanyuan Shi, Bolun Xu, Yushi Tan, Daniel Kirschen, and Baosen Zhang, ["Optimal Battery Control Under Cycle Aging Mechanisms in Pay for Performance Settings''](https://ieeexplore.ieee.org/abstract/document/8449100), IEEE Transactions on Automatic Control, 2019. [[PDF]](https://arxiv.org/pdf/1709.05715.pdf) [[Code]](https://drive.google.com/file/d/1LNoaSbdMlIJ5RucSjCLRBmrBmqaQ0jfS/view?usp=sharing)

[3]. Bolun Xu, Yuanyuan Shi, Daniel Kirschen, and Baosen Zhang, ["Optimal regulation response of batteries under cycle aging mechanisms”](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8263750), IEEE Conference on Decision and Control (CDC), 2017  [[PDF]](https://arxiv.org/pdf/1703.07824.pdf)

[4]. Bolun Xu, Yuanyuan Shi, Daniel Kirschen, and Baosen Zhang, ["Optimal Battery Participation in Frequency Regulation Markets"](https://ieeexplore.ieee.org/document/8383984), IEEE Transactions on Power Systems, 2018. [[PDF]](https://arxiv.org/pdf/1710.10514.pdf) [[Code]](https://drive.google.com/file/d/1NS_dURp4K211zeNiInDYId97VMNwDry1/view?usp=sharing)
