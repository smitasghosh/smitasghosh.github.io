---
layout: page
title: Evolutionary & Higher-Order Network Dynamics
description: Models and learning-based methods for evolutionary diffusion, fixation processes, competitive and reversible dynamics in complex networks, with an emphasis on long-horizon decision making.
img: /assets/img/projects/evolutionary_network_dynamics_thumbnail.png
importance: 3
category: research
---

## Overview

This research area studies network processes that go beyond standard irreversible diffusion models. A central focus is on **evolutionary dynamics**, where competing states spread stochastically over a network and the long-term outcome depends on both graph structure and node-dependent fitness. More broadly, this area is concerned with network models in which interaction dynamics are richer, more competitive, and more structurally nuanced than classical pairwise influence propagation.

Key themes include:

- Evolutionary diffusion on networks
- Fixation maximization
- Competitive and reversible propagation
- Position-dependent fitness
- Active node selection
- Higher-order network dynamics

## Representative Direction

### 1. Evolutionary Diffusion and Fixation Maximization

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/evolutionary_network_dynamics_thumbnail.png"
      title="Positional Moran process dynamics with active nodes"
      caption="Figure 1. Positional Moran process dynamics with active nodes and mutant reproduction."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This work studies **fixation maximization** under the **positional Moran process**, a competitive diffusion model in which propagation is stochastic, reversible, and influenced by node position and fitness. In contrast to classical influence maximization, the objective here is not simply to trigger large diffusion, but to select an initial active set that maximizes the probability of eventual population-wide dominance.

The figure illustrates the dynamics of the process. On the left, selected active nodes are highlighted, and the mutant node reproduces with an advantage determined by the fitness term \(1 + \delta\). Red arrows indicate mutant-driven reproduction or spread from the currently active configuration. On the right, the process transitions to the next state, where blue arrows indicate the subsequent reproduction and replacement dynamics. The figure emphasizes that evolutionary diffusion is **competitive and state-dependent**: the next configuration depends not only on network connectivity, but also on which nodes are active, how fitness is distributed, and how reproduction propagates through the graph over time.

This setting motivates the development of scalable learning-based policies for active node selection. The accepted paper introduces **LEAP**, a deep reinforcement learning framework that formulates active node selection as a Markov decision process and learns fixation-aware representations that capture graph structure together with invasion and stability signals. The goal is to achieve high-quality fixation strategies without relying on repeated simulation-intensive greedy search.

**Status.** Accepted paper; formal citation to be added once bibliographic details are available.

## Summary

This project illustrates a broader shift from static diffusion models toward **evolutionary and competitive network dynamics**. By combining graph structure, stochastic competition, and learning-based optimization, this line of research seeks scalable methods for reasoning about long-horizon dominance and intervention in evolving networked systems.