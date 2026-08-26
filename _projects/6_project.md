---
layout: page
title: Undergraduate Research & Student Publications
description: Research collaborations with undergraduate student coauthors across social network analysis, machine learning, computational social science, cybersecurity, and applied data science, highlighting student-driven projects that led to conference and journal publications.
img: /assets/img/projects/ugr_research_thumbnail.png
importance: 6
category: research
---

## Overview

This page highlights research collaborations with undergraduate student authors and coauthors. These projects span social network analysis, machine learning, natural language processing, cybersecurity, public-interest data science, and computational social science. Together, they reflect a strong emphasis on student-centered research, hands-on mentorship, and publication-driven undergraduate scholarship.

The projects are listed in **reverse chronological order**, from the most recent to the earlier works.

---

## 2024

### 1. Topic Modeling-Driven Feature Engineering to Enhance Clickbait Detection in Social Networks

<div class="row justify-content-sm-center">
  <div class="col-sm-9 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_topic_modeling_clickbait.png"
      title="Topic modeling-driven feature engineering for clickbait detection"
      caption="Figure 1. A topic-modeling-driven pipeline that extracts latent topic signals from video titles and transcripts, converts them into binary features, and uses them to support clickbait classification."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This project studies how **topic modeling can be used as a feature-engineering mechanism** for clickbait detection in social networks. The figure illustrates a two-stage pipeline. In the first stage, video titles and transcripts are processed through Latent Dirichlet Allocation (LDA) to obtain topic-based information. In the second stage, the derived topic signals are converted into binary features and supplied to a downstream classification model. The core idea is that latent topical structure can provide complementary signals beyond surface-level textual cues, improving the ability to distinguish clickbait from non-clickbait content.

**Citation.** Ghosh, Smita, Shiv Jhalani, and C. J. Oshiro. "Topic Modeling-Driven Feature Engineering to Enhance Clickbait Detection in Social Networks." In *2024 15th International Conference on Information, Intelligence, Systems & Applications (IISA)*, pp. 1-8. IEEE, 2024.

---

### 2. Enhancing Clickbait Detection with Cross-Modal Topic Modeling in Social Networks

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_cross_modal_clickbait.png"
      title="Cross-modal topic modeling for clickbait detection"
      caption="Figure 2. A cross-modal topic-modeling framework that compares topics derived from titles and transcripts and then uses a similarity score to classify content as clickbait or not clickbait."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This project extends clickbait detection by using **cross-modal topic modeling**. Instead of only extracting topical information from a single input source, the method compares the topic structure of the title with the topic structure of the transcript. The similarity between these two topic representations is then used as a discriminative signal. The figure illustrates the intuition clearly: if the title and transcript are topically aligned, the content is less likely to be clickbait; if they diverge substantially, the mismatch may indicate clickbait behavior.

**Citation.** Ghosh, Smita, Diptaraj Sen, and Sneha Ghosh. "Enhancing Clickbait Detection with Cross-Modal Topic Modeling in Social Networks." In *2024 7th International Conference on Information and Computer Technologies (ICICT)*, pp. 289-294. IEEE, 2024.

---

## 2023

### 3. Maximizing Prediction Accuracy in Wildfire Severity: A Comprehensive Analysis of Machine Learning Models Using Environmental Features

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_wildfire_features.png"
      title="Environmental features for wildfire severity prediction"
      caption="Figure 3. Example engineered environmental features used for wildfire severity prediction, including precipitation, rainy season precipitation, rainy-day counts, and high-temperature indicators."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This project examines wildfire severity prediction using **environmental and meteorological features**. The figure lists representative engineered variables, including total precipitation in the months preceding a fire, rainy-season precipitation, counts of rainy days, and counts of very hot days. The study compares machine learning models for predicting wildfire severity and emphasizes the importance of carefully designed domain-relevant features for improving predictive performance.

**Citation.** Nocerino, Michael, and Smita Ghosh. "Maximizing prediction accuracy in wildfire severity: A comprehensive analysis of machine learning models using environmental features." In *2023 IEEE Global Humanitarian Technology Conference (GHTC)*, pp. 448-455. IEEE, 2023.

---

### 4. Detecting Fake News Spreaders on Twitter Through Follower Networks

