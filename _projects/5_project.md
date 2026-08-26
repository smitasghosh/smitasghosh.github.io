---
layout: page
title: Applied & Interdisciplinary Machine Learning
description: Interdisciplinary applications of machine learning, graph analysis, natural language processing, and computational methods to problems spanning neuroscience, cybersecurity, data structures, and other scientific domains.
img: /assets/img/projects/AI_interdisc_thumbnail.png
importance: 5
category: research
---

## Overview

This research area applies machine learning, graph analysis, natural language processing, and computational modeling to interdisciplinary problems beyond traditional social network analysis. The work combines methodological development with domain-specific questions in areas including neuroscience, cybersecurity, and the mathematical analysis of computational structures.

A common theme is the use of computational methods not only to improve predictive or algorithmic performance, but also to understand the structure underlying a problem and develop methods that remain interpretable and practically meaningful.

Key themes include:

- Applied machine learning
- Graph-based data analysis
- Explainable and interpretable methods
- Computational neuroscience
- Cybersecurity and password analysis
- Natural language and phonetic modeling
- Algebraic analysis of computational structures
- Interdisciplinary computational research

## Representative Directions

### 1. Brain Network Classification

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/brain_network_classification.png"
      title="Discriminative connectivity in brain networks"
      caption="Figure 1. Representative discriminative functional connections identified in brain-network classification."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This work investigates whether functional brain networks derived from functional magnetic resonance imaging (fMRI) can be classified to identify connectivity patterns associated with neurodevelopmental conditions such as Autism Spectrum Disorder (ASD) and Attention-Deficit/Hyperactivity Disorder (ADHD).

Each fMRI scan is represented as a graph in which vertices correspond to brain regions of interest and edges capture functional co-activation between regions. The research studies explainable graph-classification approaches, including Contrast Subgraphs and a simpler **Discriminative Edges** method designed to identify connectivity patterns that distinguish populations while reducing computational complexity.

The figure visualizes representative discriminative connections between brain regions. Such connections provide an interpretable representation of which functional relationships contribute to distinguishing brain-network populations, allowing the analysis to go beyond a purely black-box classification outcome.

The study also examines tabular representations of graph data, higher-order connectivity information, and similarity-based analyses to better understand the fundamental difficulty of classifying brain networks.

**Citation.** Enns, Keanelek, Kazi Tabassum Ferdous, Sowmya Balasubramanian, Smita Ghosh, Venkatesh Srinivasan, and Alex Thomo. "Are brain networks classifiable?" *Network Modeling Analysis in Health Informatics and Bioinformatics* 13, no. 1 (2024): 44.

---

### 2. Generating and Attacking Passwords with Misspellings

<div class="row justify-content-sm-center">
  <div class="col-sm-9 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/homophone_password_cracking.png"
      title="Password cracking with homophone-based misspellings"
      caption="Figure 2. Password-cracking performance using baseline dictionaries and dictionaries augmented with generated homophonous misspellings across multiple test datasets."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This work examines a counterintuitive question in password security: **does intentionally misspelling words actually make passwords more resistant to guessing attacks?** Many traditional password recommendations encourage users to avoid dictionary words or replace them with nonstandard spellings. The research studies whether attackers can systematically exploit this behavior.

The work introduces two methods for generating similar-sounding misspellings by treating the problem through the linguistic concept of homophones. **ProbP2G** uses probabilistic phoneme-to-grapheme correspondences, while **LSTM-P2G** uses a neural phoneme-to-grapheme model to generate alternative spellings that preserve similar pronunciations.

The figure compares password-cracking rates obtained using the original dictionaries with dictionaries augmented by generated misspellings across multiple password datasets. The results demonstrate that incorporating homophonous misspellings can increase cracking success, showing that nonstandard spelling alone does not necessarily provide meaningful protection against adaptive attackers.

**Citation.** Houshmand, Shiva, Smita Ghosh, and Jared Maeyama. "Generating and Attacking Passwords with Misspellings by Leveraging Homophones." In *IFIP International Conference on ICT Systems Security and Privacy Protection*, pp. 67-81. Cham: Springer Nature Switzerland, 2025.

---

### 3. An Algebraic Perspective on Tree Imbalance

<div class="row justify-content-sm-center">
  <div class="col-sm-9 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/tree_imbalance.png"
      title="Algebraic analysis of tree imbalance"
      caption="Figure 3. An example of structural imbalance introduced through additional tree depth."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This work develops an algebraic perspective on **tree imbalance**, connecting commonly used imbalance measures with concepts from group theory and structural symmetry. Rather than treating tree balance only through conventional statistics such as subtree size or height differences, the research investigates how permutations and group actions can characterize asymmetry in tree structures.

Two complementary approaches are studied. The first interprets subtree-based imbalance through the action of symmetric groups on child subtrees. The second uses the **orbit-stabilizer theorem** to quantify structural asymmetry based on the number of distinguishable arrangements at different levels of a tree.

The figure illustrates a tree whose additional depth introduces structural imbalance. This example is particularly useful because conventional measures such as Colless' Index can fail to distinguish the modified structure from a more balanced tree, whereas the orbit-stabilizer-based measure captures the added asymmetry. The example highlights how an algebraic formulation can identify structural differences that are invisible to some traditional tree-imbalance metrics.

**Citation.** Palit, Priyojit, and Smita Ghosh. "An Algebraic Perspective on Tree Imbalance Metrics." In *International Conference on Algorithmic Aspects in Information and Management*, pp. 243-253. Singapore: Springer Nature Singapore, 2024.

## Summary

These projects illustrate the breadth of interdisciplinary computational research: graph-based methods are used to investigate functional brain connectivity, language and deep learning are applied to password security, and algebraic techniques provide new perspectives on structural properties of trees.

Across these domains, the common objective is to adapt computational and machine learning methods to the structure of the underlying problem while emphasizing interpretability, rigorous analysis, and practical relevance.

