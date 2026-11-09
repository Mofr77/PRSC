# PRSC: Part-aware Reasoning for Semantic Correspondence

> **Can VLMs reason about semantic identity and establish precise point-level correspondence across different instances?**

## Overview

PRSC explores the potential of Vision-Language Models (VLMs) for semantic correspondence.

Given a source image, a query point, and a target image, the goal is to identify the semantic meaning of the source point and locate its corresponding position in the target image.

Instead of directly predicting coordinates based on visual similarity, we explore a part-aware reasoning paradigm:

- **Semantic Understanding:** Identify the object part and semantic identity of the source point.
- **Part-aware Reasoning:** Understand its relative position and local structural context.
- **Cross-instance Matching:** Find the corresponding semantic part in the target image.
- **Precise Localization:** Predict the target point coordinates.

## Research Direction

We aim to investigate how VLMs can leverage semantic understanding and spatial reasoning to improve fine-grained visual correspondence, potentially combined with supervised fine-tuning and reinforcement learning.

## Benchmarks

- SPair-71k
- PF-PASCAL
- AP-10K

## Status

<sub>Research in progress. Methodology and implementation are under exploration.</sub>
