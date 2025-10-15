---
title: "Learning Triton One Kernel At a Time: Matrix Multiplication"
summary: "Published on Towards Data Science"
date: 2025-10-15
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

Matrix multiplication is undoubtedly the most common operation performed by GPUs. It is the fundamental building block of linear algebra and shows up across a wide spectrum of different fields such as graphics, physics simulations and scientific computing while being ubiquitous in machine learning.

In today’s article, we’ll break down the conceptual implementation of general matrix-matrix multiplication (GEMM) while introducing several optimisation concepts such as tiling and memory coalescing. Finally, we’ll implement GEMM in Triton!

In this tutorial series, we’ll learn the basics of GPU architecture and how to implement high-performance Triton kernels! All the code presented in this series will be available at https://github.com/RPegoud/Triton-Kernels.


<video width="640" height="360" controls autoplay loop muted>
  <source src="video.mp4" type="video/mp4">
</video>

Read the full article on [**Towards Data Science**](https://towardsdatascience.com/learning-triton-one-kernel-at-a-time-matrix-multiplication/)!