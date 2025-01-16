---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

- **Personalized Top-K Set Queries Over Predicted Scores**  
  *VLDB Conference, Dec 2024 (Under Review)*  
  This work studies the applicability of expensive external oracles such as large language models in answering top-$k$ queries over predicted scores. Such scores are incurred by user-defined functions to answer personalized queries over multi-modal data. We propose a generic computational framework that handles arbitrary set-based scoring functions, as long as the functions could be decomposed into constructs, each of which sent to an oracle (in our case an LLM) to predict partial scores. At a given point in time, the framework assumes a set of responses and their partial predicted scores, and it maintains a collection of possible sets that are likely to be the true top-$k$. Since calling oracles is costly, our framework judiciously identifies the next construct, i.e., the next best question to ask the oracle so as to maximize the likelihood of identifying the true top-$k$. We present a principled probabilistic model that quantifies that likelihood. We study efficiency opportunities in designing algorithms. We run an evaluation with three large scale datasets, scoring functions, and baselines.  Experiments indicate the efficacy of our framework, as it achieves an order of magnitude improvement over baselines in requiring LLM calls while ensuring result accuracy. Scalability experiments further indicate that our framework could be used in large-scale applications.

- **X-ray Image Enhancement using G-CLAHE**  
  *IJPRAI, June 2024*  
  In the field of medical imaging, accurate diagnosis heavily relies on effective image enhancement tech- niques, particularly for X-ray images. Existing methods often suffer from various challenges in enhancing such images. These methods either must sacrifice global image characteristics over local image charac- teristics or vice versa. This study introduces a novel approach, called G-CLAHE (Global Contrast-Limited Adaptive Histogram Equalization), that perfectly suits medical imaging, with a focus on X-rays. Conceptu- ally, this novel method adapts both Global Histogram Equalization (GHE) and Limited Adaptive Histogram Equalization (CLAHE) to preserve both local and global image characteristics after enhancement. G- CLAHE demonstrates significant improvements over current state-of-the-art algorithms, effectively ad- dressing their limitations and enhancing the quality of X-ray images for enhanced diagnostic accuracy.

- **Model Reusability in Reinforcement Learning**  
  *VLDB Journal, June 2024 (Under Revision)*  
  The ability to reuse trained models in Reinforcement Learning (RL) holds substantial practical value in particular for complex tasks. While model reusability is widely studied for supervised models in data management, to the best of our knowledge, this is the first ever principled study that is proposed for RL. To capture trained policies, we develop a framework based on an expressive and lossless graph data model that accommodates Temporal Difference Learning (TDL) and Deep-RL based RL algorithms. Our framework is able to capture arbitrary reward functions that can be composed at inference time. The framework comes with theoretical guarantees and shows that it yields the same result as policies trained from scratch.
  We design a parameterized algorithm that strikes a balance between efficiency and quality wrt cumulative reward. Our experiments with two common RL tasks (query refinement and robot movement) corroborate our theory and show the effectiveness and efficiency of our algorithms.


- **Edge Landmarks for Answering Lower Bound Distance Queries**  
  *KDD 2024 (Submitted)*  
  Given a metric space graph 𝐺 (𝑉 , 𝐸) with 𝑚 edges that have their distances known and the remaining edge distances being unknown, we study the problem of answering lower bound distance queries over the unknown edges, when no blackbox function (distance oracle) is available to return any additional distances. Given one of the unknown edge between a pair of objects as a query, the lower bound of distance denotes the minimum possible distance between that pair of objects while satisfying all other constraints. Such lower bound computations stand to benefit a variety of proximity problems considering data coming from compelling application do- mains. We propose a suite of algorithmic techniques with provable guarantees that trade-off between pre-processing time query processing time and quality, as long as the distances satisfy the metric property (in particular, triangular inequality). Our work advances the state-of-the-art solutions both analytically and empirically that we demonstrate by conducting exhaustive experimentation using multiple large scale real world datasets.
