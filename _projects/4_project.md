---
layout: page
title: AI for Digital Mental Health & Computational Social Science
description: Interdisciplinary AI research for understanding how people use and perceive conversational AI for mental health and emotional support, combining social media analysis, natural language processing, and safety-oriented methods for responsible conversational AI.
img: /assets/img/projects/digital_mental_health_safechat.png
importance: 4
category: research
---

## Overview

This research area investigates how artificial intelligence, particularly conversational and generative AI, intersects with mental health, emotional support, and online human behavior. The work combines machine learning, natural language processing, computational social science, and graph-based methods to study how people use AI systems, what benefits and concerns they perceive, and how such systems can be made safer for sensitive interactions.

The research spans both **descriptive and safety-oriented perspectives**. One direction analyzes large-scale social media discourse to understand users' experiences with AI-mediated emotional support. A complementary direction develops computational safeguards for identifying potentially sensitive or high-risk conversations in conversational AI systems.

Key themes include:

- Generative AI for mental health and emotional support
- Computational social science
- Conversational AI safety
- Self-harm risk detection
- Sentiment and behavioral analysis
- Topic modeling and thematic analysis
- Social media discourse analysis
- Graph-based conversational modeling
- Responsible and human-centered AI

## Representative Directions

### 1. Understanding Sentiment Toward AI-Mediated Mental Health Support

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/digital_mental_health_sentiment.png"
      title="Sentiment analysis of social media discussions"
      caption="Figure 2. Comparison of sentiment classifications obtained using VADER, RoBERTa, and Microsoft sentiment analysis models."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This work examines how people discuss ChatGPT's emerging role in emotional and mental health support on social media. Multiple sentiment analysis approaches are used to characterize whether online discussions express predominantly positive or negative perceptions.

The figure compares sentiment distributions produced by three different analysis methods: VADER, RoBERTa, and Microsoft's sentiment model. Although the exact classifications vary across models, the analysis provides a complementary view of how users characterize their experiences with conversational AI for emotional and mental health support.

**Citation.** Ghosh, Smita, Xiaochen Luo, Jared Maeyama, Shiv Jhalani, C. J. Oshiro, Tharun Venkatesh, and Rushil Patel. "Therapist by Chance: Investigating ChatGPT’s Emotional and Mental Health Support via Sentiment Analysis on Social Networks." In *International Conference on Advances in Social Networks Analysis and Mining*, pp. 124-138. Cham: Springer Nature Switzerland, 2025.

---

### 2. How Users Shape ChatGPT into a Digital Therapist

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/digital_mental_health_themes.png"
      title="Themes in the use of ChatGPT for mental health"
      caption="Figure 3. Themes characterizing how Reddit users describe using ChatGPT for mental health and emotional support."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

Beyond aggregate sentiment, this research examines **why and how people use ChatGPT for mental health-related purposes**. The thematic analysis identifies several dimensions of these interactions, including users' therapeutic goals, engagement patterns, perceived advantages over human therapy, and concerns or limitations.

The themes include uses such as companionship, self-discovery, emotional support, journaling, guidance seeking, and preparation for therapy. Users also describe characteristics they perceive as advantageous, including accessibility, availability, perceived non-judgment, and consistency. At the same time, the analysis surfaces concerns involving emotional depth, privacy, ethical safeguards, and the distinction between immediate conversational support and longer-term personal growth.

**Citation.** Luo, Xiaochen, Smita Ghosh, Jacqueline L. Tilley, Patrica Besada, Jinqiu Wang, and Yangyang Xiang. "Shaping ChatGPT into my Digital Therapist: A thematic analysis of social media discourse on using generative artificial intelligence for mental health." *Digital Health* 11 (2025): 20552076251351088.

---

### 3. Structured Detection of Self-Harm Risk in Conversation

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/safechat_model_results.png"
      title="SAFE-Chat model comparison"
      caption="Figure 4. Performance comparison across machine learning, transformer, graph-based, and agentic approaches for conversation-level sensitivity detection."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

A central question in SAFE-Chat is how different representations capture self-harm-relevant signals distributed across a multi-turn conversation. The study compares several model families, including XGBoost, Mental-RoBERTa, a confidence-oriented graph convolutional network, and an agentic AI approach.

The results shown above indicate that the graph-based conversational representation provides the strongest performance on several reported classification metrics. This supports the paper's broader hypothesis that **structured dialogue representations can capture context-dependent risk signals that may not be adequately represented by individual utterances alone**.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/safechat_utterance_risk.png"
      title="Context-dependent utterance sensitivity"
      caption="Figure 5. Example conversation-level sensitivity scores associated with individual utterances."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

The framework also examines how sensitivity evidence is distributed across individual conversational turns. Some utterances provide explicit indicators of risk, whereas others are substantially more ambiguous when interpreted independently.

This illustrates why conversation-level modeling is important: risk can depend on **how multiple utterances interact and accumulate over time**, rather than being determined by isolated keywords or single-message classification.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/safechat_conversation_example.png"
      title="SAFE-Chat conversational safeguard"
      caption="Figure 6. Illustration of SAFE-Chat monitoring a multi-turn interaction and identifying elevated conversational sensitivity."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

The example illustrates SAFE-Chat as a modular safeguard around an existing conversational system. The conversational model continues generating responses, while the safeguard independently evaluates the evolving interaction and can raise a sensitivity flag when the accumulated context warrants additional attention.

This design decouples safety monitoring from the underlying generative model, making the framework applicable as an external layer for conversational AI systems.

**Status.** Figures 4-6 are from an accepted paper; formal citation to be added once bibliographic details are available.

---

### 4. Tracking Public Perceptions of Conversational AI Across Platforms and Time

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/digital_mental_health_analysis_pipeline.png"
      title="Cross-platform computational social science analysis"
      caption="Figure 8. Analysis pipeline combining sentiment analysis, topic modeling, and temporal analysis of social media discussions."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

A complementary project studies how perceptions of conversational AI for emotional and mental health support differ across **platforms, sentiment categories, and time**. The analysis integrates data collection and preprocessing with sentiment analysis, topic modeling, and temporal analysis.

Rather than treating positive, neutral, and negative sentiment as homogeneous categories, the work examines the underlying narratives associated with each sentiment class.

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/digital_mental_health_cross_platform_topics.png"
      title="Cross-platform themes in conversational AI discourse"
      caption="Figure 9. Representative topics associated with positive, neutral, and negative discussions across Twitter/X, Reddit, and YouTube."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

The analysis reveals qualitatively different narratives across platforms and sentiment groups. Positive discussions emphasize themes such as accessibility, conversational support, personal growth, and perceived helpfulness. Neutral discussions include evaluation of AI tools, privacy-related discussions, and questions about whether AI can substitute for conventional support. Negative discussions surface concerns involving reliability, superficial assistance, inadequate support, and broader social consequences.

The project therefore moves beyond aggregate sentiment scores to study **what specific benefits, expectations, limitations, and concerns are represented within each sentiment category**. It also examines whether these narratives and sentiment distributions change over time.

**Status.** Figures 8-9 are from an accepted paper; formal citation to be added once bibliographic details are available.

## Summary

Together, these projects examine AI-mediated mental health from both **human-centered and computational safety perspectives**. Computational social science methods reveal why people seek emotional support from conversational AI, what they value, and what concerns they express across online communities. In parallel, machine learning and graph-based approaches provide mechanisms for detecting sensitive conversational contexts and supporting safer deployment.

This research aims to better understand the emerging relationship between people and conversational AI while developing computational methods that make these systems more interpretable, responsible, and sensitive to the risks associated with real-world use.