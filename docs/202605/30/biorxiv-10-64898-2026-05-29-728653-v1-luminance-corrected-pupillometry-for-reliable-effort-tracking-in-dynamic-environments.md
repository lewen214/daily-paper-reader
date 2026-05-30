---
title: Luminance-corrected Pupillometry for Reliable Effort-tracking in Dynamic Environments
title_zh: 亮度校正的瞳孔测量法用于动态环境中可靠的努力追踪
authors: "Cai, Y., Naber, M., Van der Stigchel, S., Strauch, C."
date: 2026-05-29
pdf: "https://www.biorxiv.org/content/10.64898/2026.05.29.728653v1.full.pdf"
tags: ["query:pwad"]
score: 7.0
evidence: 亮度校正瞳孔测量法用于从亮度引起的瞳孔变化中分离努力
tldr: 瞳孔测量法能客观追踪努力，但瞳孔大小受亮度变化严重干扰，在动态视觉场景中应用受限。本文提出开源、可解释的动态瞳孔测量建模方法Open-DPSM，校正整体与瞬时亮度效应。在听觉n-back任务与动态驾驶视频的实验中，校正后瞳孔测量在聚合和时间解析层面的努力鉴别力大幅提升，且略优于主观问卷和行为准确率。多模态融合（瞳孔、行为、主观）的分类性能最高（AUC=0.98），为复杂动态环境下的细粒度努力追踪奠定了实用基础，并附有教程指导应用。
source: biorxiv
selection_source: fresh_fetch
motivation: 瞳孔测量努力追踪受亮度变化干扰，限制其在动态视觉环境中的可靠性，亟需有效校正方法。
method: 在听觉n-back任务中搭配恒定或动态视觉输入，使用Open-DPSM动态建模校正亮度影响，并对比多模态指标。
result: 校正后瞳孔测量努力鉴别力显著提升，在聚合层面略优于准确率和NASA-TLX，三模态结合AUC达0.98。
conclusion: 亮度校正瞳孔测量实现动态环境下的可靠努力追踪，多模态结合效果最佳，并提供开源工具。
---

## 摘要
瞳孔测量法提供了一种客观的方法来跨领域指示努力程度。然而，瞳孔大小受到亮度变化的强烈影响，这会掩盖与努力相关的效应，并限制其在大多数具有动态视觉输入的应用场景中的使用。我们在此介绍并验证了一种方法来克服这个问题。为此，参与者在观看恒定视觉输入或动态驾驶视频片段的同时，执行了不同难度的听觉n-back任务。努力程度通过生理学（瞳孔大小）、行为学（准确率）和主观（NASA-TLX）方式评估。准确率、问卷分数和瞳孔大小在会话层面进行分析，而瞳孔测量法还提供了连续的实时信息。正如预期，瞳孔测量法追踪了努力程度的差异，但在动态视觉输入下其辨别力显著降低。使用一个动态、可解释且开源的建模流程（Open-DPSM）对整体亮度和逐刻亮度变化的影响进行校正，大大提高了在聚合和实时层面上的努力辨别力。在聚合层面，亮度校正的瞳孔测量法略优于准确率和NASA-TLX。结合所有三种测量方法获得了最高的分类性能（AUC = 0.98），这支持了努力是多维度的，并且最好通过多模态方式捕捉的观点。这些发现为在基础和应用研究中使用复杂动态刺激进行精细的生理学努力与唤醒追踪奠定了实用基础。教程部分指导研究人员使用此处验证的方法，在动态观看环境中对其自己的瞳孔测量数据进行亮度校正。

## Abstract
Pupillometry provides an objective way to index effort across domains. However, pupil size is strongly affected by luminance changes, which can obscure effort-related effects, and limit its use in most applied scenarios with dynamic visual input. We here introduce and validate a method to overcome this problem. To this end, participants performed an auditory n-back task of differing difficulty while viewing either constant visual input or dynamic driving movie clips. Effort was assessed physiologically (pupil size), behaviorally (accuracy), and subjectively (NASA-TLX). Accuracy, questionnaire scores, and pupil size were analyzed at the session level, while pupillometry additionally provided continuous time-resolved information. As expected, pupillometry tracked differences in effort, but its discriminability was substantially reduced under dynamic visual input. Correcting for the effects of overall luminance and moment-to-moment luminance changes using a dynamic, explainable, and open-source modeling procedure (Open-DPSM) considerably improved effort discriminability on both aggregate and time-resolved levels. At the aggregate level, luminance-corrected pupillometry slightly outperformed accuracy and NASA-TLX. Combining all three measures yielded the highest classification performance (AUC = 0.98), supporting the view that effort is multifaceted and best captured multimodally. These findings establish a practical basis for fine-grained physiological tracking of effort and arousal in both fundamental and applied research using complex, dynamic stimuli. A tutorial section guides researchers in applying luminance correction to their own pupillometric data in dynamic viewing environments using the here validated approach.