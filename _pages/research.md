---
layout: archive
title: "Research"
excerpt: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}


<a id="sec-1"></a>
#### 1. World Models in Genomics: From DYNA to Dynamic Variant Reclassification

Building upon our prior work **DYNA**, a disease-specific language model for variant pathogenicity prediction, we explore a novel application of *world models*—a concept borrowed from agentic AI and model-based reinforcement learning—to dynamically reclassify variants of uncertain significance (VUS). This approach treats variant interpretation as an evolving reasoning process, where predictions are updated as new evidence becomes available.

Our framework integrates model-based reinforcement learning with large language model (LLM)-based embeddings, enabling **uncertainty-aware re-evaluation** of rare cardiovascular variants such as those in *FBN2*. This is a significant departure from static classifiers, allowing our model to simulate how clinical understanding might improve over time.

<p align="center">
  <img src="/assets/img/research/dyna-worldmodel.png" alt="DYNA-WorldModel workflow" width="600">
</p>

**Figure.** *Illustration of our DYNA-WorldModel framework.*  
The model combines LLM-based representations with model-based reinforcement learning, updating pathogenicity assessments as evidence accumulates. It is designed to handle underpowered or sparse case data scenarios and is especially applicable to VUS reclassification in clinical genomics.


*Related publication:*
- [Zhan, H., Moore, J. H., & Zhang, Z. (2025). A disease-specific language model for variant pathogenicity in cardiac and regulatory genomics. <i>Nature Machine Intelligence</i>.](https://huixin-zhan-ai.github.io//publications/)
