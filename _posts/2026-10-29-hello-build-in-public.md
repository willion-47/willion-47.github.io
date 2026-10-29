---
layout: post
title: 开张：在这里 build in public
date: 2026-10-29 20:00:00+0800
description: 这个博客会写什么，以及为什么要公开记录
tags: build-in-public
categories: notes
related_posts: false
---

这是这个博客的第一篇文章。

## 为什么要写

学东西的时候，只读不写很容易变成“看过了”。把笔记整理成文章、公开出来，一方面逼自己真正想清楚，另一方面也让别人知道我在做什么，说不定就能遇到一起讨论的人。

## 会写什么

- **ML 理论笔记**：最近在学 ScaledGD 的收敛分析。它的更新可以看成给梯度下降加了一个预条件：

$$
L_{t+1} = L_t - \eta \, \nabla_L f(L_t, R_t) \left(R_t^\top R_t\right)^{-1}, \qquad
R_{t+1} = R_t - \eta \, \nabla_R f(L_t, R_t) \left(L_t^\top L_t\right)^{-1}.
$$

  之后会把证明思路一步步写下来。

- **论文笔记**：CLIP、LLaMA 等经典工作，每篇一页。
- **周报精选**：每周挑几条 AI 进展，写下自己的看法。
- **项目记录**：做项目时踩过的坑和学到的东西。

欢迎常来看看。