<div class="row justify-content-sm-center">
  <div class="col-sm-9 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_fake_news_spreaders.png"
      title="Detecting fake news spreaders on Twitter"
      caption="Figure 4. A pipeline for collecting Twitter data, organizing relational information, and labeling tweets and retweets to support fake news spreader detection."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This project studies how to identify **fake news spreaders on Twitter** by leveraging network and content signals. The figure shows a multi-stage pipeline involving data collection through the Twitter API, database organization, relationship extraction, data cleaning, and a classifier that labels tweets and retweets. The broader research goal is to move beyond isolated post classification and instead identify users who actively participate in the spread of misinformation through their follower and retweet behavior.

**Citation.** Ghosh, S., J. M. Z. Fernandez, I. Z. González, A. M. Calle, and N. Shaghaghi. *Detecting fake news spreaders on twitter through follower networks*. Lecture Notes of the Institute for Computer Sciences, Social-Informatics and Telecommunications Engineering (LNICST), vol. 480, 2023.

---

### 5. A Data-Driven Strategy for Online Hate Speech Spreader Identification Using Modified PageRank

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_hate_speech_spreaders.png"
      title="Hate speech spreader identification using modified PageRank"
      caption="Figure 5. A network-based view of spreader identification in which users are connected through a social graph and weighted by signals that can support ranking-based detection."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This project addresses the identification of **hate speech spreaders** on online social networks. The core idea is to move from classifying individual hate speech posts to ranking users according to their likelihood of spreading harmful content. The figure illustrates a network perspective, where users are embedded in a social graph and associated with weights or scores that can be used by a modified PageRank-style approach. This framing supports data-driven identification of influential or high-risk spreaders rather than focusing only on post-level detection.

