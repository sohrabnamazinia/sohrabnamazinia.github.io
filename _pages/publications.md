---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

- **Personalized Recommendation using LLMs and Human-in-the-loop**  
  *In Progress*  
  Personalized recommendations play a crucial role in enhancing user experience across a plethora of existing and emerging data science applications. Large Language Models (LLMs) are particularly effective due to their ability to handle multi-modal data (e.g., text, images, videos). In this work, I propose to discuss a generic computational framework that allows personalized recom- mendations to an end user with the goal of learning user’s preference over the feature space to rank and recommend items to them. LLMs are used to score feature values of the items from multi-modal data. Specifically, given n items and m features, the core problem is to learn a complete preference order of a user over the feature space, which will entail a personalized ranking over the items. The user is involved sporadically and judiciously in the loop as they are asked a few questions. A question involves showing human a pair (e.g. image or review related to two different items) and asking to identify which one they would prefer more. The novelty of the framework lies in its ability to handle multiple ranking functions with the goal of identifying fewest number of questions to be asked to the user, such that a full preference order over the feature space could be inferred. In this work, I will do a technical deep dive of the framework with popular ranking functions (including Maximal marginal relevance or MMR) and demonstrate its effectiveness through empirical evaluations.

- **X-ray Image Enhancement using G-CLAHE**  
  *IJPRAI, June 2024*  
  In the field of medical imaging, accurate diagnosis heavily relies on effective image enhancement tech- niques, particularly for X-ray images. Existing methods often suffer from various challenges in enhancing such images. These methods either must sacrifice global image characteristics over local image charac- teristics or vice versa. This study introduces a novel approach, called G-CLAHE (Global Contrast-Limited Adaptive Histogram Equalization), that perfectly suits medical imaging, with a focus on X-rays. Conceptu- ally, this novel method adapts both Global Histogram Equalization (GHE) and Limited Adaptive Histogram Equalization (CLAHE) to preserve both local and global image characteristics after enhancement. G- CLAHE demonstrates significant improvements over current state-of-the-art algorithms, effectively ad- dressing their limitations and enhancing the quality of X-ray images for enhanced diagnostic accuracy.

- **Efficient Policy Reusability in Reinforcement Learning**  
  *PVLDBv17, May 2024 (Submitted)*  
  We investigate the reusability of pre-trained policies in Reinforcement Learning (RL). This goal holds sub- stantial practical value, opening avenues for further efficiency and resource optimization. The core ques- tion is how to use pre-trained policies for a given task. We develop a framework based on an expressive and lossless graph data model. Our framework extends to Temporal Difference Learning (TDL) and Deep- RL based RL algorithms and to any number of arbitrary reward functions. The framework comes with theoretical guarantees and shows that it yields the same result as policies trained from scratch. We also design a parameterized algorithm that strikes a balance between efficiency and quality. We run exten- sive experiments with two common RL tasks (query refinement and robot movement) that corroborate our theory and show the effectiveness and efficiency of our algorithms.


- **Edge Landmarks for Answering Lower Bound Distance Queries**  
  *KDD 2024 (Submitted)*  
  Given a metric space graph G(V, E) with m edges that have their distances known and the remaining edge distances being unknown, we study the problem of answering lower bound distance queries. Given one of the unknown edge between a pair of objects as a query, the lower bound of distance denotes the minimum possible distance between that pair of objects while satisfying all other constraints. Such lower bound computations stand to benefit a variety of proximity problems considering data coming from compelling application domains. We design an Oracle to answer lower bound distance queries given a pre-computed arbitrary set of distances, and propose a suite of algorithmic techniques with provable guarantees that trade-off between pre-processing time, storage cost, and query processing time, as long as the distances satisfy the metric property (in particular, triangular inequality). We are the first to design solutions to answer lower bound queries considering pre-processing time, storage cost, and query processing time. Our work advances the state-of-the-art solutions both analytically and empirically that we demonstrate by conducting exhaustive experimentation using multiple large scale real world datasets.
