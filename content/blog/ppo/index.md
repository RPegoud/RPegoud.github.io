---
title: "A Practical Guide to Proximal Policy Optimization in JAX 📈"
summary: "Published on Towards Data Science"
date: 2024-05-01
math: true
authors:
  - admin
tags:
  - Reinforcement Learning
  - Proximal Policy Optimisation
  - JAX
image:
  caption: ''
---

## Summary

Since its publication in a 2017 paper by OpenAI, __Proximal Policy Optimization__ (PPO) is widely regarded as one of the state-of-the-art algorithms in Reinforcement Learning. Indeed, PPO has demonstrated remarkable performances across various tasks, from attaining superhuman performances in Dota 2 teams to solving a Rubik’s cube with a single robotic hand while maintaining three main advantages: simplicity, stability, and sample efficiency.

However, implementing RL algorithms from scratch is notoriously _difficult_ and error-prone, given the numerous error sources and implementation details to be aware of.

In this article, we’ll focus on breaking down the clever tricks and programming concepts used in a popular implementation of PPO in JAX. Specifically, we’ll focus on the implementation featured in the __PureJaxRL__ library, developed by __Chris Lu__.

Read the full article on [**Towards Data Science**](https://towardsdatascience.com/breaking-down-state-of-the-art-ppo-implementations-in-jax-6f102c06c149/)!