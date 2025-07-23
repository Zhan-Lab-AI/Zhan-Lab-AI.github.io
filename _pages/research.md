---
layout: archive
title: "Research"
excerpt: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

<p>
At the <strong>Zhan Lab</strong>, we build next-generation AI systems that connect language models, clinical reasoning, and biological discovery. 
Our mission is to enable <strong>trustworthy, interpretable, and interactive AI</strong> that transforms genomic medicine, precision health, and human-AI collaboration.
</p>

<p>
We believe foundational models—if properly secured and grounded—can revolutionize science and healthcare. 
Our research spans from rare variant discovery to secure genomics and autonomous surgical reasoning.
</p>

<h2>Primary Research Areas</h2>
<ol>
  <li>
    <a href="#sec-1">Variant Effect Prediction with Large Language Models</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;1.1 <a href="#sec-1-1">Disease-Specific Modeling</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;1.2 <a href="#sec-1-2">World Models for Dynamic Reclassification</a>
  </li>
  <li>
    <a href="#sec-2">Trustworthy and Secure Genomic AI</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;2.1 <a href="#sec-2-1">Privacy Leakage in Foundation Models</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;2.2 <a href="#sec-2-2">Adversarial Robustness</a>
  </li>
  <li>
    <a href="#sec-3">Unified Generative AI for Surgery and Rehabilitation</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;3.1 <a href="#sec-3-1">Diffusion-Based Surgical Gesture Prediction</a><br>
    &nbsp;&nbsp;&nbsp;&nbsp;3.2 <a href="#sec-3-2">Assistive Robotics for Rehab</a>
  </li>
</ol>

<hr>

<a id="sec-1"></a>
<h3>1. Variant Effect Prediction with Large Language Models</h3>
<p>
We develop disease-specific language models to predict the functional impact of genetic mutations. 
Our flagship system, <strong>DYNA</strong>, enables more precise variant interpretation for cardiac and regulatory genomics.
</p>

<a id="sec-1-1"></a>
<h3>1.1 Disease-Specific Modeling</h3>
<p>
DYNA outperforms general-purpose LLMs by focusing on domain-specific signals in gene regulation and disease mechanisms. 
We work on calibration, zero-shot generalization, and clinically relevant variant filtering.
</p>

<a id="sec-1-2"></a>
<h3>1.2 World Models in Genomics: From DYNA to Dynamic Variant Reclassification</h3>
<p>
Building upon our prior work DYNA, a disease-specific language model for variant pathogenicity prediction, we propose a novel direction that introduces world models into the field of genomic interpretation. This approach reconceptualizes variant effect prediction as a dynamic reasoning process—where predictions evolve over time as new clinical or biological evidence becomes available.

This shift toward world modeling enables more flexible and forward-looking interpretation of variants of uncertain significance (VUS), particularly in underrepresented diseases such as cardiovascular disorders. It lays the groundwork for rethinking how uncertainty and evidence accumulation are handled in clinical genomics.

</p>
 

<p align="center">
  <img src="/images/dyna-worldmodel.pdf" alt="DYNA-WorldModel workflow" width="600">
</p>

**Figure.** *Illustration of our DYNA-WorldModel framework.*  
The model treats variant interpretation as an evolving state, enabling re-evaluation as additional information emerges. This paradigm is especially impactful for rare variant prioritization in contexts with limited labeled data.


*Related publication:*
- [Zhan, H., Moore, J. H., & Zhang, Z. (2025). A disease-specific language model for variant pathogenicity in cardiac and regulatory genomics. <i>Nature Machine Intelligence</i>.](https://huixin-zhan-ai.github.io//publications/)

<hr>

<a id="sec-2"></a>
<h3>2. Privacy and Security in Genomic AI</h3>
<p>
Genomic foundation models are powerful—but vulnerable. 
We study <strong>privacy risks</strong> and build <strong>robust learning frameworks</strong> to make genomic AI secure, reproducible, and fair.
</p>

<a id="sec-2-1"></a>
<h3>2.1 Privacy Leakage in Foundation Models</h3>
<p>
Our recent work revealed privacy leakage in models like DNABERT-2. 
Using mutational probes, we demonstrate that even foundation models trained without labels can memorize sensitive genomic sequences. 
We introduce defense strategies such as mutational masking.
</p>

<a id="sec-2-2"></a>
<h3>2.2 Adversarial Robustness</h3>
<p>
We test how robust genomic LLMs are under adversarial perturbations—like biologically plausible point mutations—
and develop robust training techniques for variant prediction models to remain stable in real-world deployment.
</p>

<p align="center">
  <img src="/images/adversarial.png" alt="Adversary GFMs" width="600">
</p>

**Figure.** *Illustration of adversarial sensitivity in GFMs.* 

*Related publication:*
- [Zhan, H., Moore, J. H. (2025). SafeGenes: Evaluating the Adversarial Robustness of Genomic Foundation Models. <i>Submitted</i>.](https://arxiv.org/abs/2506.00821)

<hr>

<a id="sec-3"></a>
<h3>3. Privacy-Aware Agentic AI for Surgery and Rehabilitation</h3>
<p>
To build truly <strong>trustworthy agentic AI</strong> for clinical settings, we must go beyond performance—
addressing <strong>privacy, generalizability, and robustness</strong> in embodied and interactive medical AI systems.
Our lab explores how to integrate language models and sensor data while safeguarding patient confidentiality and minimizing information leakage.
</p>

<a id="sec-3-1"></a>
<h3>3.1 Privacy-Preserving Surgical Gesture Prediction</h3>
<p>
Surgical AI must reason over real-time data—often from cameras, wearables, and robotic devices—yet these streams can contain sensitive information.
We study how to predict the next <strong>surgical gesture or subphase</strong> using <strong>privacy-aware multimodal modeling</strong>, 
ensuring data minimization and feature obfuscation without degrading performance.
Our goal is to enable <strong>skill assessment, decision support, and AI-guided training</strong> while preserving surgeon and patient privacy.
</p>

<a id="sec-3-2"></a>
<h3>3.2 Assistive Robotics for Rehab</h3>
<p>
We collaborate with clinicians and engineers to embed AI into rehab robotics. 
We use wearable sensor data and fine-grained action modeling to personalize rehabilitation plans for stroke and spinal injury patients.
</p>

<p align="center">
  <img src="/images/robotics.png" alt="Privacy-Preserving Surgical Gesture Prediction" width="600">
</p>

**Figure.** *Personalized gesture sequence prediction using diffusion models.* 

*Related publication:*
- [Zhan, H., Moore, J. H. (2025). Agentic Surgical AI: Surgeon Style Fingerprinting and Privacy Risk Quantification via Discrete Diffusion in a Vision-Language-Action Framewor. <i>MICCAI Agentic AI Workshop</i>.](https://arxiv.org/abs/2506.08185)
