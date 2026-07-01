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

## Geometry and Topology of Large Language Models

We study the internal representations of transformer models using tools from geometry and topological data analysis. By treating token embeddings as evolving point clouds across layers, we characterize how models organize and process information. This geometric perspective reveals interpretable structure in the latent space and provides practical tools for model interpretability and safety. Applications include pre-output monitoring, layer pruning, and understanding uncertainty propagation in neural networks.

<div class="research-meta">
<strong>People:</strong> Yuri Gardinazzi and Karthik Viswanathan<br>
<strong>Papers:</strong> <a href="https://icml.cc/virtual/2025/poster/43958">Persistent Topological Features in Large Language Models</a>, <a href="https://arxiv.org/pdf/2501.10573">The Geometry of Tokens in Internal Representations of Large Language Models</a>
</div>

</div>

<div class="research-section research-right" markdown="1">

## Topological Analysis of Neural Dynamics

We develop methods to characterize temporal evolution in neural population recordings using persistent homology. By tracking topological features (loops, connected components) in time-varying activity patterns, we extract compact representations of spatiotemporal dynamics. This framework applies to several types of high-dimensional time series from neuroscience experiments.

<div class="research-meta">
<strong>People:</strong> Yuri Gardinazzi and Ana Fló<br>
<strong>Papers:</strong> <a href="https://proceedings.mlr.press/v325/gardinazzi26b.html">Zigzag Persistence of Neural Responses to Time-Varying Stimuli</a>
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
