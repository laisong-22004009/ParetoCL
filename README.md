# ParetoCL

Official PyTorch implementation of "Pareto Continual Learning: Preference-Conditioned Learning and Adaption for Dynamic Stability-Plasticity Trade-off" [AAAI 2025]

<details>
  <summary>
  <font size="+1">Abstract</font>
  </summary>
Continual learning aims to learn multiple tasks sequentially. A key challenge in continual learning is balancing between two objectives: retaining knowledge from old tasks (stability) and adapting to new tasks (plasticity). Experience replay methods, which store and replay past data alongside new data, have become a widely adopted approach to mitigate catastrophic forgetting. However, these methods neglect the dynamic nature of the stability-plasticity trade-off and aim to find a fixed and unchanging balance, resulting in suboptimal adaptation during training and inference. In this paper, we propose Pareto Continual Learning (ParetoCL), a novel framework that reformulates the stability-plasticity trade-off in continual learning as a multi-objective optimization (MOO) problem. ParetoCL introduces a preference-conditioned model to efficiently learn a set of Pareto optimal solutions representing different trade-offs and enables dynamic adaptation during inference. From a generalization perspective, ParetoCL can be seen as an objective augmentation approach that learns from different objective combinations of stability and plasticity. Extensive experiments across multiple datasets and settings demonstrate that ParetoCL outperforms state-of-the-art methods and adapts to diverse continual learning scenarios. 
</details>


## Introduction
In this paper, we propose a simple yet efficient hypernet-based continual learning model.

The overview of the proposed Pareto Continual Learning.
<div align="center">
  <img src="resources/Overview.png" width=80%/>
  " width=80%/>
</div>