---
layout: page
permalink: /research/
title: research
description: Research themes and current directions
nav: true
nav_order: 3.5
---

## Geometry and Topology of Large Language Models

We study the internal representations of transformer models using tools from geometry and topological data analysis. By treating token embeddings as evolving point clouds across layers, we characterize how models organize and process information. This geometric perspective reveals interpretable structure in the latent space and provides practical tools for model interpretability and safety. Applications include pre-output monitoring, layer pruning, and understanding uncertainty propagation in neural networks.

---

## Topological Analysis of Neural Dynamics

We develop methods to characterize temporal evolution in neural population recordings using persistent homology. By tracking topological features (loops, connected components) in time-varying activity patterns, we extract compact representations of spatiotemporal dynamics. This framework applies to several types of high-dimensional time series from neuroscience experiments.

---

## Learning Optimal Topological Summaries

Applying topological data analysis requires choosing filtrations and vectorization schemes. We introduce methods to learn these components by maximizing relevant information about the system. This enables automated, task-specific optimization of the topological pipeline for scientific inference problems. The framework is implemented in an open-source library and applies to point clouds, fields, and time series.

---

## Bayesian Inference for Spectroscopy

We develop Bayesian methods for feature extraction from X-ray absorption and other spectroscopic data. By fitting physically motivated forward models with full uncertainty quantification, we enable robust analysis of operando measurements where traditional baseline subtraction fails. The approach combines objective model selection via information criteria with MCMC posterior sampling to provide interpretable, statistically rigorous spectral decomposition.
