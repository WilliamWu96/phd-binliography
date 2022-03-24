# PhD-bibliography

# Table of contents

* [Generalization](#generalization-dart)
  * [RL Generalization](#rl-generalization)
  * [IL Generalization](#il-generalization)
* [Exploration Strategy](#exploration-strategy)
* [CARLA](#carla)

# Generalization :dart:

## RL generalization

### 2021

* [arXiv 2021] [A Survey of Generalisation in Deep Reinforcement Learning](https://arxiv.org/abs/2111.09794)
* [arXiv 2021] [Generalization of Reinforcement Learning with Policy-Aware Adversarial Data Augmentation](https://arxiv.org/abs/2106.15587)
  <details>
    <summary> Hanping Zhang et al. 
        <em></em> 2021 </summary>
    The generalization gap in reinforcement learning (RL) has been a significant obstacle that prevents the RL agent from learning general skills and adapting to varying environments. Increasing the generalization capacity of the RL systems can significantly improve their performance on real-world working environments. In this work, we propose a novel policy-aware adversarial data augmentation method to augment the standard policy learning method with automatically generated trajectory data. Different from the commonly used observation transformation based data augmentations, our proposed method adversarially generates new trajectory data based on the policy gradient objective and aims to more effectively increase the RL agent's generalization ability with the policy-aware data augmentation. Moreover, we further deploy a mixup step to integrate the original and generated data to enhance the generalization capacity while mitigating the over-deviation of the adversarial data. We conduct experiments on a number of RL tasks to investigate the generalization performance of the proposed method by comparing it with the standard baselines and the state-of-the-art mixreg approach. The results show our method can generalize well with limited training diversity, and achieve the state-of-the-art generalization test performance.
    </details>
    
* [arXiv 2021] [Learning Invariant Representations for Reinforcement Learning without Reconstruction](https://arxiv.org/abs/2006.10742)
  <details>
    <summary> Amy Zhang et al. 
        <em>ICLR</em> 2021 </summary>
    We study how representation learning can accelerate reinforcement learning from rich observations, such as images, without relying either on domain knowledge or pixel-reconstruction. Our goal is to learn representations that both provide for effective downstream control and invariance to task-irrelevant details. Bisimulation metrics quantify behavioral similarity between states in continuous MDPs, which we propose using to learn robust latent representations which encode only the task-relevant information from observations. Our method trains encoders such that distances in latent space equal bisimulation distances in state space. We demonstrate the effectiveness of our method at disregarding task-irrelevant information using modified visual MuJoCo tasks, where the background is replaced with moving distractors and natural videos, while achieving SOTA performance. We also test a first-person highway driving task where our method learns invariance to clouds, weather, and time of day. Finally, we provide generalization results drawn from properties of bisimulation metrics, and links to causal inference.
    </details>

## IL generalization

### 2020

* [arXiv 2021] [Generalization Guarantees for Imitation Learning](https://arxiv.org/pdf/2008.01913)

# Exploration Strategy

A list of papers regarding exploration strategy in (deep) reinforcement learning.

## Exploration Strategy

### 2021

### 2018

* [arXiv 2018] [Exploration by Random Network Distillation](https://arxiv.org/abs/1810.12894)

## Unsupervised Active Pretraining

### 2021

* [arXiv 2021] [Behavior From the Void: Unsupervised Active Pre-Training](https://arxiv.org/abs/2103.04551)

* [arXiv 2021] [APS: Active Pretraining with Successor Features](https://arxiv.org/abs/2108.13956)

* [arXiv 2021] [Reinforcement Learning with Prototypical Representations](https://arxiv.org/abs/2102.11271)

# CARLA

## reinforcement-learning-CARLA

### 2021

* [arXiv 2021] [Multi-Modal Fusion Transformer for End-to-End Autonomous Driving](https://arxiv.org/abs/2104.09224)

* [arXiv 2021] [Learning to drive from a world on rails](https://arxiv.org/pdf/2105.00636)

### 2020
* [PhD thesis 2020] [Safe and Efficient Reinforcement Learning for Behavioural Planning in Autonomous Driving](https://hal.inria.fr/tel-03035705/document)


## imitation-learning-CARLA

### 2022

* [arXiv 2022] [Learning from All Vehicles](https://arxiv.org/pdf/2203.11934)

### 2021

* [arXiv 2021] [Learning by cheating](https://arxiv.org/pdf/1912.12294)

