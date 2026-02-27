---
title: "Cutting LLM Memory by 84%: A Deep Dive into Fused Kernels"
summary: "Published on Towards Data Science"
date: 2026-01-16
math: true
authors:
  - admin
tags:
  - Triton
  - PyTorch
  - GPU Programming
image:
  caption: ''
---

## Summary

If you’ve ever trained or fine-tuned an LLM, you’ve likely hit a wall at the very last step: the Cross-Entropy Loss.

The culprit is the logit bottleneck. To predict the next token, we project a hidden state into a massive vocabulary space. For Llama 3 (128,256 tokens), the weight matrix alone is over 525 million parameters. While that’s only ~1GB in bfloat16, the intermediate logit tensor is the real issue. For large batches, it can easily exceed 80GB of VRAM just to compute a single scalar loss.

Optimising this layer is how libraries like Unsloth and Liger-Kernel achieve such massive memory reductions. In this article, we’ll build a fused Linear + Cross Entropy kernel from scratch in Triton. We will derive the math and implement a tiled forward and backward pass that slashes peak memory usage by 84%.

Read the full article on [**Towards Data Science**](https://towardsdatascience.com/cutting-llm-memory-by-84-a-deep-dive-into-fused-kernels/)!