**Citation.** Ghosh, Smita, and Shiv Jhalani. "A Data-Driven Strategy for Online Hate Speech Spreader Identification Using Modified PageRank." In *Computer Science & Information Technology*, 2023. DOI: [10.5121/csit.2023.131916](https://doi.org/10.5121/csit.2023.131916).

---

## 2022

### 6. Depression Detection Using Machine and Deep Learning Models to Assess Mental Health of Social Media Users

<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_depression_detection.png"
      title="Depression detection and recommendation pipeline"
      caption="Figure 6. A multi-phase framework that labels user posts, computes a user-level happiness or mental-health factor, and uses it to drive downstream recommendation."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This project investigates the use of **machine learning and deep learning for assessing mental health signals in social media activity**. The figure shows a multi-phase framework: user posts are first classified, then aggregated into a user-level factor, and finally used to drive a recommendation component. This structure reflects an important idea in applied mental-health analytics: post-level predictions alone are often insufficient, and more informative user-level assessments can be obtained by aggregating evidence across a user's activity.

**Citation.** Ghosh, S., Ghosh, S., Sen, D., and Das, P. "Depression Detection Using Machine and Deep Learning Models to Assess Mental Health of Social Media Users." *Computer Science & Information Technology*, 2022.

---

### 7. Detection of Clickbait Content Spreaders on Online Social Networks

<div class="row justify-content-sm-center">
  <div class="col-sm-7 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_clickbait_spreaders_retweet_lists.png"
      title="Retweet relationships for clickbait spreaders"
      caption="Figure 7. A user-level illustration showing how retweet lists can be associated with network relationships to model clickbait content spreading behavior."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-7 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_clickbait_spreaders_sampling.png"
      title="Sampling tweets for clickbait spreader analysis"
      caption="Figure 8. A schematic showing how a tweet collection can be partitioned across users to construct user-level tweet sets for spreader analysis."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This project studies the detection of **clickbait content spreaders**, rather than only classifying clickbait posts themselves. The first figure shows the network intuition behind the task by associating users with retweet lists and relationships. The second figure illustrates how tweet collections can be sampled and assigned to users so that user-level representations can be constructed. Together, these figures support a spreader-centric perspective: the goal is to identify which users are systematically involved in producing or propagating clickbait content in a networked environment.

**Citation.** Ghosh, Smita, Pramita Das, Sneha Ghosh, and Diptaraj Sen. "Detection of Clickbait Content Spreaders on Online Social Networks." In *2022 5th International Conference on Information and Computer Technologies (ICICT)*, pp. 23-28. IEEE, 2022.

---

## 2021

### 8. Twitter Sentiment Analysis and Political Approval Ratings for Situational Awareness

<div class="row justify-content-sm-center">
  <div class="col-sm-9 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_twitter_sentiment_timeseries.png"
      title="Twitter sentiment over time"
      caption="Figure 9. Time-series sentiment analysis showing positive and negative tweet volumes over time."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<div class="row justify-content-sm-center">
  <div class="col-sm-9 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_political_approval_ratings.png"
      title="Political approval ratings from social media sentiment"
      caption="Figure 10. Approval and disapproval trends estimated from social media sentiment for situational awareness."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

This project studies how **Twitter sentiment can be used for situational awareness and political approval estimation**. The first figure presents temporal sentiment trends, tracking positive and negative tweet volumes over time. The second figure translates such social media signals into approval and disapproval trajectories. Together, the figures illustrate how large-scale online discourse can be used as a proxy for evolving public sentiment and political response.

**Citation.** Shaghaghi, Navid, Andres Mauricio Calle, Juan Manuel Zuluaga Fernandez, Mubashir Hussain, Yash Kamdar, and Smita Ghosh. "Twitter sentiment analysis and political approval ratings for situational awareness." In *2021 IEEE Conference on Cognitive and Computational Aspects of Situation Management (CogSIMA)*, pp. 59-65. IEEE, 2021.

---

### 9. ClassRoute: Bridging the Digital Academic-Content Divide

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_classroute_functions.png"
      title="ClassRoute platform functions"
      caption="Figure 11. Core functions of the ClassRoute platform, including multilingual translation, educational videos, syllabi, question-and-answer resources, community discussion, individualized assessment, and accompanied learning trajectories."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

ClassRoute investigates how machine learning, natural language processing, and mobile educational technologies can help reduce the **digital academic-content divide**. The platform is designed around mother-tongue-based community learning and aims to improve access to educational materials for students who may face linguistic, geographic, or socioeconomic barriers.

The figure above summarizes the major functions of the platform. ClassRoute integrates multilingual translation, instructional videos, syllabi, a question-and-answer repository, community discussion, individualized knowledge assessment, learning trajectories, and mechanisms for recognizing student accomplishments. The goal is to provide an integrated educational environment rather than only translating isolated learning materials.

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_classroute_dashboard.png"
      title="ClassRoute mobile learning interface"
      caption="Figure 12. Example ClassRoute mobile interfaces showing the learner dashboard and video-based study functionality."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

The mobile interface illustrates how these capabilities are presented directly to learners. The dashboard provides access to resources such as the question bank, educational videos, community discussions, and learner-oriented features. The video-study interface organizes educational content into accessible topic-based lessons, supporting mobile-first learning in environments where conventional educational resources may be limited.

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid
      path="assets/img/projects/ugr_classroute_qa_bengali.png"
      title="ClassRoute multilingual community Q&A"
      caption="Figure 13. Example of ClassRoute's community question-and-answer functionality in Bengali, illustrating its support for mother-tongue-based learning."
      class="img-fluid rounded z-depth-1" %}
  </div>
</div>

A central design objective of ClassRoute is to make educational interaction available in a learner's **mother tongue**. The example above shows the community question-and-answer interface in Bengali, where learners can submit questions and participate in discussions in their preferred language. This multilingual support is intended to reduce language barriers while preserving the collaborative aspects of online learning.

**Citation.** Shaghaghi, Navid, Maria Joseph Israel, Smita Ghosh, Saikat Mondal, Anindita Mondal, and Abhishek Biswas. "ClassRoute: Bridging the Digital Academic-Content Divide." In *2021 1st Conference on Online Teaching for Mobile Education (OT4ME)*, pp. 168-173. IEEE, 2021.

---

## Summary

These undergraduate research collaborations span a wide range of areas, including clickbait detection, misinformation spreader detection, hate speech spreader identification, wildfire severity prediction, social-media-based mental health analysis, situational awareness, and educational technology. Across these projects, undergraduate student researchers contributed to publishable work that combined methodological development with practical, socially relevant applications.
