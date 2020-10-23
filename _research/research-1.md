---
title: "Bring Energy Storage (ES) and Renewable Energy (RE) to the Grid via Market Design"
excerpt: "Energy storage (ES) is one of the critical technologies to enable energy system transition, especially the integration of the renewable generation. Whereas the high capital cost defers its penetration into energy system. The justification of the ES capital cost relies on well-designed ES business models that can harness the maximum value for the stakeholders involved. "
collection: research
---
<p>&nbsp;</p>

Energy storage (ES) is one of the critical technologies to enable energy system transition, especially the integration of the renewable generation. Whereas the high capital cost defers its penetration into energy system. The justification of the ES capital cost relies on well-designed ES business models that can harness the maximum value for the stakeholders involved. 

The prosperity of sharing economy suggests its capability to bring capital-intensive ES resources to energy system through sharing. There are generally two sharing paradigms: i) multiple users cooperatively to invest and use a common-owned ES; ii) An energy storage operator (ESO) invests blocks of ES to gain profit by providing energy storage service to its consumers. However, the successful exertion relies on an appropriate market mechanism that can "allocate" the payoff among the different stakeholders involved, which is challenging due to multi-step operation pattern of the ES resource.

<p align="center">
	<img src='/images/research/game.png'>
</p>
To ground this question, we looked at the interaction of learning agents in Cournot competition. A Cournot game is the underlying market model for many demand response programs in energy markets, where providers bid their available quantity, the service price is then set by the total supply, and each provider gets paid accordingly. Players in the game are self-interested and aim to maximize their own payoffs by strategically choosing the bidding quantity. In this work, we attempted to analyze the long-run outcome of dynamic learning agents in a Cournot game. Since each agent receives very limited feedback (just the cleared price and nothing else about the system), it was an open problem to even establish if the learning dynamics would converge at all. 

Notably, we proved the convergence of two widely used classes of machine learning algorithms: no-regret algorithms and policy gradient, to the Nash Equilibrium in concave Cournot games. In addition, we showed that exploiting the structure of the game can accelerate the convergence of learning, where policy gradient converges exponentially and no-regret converges sub-linearly.

## Reference:

[1] Yuanyuan Shi, Baosen Zhang, ["Learning in Cournot Games with Limited Information Feedback''](https://arxiv.org/abs/1906.06612), arXiv Preprint. 
