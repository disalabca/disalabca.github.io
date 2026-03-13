---
layout: post
title: Our paper <b>Evaluating the Environmental Impact of using Small Language Models and Prompt Engineering for Code Generation</b> has been accepted to EASE 2026.
date: 2026-03-12
inline: false
related_posts: false
---

## Paper Title: Evaluating the Environmental Impact of using Small Language Models and Prompt Engineering for Code Generation

Authors: [Md Afif Al Mamun](https://afif.me), Sayan Nath, Gias Uddin, Novarun Deb

## Abstract

The shift from cloud-hosted Large Language Models (LLMs) to locally deployed open-source Small Language Models (SLMs) has democratized AI-assisted coding; however, it has also decentralized the environmental footprint of AI. While prompting strategies—such as Chain-of-Thought and ReAct—serve as external mechanisms for optimizing code generation without modifying model parameters, their impact on energy consumption and carbon emissions remains largely invisible to developers. This paper presents the first systematic empirical study investigating how different prompt engineering strategies in SLM-based code generation impact code generation accuracy alongside sustainability factors. We evaluate six prominent prompting strategies across 11 open-source models (ranging from 1B to 34B parameters) using the HumanEval+ and MBPP+ benchmarks. By measuring Pass@1 accuracy alongside energy (kWh), carbon emissions (kgCO$_2$eq), and inference latency, we reveal that sustainability often decouples from accuracy, allowing significant environmental optimizations without sacrificing performance. Our findings indicate that Chain-of-Thought, being a simpler prompting technique, can provide a near-optimal balance between reasoning capability and energy efficiency. Conversely, multi-sampling strategies often incur disproportionate costs for marginal gains. Finally, we identify grid carbon intensity as the dominant factor in deployment-time emissions, highlighting the need for practitioners to consider regional energy profiles. This work provides a quantitative foundation for "green" prompt engineering, enabling developers to align high-performance code generation with ecological responsibility.
