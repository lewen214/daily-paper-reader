---
title: Luminance-corrected Pupillometry for Reliable Effort-tracking in Dynamic Environments
title_zh: 亮度校正的瞳孔测量法用于动态环境中可靠的努力追踪
authors: "Cai, Y., Naber, M., Van der Stigchel, S., Strauch, C."
date: 2026-05-31
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.29.728653v2.full.pdf"
tags: ["query:pwad"]
score: 6.0
evidence: 采用亮度校正的瞳孔测量法，与涉及瞳孔直径的感知亮度模型相关
tldr: 瞳孔测量可客观反映努力程度，但亮度变化干扰其准确性，尤其在动态场景下受限。本研究提出开放动态瞳孔系统测量模型(Open-DPSM)，校正整体亮度及瞬间变化。实验表明，校正后动态环境下努力辨别力显著提升，略优于准确率和NASA-TLX评分，且三模态结合(AUC=0.98)效果最佳。该工作为复杂刺激下的精细努力追踪奠定基础，并提供教程助力应用。
source: biorxiv
selection_source: fresh_fetch
motivation: 动态视觉环境中亮度变化严重干扰瞳孔对努力的反映，制约瞳孔测量在现实场景的可靠追踪。
method: 采用Open-DPSM模型校正整体和瞬时亮度效应，通过听觉n-back任务搭配恒定或动态驾驶视频刺激进行验证。
result: 亮度校正后努力辨别力显著增强，校正瞳孔测量略优于行为与主观指标，三模态融合分类AUC达0.98。
conclusion: 验证了亮度校正瞳孔测量在动态环境中的有效性，为多模态努力评估提供基础，并附教程指导应用。
---

## 摘要
瞳孔测量法提供了一种客观衡量跨领域努力的方式。然而，瞳孔大小受到亮度变化的强烈影响，这可能掩盖与努力相关的效应，并限制其应用于具有动态视觉输入的大多数场景。我们在此介绍并验证了一种克服该问题的方法。为此，参与者在观看恒定视觉输入或动态驾驶电影片段的同时，执行了难度不同的听觉n-back任务。努力通过生理学（瞳孔大小）、行为学（准确度）和主观（NASA-TLX）进行评估。准确度、问卷评分和瞳孔大小在会话层面进行分析，而瞳孔测量还提供了连续的时间分辨信息。正如预期，瞳孔测量追踪了努力的差异，但在动态视觉输入下其区分能力显著降低。使用动态、可解释且开源的建模程序（Open-DPSM）校正总体亮度和瞬时亮度变化的影响，在聚合和时间分辨层面均显著提升了对努力的区分能力。在聚合层面，亮度校正的瞳孔测量法略优于准确度和NASA-TLX。结合所有三种测量方法产生了最高的分类性能（AUC=0.98），支持了努力具有多面性且最好通过多模态捕捉的观点。这些发现为在基础研究和应用研究中利用复杂动态刺激进行精细的努力与唤醒生理追踪奠定了实践基础。本文还提供了一个教程部分，指导研究人员使用此验证方法在动态观看环境中对自己的瞳孔测量数据应用亮度校正。

## Abstract
Pupillometry provides an objective way to index effort across domains. However, pupil size is strongly affected by luminance changes, which can obscure effort-related effects, and limit its use in most applied scenarios with dynamic visual input. We here introduce and validate a method to overcome this problem. To this end, participants performed an auditory n-back task of differing difficulty while viewing either constant visual input or dynamic driving movie clips. Effort was assessed physiologically (pupil size), behaviorally (accuracy), and subjectively (NASA-TLX). Accuracy, questionnaire scores, and pupil size were analyzed at the session level, while pupillometry additionally provided continuous time-resolved information. As expected, pupillometry tracked differences in effort, but its discriminability was substantially reduced under dynamic visual input. Correcting for the effects of overall luminance and moment-to-moment luminance changes using a dynamic, explainable, and open-source modeling procedure (Open-DPSM) considerably improved effort discriminability on both aggregate and time-resolved levels. At the aggregate level, luminance-corrected pupillometry slightly outperformed accuracy and NASA-TLX. Combining all three measures yielded the highest classification performance (AUC = 0.98), supporting the view that effort is multifaceted and best captured multimodally. These findings establish a practical basis for fine-grained physiological tracking of effort and arousal in both fundamental and applied research using complex, dynamic stimuli. A tutorial section guides researchers in applying luminance correction to their own pupillometric data in dynamic viewing environments using the here validated approach.