---
layout: page
title: Learning-Based Graph Combinatorial Optimization
description: Machine learning and deep reinforcement learning methods for solving graph-based and combinatorial optimization problems.
img: /assets/img/projects/learning_graph_optimization_thumbnail.png
importance: 2
category: research
---

## Overview

This research area develops learning-based methods for solving graph and combinatorial optimization problems. A central theme is the use of graph representation learning and deep reinforcement learning to guide sequential decisions in complex network settings. These methods support problems such as influence maximization, rumor containment, and edge activation in constrained or structured graph environments.

Key themes include:

- Learning-based graph optimization
- Deep reinforcement learning
- Graph representation learning
- Influence maximization
- Rumor containment
- Sequential decision making on networks

## Representative Directions

### 1. Group Influence Maximization with Deep Reinforcement Learning

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/group_influence_drl.png"
      title="Group influence maximization with deep reinforcement learning"
      caption="Figure 1. A learning-based pipeline for node embedding, Q-value computation, and seed selection in group influence maximization."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This work studies group influence maximization using deep reinforcement learning. The framework learns node representations, evaluates candidate actions through Q-values, and then selects influential seed nodes using an exploration-exploitation strategy. The goal is to identify effective intervention strategies in networks with group or community structure, while learning policies that generalize across instances.

**Citation.** Ghosh, Smita, Tiantian Chen, and Weili Wu. "Enhanced group influence maximization in social networks using deep reinforcement learning." *IEEE Transactions on Computational Social Systems* 12, no. 2 (2024): 573-585.

---

### 2. Rumor Containment in Hypergraph Social Networks

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/hypergraph_rumor_containment.png"
      title="Rumor containment in hypergraph social networks"
      caption="Figure 2. A deep reinforcement learning framework for protector node selection in hypergraph-based rumor containment."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This direction addresses rumor containment in social networks modeled as hypergraphs. The method represents higher-order interactions, learns node embeddings, computes action values, and selects protector nodes to limit harmful diffusion. By combining hypergraph structure with deep reinforcement learning, the framework extends beyond pairwise network models and supports intervention in richer diffusion environments.

**Citation.** Kundu, Gouri, Smita Ghosh, and Sankhayan Choudhury. "Rumor containment in hypergraph representation of social networks: A deep reinforcement learning-based solution." *IEEE Transactions on Computational Social Systems* 12, no. 4 (2024): 1653-1664.

---

### 3. Edge Activation for Closed Network Influence Maximization

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/graph_optimization_relink.png"
      title="Edge activation for closed network influence maximization"
      caption="Figure 3. The RELINK framework for edge selection using learned embeddings and Q-value computation."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This work studies closed-network influence maximization through edge activation. Instead of selecting only nodes, the framework learns to activate edges that improve diffusion outcomes under network constraints. The RELINK approach combines learned embeddings, Q-value computation, and reinforcement learning-based decision making to identify high-value edge interventions, broadening the design space for influence optimization in structured networks.

**Citation.** Arya, Shivvrat, Smita Ghosh, Bryan Maruyama, and Venkatesh Srinivasan. "RELINK: Edge activation for closed network influence maximization via deep reinforcement learning." In *Proceedings of the 34th ACM International Conference on Information and Knowledge Management*, pp. 65-76. 2025.

## Summary

Together, these projects illustrate how learning-based optimization can support decision making in complex graph environments. Across node selection, protector selection, and edge activation, the common goal is to learn scalable and effective policies for optimizing diffusion and intervention in networked systems.