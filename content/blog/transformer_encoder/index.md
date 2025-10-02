---
title: "Implementing a Transformer Encoder from Scratch with JAX and Haiku 🤖"
summary: "Published on Towards Data Science"
date: 2023-11-07
math: true
authors:
  - admin
tags:
  - Natural Language Processing
  - JAX
  - Large Language Models
  - Transformers
image:
  caption: ''
---

## Summary

Introduced in 2017 in the seminal paper "**Attention is all you need**", the **Transformer** architecture is arguably one of the most impactful breakthroughs in recent Deep Learning history, enabling the rise of **large language models** and even finding use in fields such as computer vision.

Succeeding to former state-of-the-art architectures relying on recurrence such as Long Short-Term Memory (LSTM) networks or Gated Recurrent Units (GRU), Transformers introduce the concept of **self-attention**, coupled with an **encoder/decoder architecture**.

In this article, we’ll implement the first half of a Transformer, the encoder, **from scratch and step by step**. 

We’ll go over each of the blocks that make up the encoder and learn to implement them efficiently. In particular, the outline of this article contains:

- The Embedding Layer and Positional Encodings
- Multi-Head Attention
- Residual Connections and Layer Normalization
- Position-wise Feed-Forward Networks


Read the full article on [**Towards Data Science**](https://towardsdatascience.com/implementing-a-transformer-encoder-from-scratch-with-jax-and-haiku-791d31b4f0dd/)!