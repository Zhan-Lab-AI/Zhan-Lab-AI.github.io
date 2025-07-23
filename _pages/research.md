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

Building upon our prior work DYNA, a disease-specific language model for variant pathogenicity prediction, we propose a novel direction that introduces world models into the field of genomic interpretation. This approach reconceptualizes variant effect prediction as a dynamic reasoning process—where predictions evolve over time as new clinical or biological evidence becomes available.

This shift toward world modeling enables more flexible and forward-looking interpretation of variants of uncertain significance (VUS), particularly in underrepresented diseases such as cardiovascular disorders. It lays the groundwork for rethinking how uncertainty and evidence accumulation are handled in clinical genomics.

<p align="center">
  <img src="/image/dyna-worldmodel.pdf" alt="DYNA-WorldModel workflow" width="600">
</p>

**Figure.** *Illustration of our DYNA-WorldModel framework.*  
The model treats variant interpretation as an evolving state, enabling re-evaluation as additional information emerges. This paradigm is especially impactful for rare variant prioritization in contexts with limited labeled data.


*Related publication:*
- [Zhan, H., Moore, J. H., & Zhang, Z. (2025). A disease-specific language model for variant pathogenicity in cardiac and regulatory genomics. <i>Nature Machine Intelligence</i>.](https://huixin-zhan-ai.github.io//publications/)
