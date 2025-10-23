---
title: Paper
permalink: /paper/
---

## WorldMemBench: evaluating memory in world models

Recent advancements in video generation technology have significantly enhanced the creation of high-fidelity, realistic content, laying a robust foundation for developing sophisticated world models. These models facilitate progress in domains such as autonomous driving, embodied intelligence, and model-based reinforcement learning by generating complex, diverse virtual scenarios. However, as research on world models intensifies, the requirements for virtual environment generation grow more stringent. An exceptional world model must exhibit strong memory capabilities, enabling rapid generalization across diverse action spaces and long-term inference based on given video contexts, while maintaining scene consistency and long-term stability. Furthermore, it should effectively prevent the generation of fictitious structures, content inconsistent with prior observations, or visually incoherent artifacts to achieve high-quality video synthesis and reliable dynamic prediction.

To realize this vision, it is imperative to establish a robust evaluation benchmark system to systematically assess the memory capabilities of world models, yet such a standard is currently lacking. Existing benchmarks primarily focus on evaluating the quality and realism of generated videos, often limited to first-person perspective data collected within a single action space. For instance, WorldScore decomposes scene generation into specific camera motion trajectories to assess video quality, while WorldModelBench evaluates adherence to physical laws to measure world modeling capabilities in application-driven domains. Although Lian et al. proposed a benchmark for world model memory, it is confined to scenes from the Minecraft game, lacking diversity in open-domain settings, and relies on loop-based agent data collection within a single action space, which struggles to align effectively with human behavior. Furthermore, existing world model benchmarks predominantly feature first-person perspectives, making it challenging to evaluate the ability of world models to simulate motion and poses.

We introduce WorldMemBench, a benchmark platform specifically designed to evaluate the memory capabilities of world models. Its core innovation lies in assessing scene memory and action knowledge memory from both first-person and third-person perspectives across diverse open-domain scenarios. Furthermore, the provided videos include frame-level aligned action sequences, character positions, camera positions, and image label descriptions, with data collected from multiple volunteers to cover a diverse range of human behavioral preferences as comprehensively as possible.

### What this page contains

- Dataset format and annotations (coming soon)
- Evaluation protocol and metrics (coming soon)
- Baseline results and example code (coming soon)
