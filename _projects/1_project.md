---
layout: page
title: Network Science & Social Influence
description: Models and algorithms for understanding influence, diffusion, community effects, and intervention in complex networks.
img: /assets/img/projects/network_science_thumbnail.png
importance: 1
category: research
---

## Overview

This research area studies how information, behaviors, and influence propagate through social and networked systems. The work spans higher-order influence models, group and community-aware diffusion, and intervention strategies such as rumor blocking and protective diffusion. Across these directions, the goal is to develop principled models and scalable algorithms for understanding and optimizing network processes.

Key themes include:

- Influence maximization
- Information diffusion
- Higher-order and hypergraph influence
- Group and community structure
- Rumor propagation and blocking
- Network intervention and protection

## Representative Directions

### 1. Higher-Order Influence in Social Networks

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/network_hyperedge.png"
      title="Higher-order influence in hypergraphs"
      caption="Figure 1. An example of a hyperedge capturing higher-order influence."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

Many diffusion processes cannot be adequately modeled using only pairwise edges. In higher-order settings, multiple source nodes may jointly influence a target node, motivating hypergraph-based models of social influence. This line of work studies influence maximization in hypergraphs, where diffusion depends on richer interaction structure than standard graph models.

**Citation.** Zhu, Jianming, Junlei Zhu, Smita Ghosh, Weili Wu, and Jing Yuan. "Social influence maximization in hypergraph in social networks." *IEEE Transactions on Network Science and Engineering* 6, no. 4 (2018): 801-811.

---

### 2. Group Influence and Community Structure

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/network_community_diffusion.png"
      title="Group influence and community structure"
      caption="Figure 2. Example of an information diffusion process across groups or communities."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

Influence often unfolds within and across groups, communities, or social units rather than in an undifferentiated network. This work examines group influence maximization, where the objective is to understand or optimize diffusion while accounting for community structure and collective behavior. Such models help capture the role of mesoscale organization in shaping diffusion outcomes.

**Citation.** Zhu, Jianming, Smita Ghosh, and Weili Wu. "Group influence maximization problem in social networks." *IEEE Transactions on Computational Social Systems* 6, no. 6 (2019): 1156-1164.

---

### 3. Rumor Blocking and Protective Intervention

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/network_rumor_blocking.png"
      title="Rumor blocking and protective diffusion"
      caption="Figure 3. Example of rumor spreading and protective intervention over time."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

In addition to maximizing beneficial diffusion, an important challenge is limiting harmful or misleading information. This direction studies rumor blocking under uncertainty, where the aim is to identify intervention strategies that reduce rumor spread even when rumor sources are not fully known in advance. These models capture the interaction between adverse diffusion and protective actions in uncertain network environments.

**Citation.** Zhu, Jianming, Smita Ghosh, and Weili Wu. "Robust rumor blocking problem with uncertain rumor sources." *World Wide Web* 24, no. 1 (2021): 229-247.

## Summary

Together, these projects illustrate a broad view of network science and social influence: influence may arise through higher-order interactions, spread through community structure, and require robust intervention in the presence of harmful diffusion. This research develops algorithmic and modeling tools for analyzing and optimizing these processes in complex networks.