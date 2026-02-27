---
title: "Learning Triton One Kernel at a Time: Softmax"
summary: "Published on Towards Data Science"
date: 2025-11-23
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

In the [previous article](https://towardsdatascience.com/learning-triton-one-kernel-at-a-time-matrix-multiplication/) of this series, we covered a ubiquitous operation in all fields of computer science: matrix multiplication. It is heavily used in neural networks to compute the activation of linear layers. However, activations on their own are difficult to interpret, since their values and statistics (mean, variance, min-max amplitude) can vary wildly from layer to layer. This is one of the reasons why we use activation functions, for example the logistic function (aka sigmoid) which projects any real number in the [0; 1] range.

The softmax function, also known as the normalised exponential function, is a multi-dimensional generalisation of the sigmoid. It converts a vector of raw scores (logits) into a probability distribution over M classes. We can interpret it as a weighted average that behaves as a smooth function and can be conveniently differentiated. It is a crucial component of dot-product attention, language modeling, and multinomial logistic regression.

In this article, we’ll cover:
- Implementing an efficient softmax kernel in Triton.
- Implementing the backward pass (autograd).
- Optimisation: cache modifiers and auto-tuning.

Read the full article on [**Towards Data Science**](https://towardsdatascience.com/a-gentle-introduction-to-deep-reinforcement-learning-in-jax-c1e45a179b92/)!