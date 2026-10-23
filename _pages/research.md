---
layout: page
permalink: /research/
title: research
description: Research themes and current directions
nav: true
nav_order: 3.5
---

<style>
.research-left {
  text-align: left;
}
.research-right {
  text-align: right;
}
.research-section {
  margin-bottom: 2rem;
  padding-bottom: 1.5rem;
  border-bottom: 1px solid var(--global-divider-color);
}
.research-section:last-child {
  border-bottom: none;
}
.research-meta {
  margin-top: 1rem;
  font-size: 0.9rem;
}
.research-meta strong {
  color: var(--global-theme-color);
}
</style>

<div class="research-section research-left" markdown="1">

## Geometry and Topology of Neural Representations

We study how neural networks, both artificial and biological, represent information, using tools from geometry and topological data analysis. We treat internal representations as point clouds that evolve across the layers of a model or over time in neural population recordings, and characterize how these systems organize and transform information. In large language models, this reveals interpretable structure in the latent space; in recordings from the mouse visual cortex, it yields compact topological descriptors that distinguish responses to different stimuli. Our goal is to make representations not only interpretable but also actionable, turning these descriptors into practical tools such as pre-output monitoring, layer pruning, and understanding how uncertainty propagates through a network.

<div class="research-meta">
<strong>People:</strong> Yuri Gardinazzi, Karthik Viswanathan, Ana Fló and Sven Heydenreich<br>
<strong>Papers:</strong> <a href="https://icml.cc/virtual/2025/poster/43958">Persistent Topological Features in Large Language Models</a>, <a href="https://openreview.net/forum?id=rBEgNAslpY">The Intrinsic Dimension of Prompts in Internal Representations of Large Language Models</a>, <a href="https://proceedings.mlr.press/v325/gardinazzi26b.html">Zigzag Persistence of Neural Responses to Time-Varying Stimuli</a>
</div>

</div>

<div class="research-section research-right" markdown="1">

## Differentiable Zigzag Persistence

Zigzag persistent homology characterizes topological structures that evolve non-monotonically, such as those arising from time-evolving data. Unlike standard persistent homology, it has so far lacked a notion of differentiability. We develop a differentiability framework for zigzag persistence based on linear interpolation, so that zigzag-based topological constraints can be integrated into gradient-based learning pipelines. This opens the way to optimizing and analyzing data that evolve dynamically over time, for example optimizing the coverage of a sensor network.

<div class="research-meta">
<strong>People:</strong> Enrico Maria Ferrari, Clemens Bannwart<br>
<strong>Papers:</strong> <a href="https://arxiv.org/abs/2609.39242">A differentiability framework for zigzag persistent homology via linear interpolation</a>
</div>

</div>

<div class="research-section research-left" markdown="1">

## Learning Optimal Topological Summaries

Applying topological data analysis requires choosing filtrations and vectorization schemes. We introduce methods to learn these components by maximizing relevant information about the system. This enables automated, task-specific optimization of the topological pipeline for scientific inference problems. The framework is implemented in an open-source library and applies to point clouds, fields, and time series.

<div class="research-meta">
<strong>People:</strong> Karthik Viswanathan, Enrico Maria Ferrari, Sven Heydenreich<br>
<strong>Papers:</strong> <a href="https://arxiv.org/abs/2605.07720">TopoFisher: Learning Topological Summary Statistics by Maximizing Fisher Information</a>
</div>

</div>

<!-- Bayesian Inference for Spectroscopy section hidden — too far off from main research themes
<div class="research-section research-right" markdown="1">

## Bayesian Inference for Spectroscopy

We develop Bayesian methods for feature extraction from X-ray absorption and other spectroscopic data. By fitting physically motivated forward models with full uncertainty quantification, we enable robust analysis of operando measurements where traditional baseline subtraction fails. The approach combines objective model selection via information criteria with MCMC posterior sampling to provide interpretable, statistically rigorous spectral decomposition.

<div class="research-meta">
</div>

</div>
-->
