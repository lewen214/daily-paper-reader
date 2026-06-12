---
title: "Pupil-DLC: an open-source deep learning pipeline for scalable, marker-less tracking of pupil dynamics across conscious and unconscious states"
title_zh: Pupil-DLC：一种开源深度学习流程，用于跨意识与无意识状态的可扩展、无标记瞳孔动态追踪
authors: "Seyfourian, P., Marks, L. C., Claar, L. D., Nahas, Y., Keating, M., Koch, C., Rembado, I."
date: 2026-06-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.01.18.700183v3.full.pdf"
tags: ["query:pwad"]
score: 7.0
evidence: 基于深度学习的瞳孔直径跟踪管道，用于可扩展的无标记瞳孔测量
tldr: 瞳孔直径是评估脑状态的重要非侵入性指标，但现有工具缺乏跨物种与条件的可扩展性。Pupil-DLC基于DeepLabCut构建开源离线管道，采用通用与个体双模型架构，在多样化小鼠数据上训练。该管道在清醒、麻醉等多种状态下均能高精度追踪瞳孔动态，且优于现有方法，并可泛化至人类。它为跨范式脑状态研究提供了可复现平台，促进小鼠与人类神经科学的转化。
source: biorxiv
selection_source: fresh_fetch
motivation: 现有瞳孔测量软件缺乏跨实验条件和物种的可扩展性与鲁棒性。
method: "基于DeepLabCut，在21,750帧手工标注小鼠视频上训练双模型（通用模型和个体模型）的离线管道。"
result: Pupil-DLC在多种状态下高保真追踪瞳孔，优于现有方法，计算效率相当，且可泛化至人类视频。
conclusion: 提供可复现、自适应的平台，量化瞳孔相关脑状态动态，桥接基础与转化神经科学。
---

## 摘要
背景：瞳孔直径是一种非侵入性脑状态生物标志物，与觉醒、注意力、认知处理和意识相关。然而，现有的瞳孔测量软件通常缺乏跨不同实验条件和物种的可扩展性和稳健性。新方法：我们推出Pupil-DLC，这是一种基于DeepLabCut的开源、离线、可扩展的无标记瞳孔追踪流程，主要针对小鼠设计。该流程在超过140个头部固定小鼠视频的21,750帧手动标注图像上进行训练，这些视频涵盖清醒和药物诱导状态（包括致幻剂和麻醉），数据集经过特意挑选以最大化瞳孔大小的变异性和模型泛化能力。Pupil-DLC采用双模型架构：通用模型（GM）用于高通量分析，个体模型（IM）用于特定会话的优化。结果：Pupil-DLC能够捕捉清醒、致幻和麻醉状态下的瞳孔动态，与真实值高度一致，并且在主动运动和安静休息期间具有同等的追踪保真度。置信度指标与人工帧质量评估一致，使得能够在准确率和保留率之间进行有原则的权衡调整。作为次要演示，Pupil-DLC无需重新训练即可扩展到未见过的、跨不同条件和帧率的人类视频，包括日光和智能手机录制。与现有方法的比较：Pupil-DLC在准确率和帧保留率上优于现有的自动化方法，同时保持与实时工具相当的计算效率。这些改进源于一种基于学习的关键点表示，该表示对瞳孔形状变化、遮挡、反射和成像伪影具有鲁棒性。GM/IM框架支持一种分层策略，以平衡通量和精度。结论：Pupil-DLC提供了一个可重复、适应性强的平台，用于量化跨实验范式和物种的瞳孔相关脑状态动态，在基础小鼠神经科学和转化人类应用之间架起了桥梁。

## Abstract
Background: Pupil diameter is a non-invasive biomarker of brain state, correlating with arousal, attention, cognitive processing, and consciousness. However, existing pupillometry software often lacks scalability and robustness across diverse experimental conditions and species. New method: We introduce Pupil-DLC, an open-source, offline, DeepLabCut-based pipeline for scalable, marker-less pupil tracking, primarily designed for mice. Trained on 21,750 manually annotated frames from over 140 videos of head-fixed mice spanning wakefulness and drug-induced states, including psychedelics and anesthesia, the dataset was deliberately selected to maximize pupil size variability and model generalization. Pupil-DLC implements a dual-model architecture: a General Model (GM) for high-throughput analysis and an Individual Model (IM) for session-specific optimization. Results: Pupil-DLC captures pupil dynamics across awake, psychedelic, and anesthetized conditions with high agreement with ground truth and equal tracking fidelity during active locomotion and quiet rest. Confidence metrics aligned with human frame quality assessments, enabling principled tuning of accuracy-retention trade-offs. As a secondary demonstration, Pupil-DLC extends to unseen human videos across diverse conditions and frame rates, including daylight and smartphone recordings, without retraining. Comparison with existing methods: Pupil-DLC outperforms existing automated methods in accuracy and frame retention while maintaining computational efficiency comparable to real-time tools. These improvements stem from a learned keypoint-based representation robust to pupil shape variability, occlusions, reflections, and imaging artifacts. The GM/IM framework supports a tiered strategy balancing throughput and precision. Conclusions: Pupil-DLC provides a reproducible, adaptable platform for quantifying pupil-linked brain state dynamics across experimental paradigms and species, bridging basic mouse neuroscience and translational human applications.