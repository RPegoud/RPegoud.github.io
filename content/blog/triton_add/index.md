---
title: "Learning Triton One Kernel At a Time: Vector Addition"
summary: "Published on Towards Data Science"
date: 2025-09-27
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

In the era of billion-parameter models, a little optimisation goes a long way. Models like GPT4 cost more than $100 millions to train, which makes a 1% efficiency gain worth over a million dollars. A powerful way to optimise the efficiency of machine learning models is by writing some of their components directly on the GPU. Now if you’re anything like me, the simple mention of CUDA kernels is enough to send chills down your spine, as they are notoriously complex to write and debug.

Fortunately, OpenAI released Triton in 2021, a new language and compiler abstracting away much of CUDA’s complexity and allowing less experienced practitioners to write performant kernels. A notable example is Unsloth, an LLM-training service that promises 30x faster training with 60% less memory usage, all thanks to replacing layers written in PyTorch with Triton kernels.

In this tutorial series, we’ll learn the basics of GPU architecture and how to implement high-performance Triton kernels! All the code presented in this series will be available at https://github.com/RPegoud/Triton-Kernels.

Read the full article on [**Towards Data Science**](https://towardsdatascience.com/learning-triton-one-kernel-at-a-time-vector-addition/)!