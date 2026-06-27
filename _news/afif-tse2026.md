---
layout: post
title: "Our paper TriagerX: Dual Transformers for Bug Triaging Tasks with Content and Interaction Based Rankings has been accepted to IEEE Transactions on Software Engineering (TSE)."
date: 2026-04-16
inline: false
related_posts: false
---

## TriagerX: Dual Transformers for Bug Triaging Tasks with Content and Interaction Based Rankings

Authors: [Md Afif Al Mamun](https://afif.me), [Gias Uddin](https://giasuddin.ca), Lan Xia, Longyu Zhang

## Abstract

Pretrained Language Models or PLMs are transformer-based architectures that can be used in bug triaging tasks. PLMs can better capture token semantics than traditional Machine Learning (ML) models that rely on statistical features (e.g., TF-IDF, bag of words). However, PLMs may still attend to less relevant tokens in a bug report, which can impact their effectiveness. In addition, the model can be sub-optimal with its recommendations when the interaction history of developers around similar bugs is not taken into account. We designed TriagerX to address these limitations. First, to assess token semantics more reliably, we leverage a dual-transformer architecture. Unlike current state-of-the-art (SOTA) baselines that employ a single transformer architecture, TriagerX collects recommendations from two transformers with each offering recommendations via its last three layers. This setup generates a robust content-based ranking of candidate developers. TriagerX then refines this ranking by employing a novel interaction-based ranking methodology, which considers developers' historical interactions with similar fixed bugs. Across five datasets, TriagerX surpasses all nine transformer-based methods, including SOTA baselines, often improving Top-1 and Top-3 developer recommendation accuracy by over 10%. We worked with our large industry partner to successfully deploy TriagerX in their development environment. The partner required both developer and component recommendations, with components acting as proxies for team assignments-particularly useful in cases of developer turnover or team changes. We trained TriagerX on the partner's dataset for both tasks, and it outperformed SOTA baselines by up to 10% for component recommendations and 54% for developer recommendations.

Links: [Arxiv](https://arxiv.org/abs/2508.16860), [PDF](TSE_TriagerX.pdf)
