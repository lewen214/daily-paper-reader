---
title: Pupil size reveals the perceptual quality and effortless nature of synesthesia
title_zh: 瞳孔大小揭示联觉的感知质量及其不费力的本质
authors: "Strauch, C., Leenaars, C., Rouw, R."
date: 2026-05-22
pdf: "https://www.biorxiv.org/content/10.1101/2025.11.24.690102v3.full.pdf"
tags: ["query:pwad"]
score: 8.0
evidence: 瞳孔反应跟踪联觉颜色的亮度，表明瞳孔大小可作为感知亮度的度量
tldr: 通过对字素-颜色联觉者的瞳孔测量，发现在恒定物理刺激下瞳孔大小能可靠跟踪联觉颜色的感知亮度，且与主观报告强度成正比。该研究揭示了瞳孔响应可作为感知亮度的客观生理指标，为基于瞳孔直径的显示亮度感知模型提供了直接证据和方法基础。
source: biorxiv
selection_source: fresh_fetch
motivation: 瞳孔反应跟踪联觉颜色的亮度，表明瞳孔大小可作为感知亮度的度量。
method: 方法与实现细节请参考摘要与正文。
result: 结果与对比结论请参考摘要与正文。
conclusion: 总体而言，该工作在所述任务上展示了有效性，并提供了可复用的思路或工具。
---

## 摘要
联觉描述的是能够产生额外意识知觉的交叉过程，例如在阅读数字时看到额外的颜色。尽管现有研究关注联觉关联的机制和效应，却常常忽略了其最显著的特征：独特的感觉现象学。在此，我们引入瞳孔测量法，作为联觉颜色现象学的一种客观生理测量方法。在16名字素-颜色联觉者和两个匹配对照组中，在恒定物理视觉输入条件下，瞳孔反应追踪了联觉颜色的亮度，并与自我报告强度成比例。联觉颜色引发的瞳孔动态与实际颜色相当，从而将联觉者与非联觉者区分开来。这些反应出现得非常迅速，不可能反映想象，并与报告的颜色亮度成比例，揭示了交叉过程引发了真正的感知加工。被要求生成颜色关联的对照组，相比联觉者或未报告颜色的对照组，显示出更大的与努力相关的瞳孔扩张，为联觉不费力的本质提供了证据。因此，联觉为研究可生理测量的现象学提供了一个易于处理的人类模型。

意义声明：我们如何测量一个人实际体验到的东西？联觉，即数字等刺激可以引发如看到颜色等交叉感觉，提供了一个罕见的测试案例。在这里，我们使这种非凡的感觉变得可客观测量，并表明它具有独特的感觉特征。我们发现，即使在物理光线保持不变的情况下，瞳孔大小也能反映联觉颜色的亮度。瞳孔会因亮色而收缩，因暗色而扩张，从而揭示了知觉的质量和强度。这些反应出现迅速，且与非联觉者不同。总之，联觉为研究内部产生的感觉提供了一个易于处理的模型，而瞳孔测量法则为有意识知觉提供了一个直接、可测量的窗口。

## Abstract
Synesthesia describes cross-over processes that can generate extra conscious percepts, such as seeing additional color when reading numbers. While existing research focuses on the mechanisms and effects of synesthetic associations, it often overlooks its most distinctive feature: unique sensory phenomenology. Here, we introduce pupillometry as an objective physiological measure of synesthetic color phenomenology. Across 16 grapheme-color synesthetes and two matched control groups, pupil responses tracked the brightness of synesthetic colors under constant physical visual input, scaling with self-reported strength. Synesthetic colors elicited pupil dynamics comparable to real colors, dissociating synesthetes from non-synesthetes. These responses emerged too rapidly to reflect imagery and scaled with reported color brightness, revealing cross-over caused genuine perceptual processing. Controls required to generate color associations showed greater effort-linked pupil dilation than synesthetes or controls who did not report colors, providing evidence for the effortless nature of synesthesia. Synesthesia thus provides a tractable human model for studying physiologically measurable phenomenology.

Significance statementHow can we measure what someone actually experiences? Synesthesia, in which stimuli such as numbers can evoke cross-over sensations like seeing colors, provides a rare test case. Here we make this extraordinary sensation objectively measurable and show that it has a distinct sensory signature. We find that pupil size reflects the brightness of synesthetic colors even when physical light remains constant. Pupils constrict for bright colors and dilate for dark ones, revealing the quality and strength of the percept. These responses emerge rapidly and differ from those of non-synesthetes. Together, synesthesia provides a tractable model for studying internally generated sensations, with pupillometry offering a direct, measurable window into conscious perception.

---

## 论文详细总结（自动生成）

### 1. 论文的核心问题与整体含义

- **研究问题**：如何客观地测量联觉（synesthesia）中主观的“额外”感知现象（如看到数字时自动出现颜色）？传统的联觉研究主要依赖主观报告和行为指标，但缺乏一种能直接反映其感官现象学（phenomenology）的客观生理测量。
- **整体含义**：该研究提出瞳孔测量法（pupillometry）可作为联觉颜色现象学的客观生理指标，从而为意识的科学研究提供一个可量化的窗口，验证联觉的“感知真实性”与“不费力的自动性”，并拓展至内部生成的感知体验的客观测量。

### 2. 方法论

- **核心思想**：利用瞳孔光反射（pupillary light response）不仅对物理亮度敏感，也对主观感知亮度敏感的特性，推断联觉颜色的主观亮度感知。若联觉者的内部颜色体验真正具有感知特性，瞳孔会因亮色而缩小，因暗色而放大，尽管物理刺激亮度恒定。
- **关键技术与分析流程**：
    - **瞳孔数据预处理**：从1000 Hz降采样至100 Hz，换算为毫米，进行基线校正（刺激前最后50 ms均值），滤除眨眼和眼跳试次。
    - **颜色报告处理**：被试在每次试验后用滑块选取HSL（色相、亮度、饱和度）颜色，取亮度（L）作为主要预测因子。
    - **统计模型**：使用线性混合效应模型（LME），以瞳孔大小为因变量，纳入“亮度”、“耦合强度”、“投射者-联想者（PA）分数”等固定效应及随机截距。同时进行逐时间点分析以观察时间进程。
    - **努力度测量**：计算瞳孔直径的一阶导数（变化速度）以排除低频漂移，比较主动对照组（必须报告颜色）、被动对照组（无任务）和联觉者的瞳孔扩张速率。

### 3. 实验设计

- **被试**：
    - 16名字素-颜色联觉者（经严格筛选，颜色一致性高）。
    - 16名被动对照组（仅观看数字，无颜色任务）。
    - 16名主动对照组（观看数字并强制选择颜色，且报告颜色关联强度）。
    - 所有被试视力正常或矫正正常，年龄匹配。
- **范式与条件**：
    - **Block 1（主要实验阶段）**：注视屏幕中央的数字（0-9，亮度随笔画数微调以保持整体光通量恒定），持续4秒，随后用色环调整工具报告该数字对应的感知颜色。此阶段测试联觉颜色对瞳孔的影响。
    - **Block 2（仅联觉者）**：呈现以其自身平均联觉颜色为填充的色盘，中心带有与Block 1相同灰度和面积的灰块，以评估真实物理亮度引发的瞳孔反应，并与Block 1对比。
- **对比方法**：无传统benchmark，而是通过组间对比（联觉者 vs. 主动/被动对照）和条件内对比（联觉者Block 1 vs. Block 2）来验证瞳孔反应是否由联觉颜色感知引起。

### 4. 资源与算力

- 文中**未提及** GPU型号、数量、训练时长等算力信息。分析使用Python和R的自定义脚本，未涉及大规模深度学习模型，因此对算力需求较低。

### 5. 实验数量与充分性

- **实验数量**：
    - 主要分析：Block 1共5760个试次（1920/组），Block 2共800个试次（仅联觉者）。
    - 组间比较：3个组之间的瞳孔大小、一致性、耦合强度等统计检验。
    - 逐时间点LME分析：探索预测因子在全时间窗的影响。
    - 努力度分析：通过瞳孔变化速度比较组间差异。
    - 额外分析：颜色一致性、PA分数的调节作用，以及物理/联觉颜色反应延迟对比。
- **充分性与客观公平性**：
    - 实验设计严谨：匹配了物理亮度（数字的总光通量基本相同），并设置主动+被动双对照组，排除任务本身引起的努力差异干扰。
    - 公平性：物理刺激在各组间完全一致；主动对照组也执行颜色报告任务，直接与联觉者比较；统计分析纳入个体差异（随机截距）。
    - 样本量相对充足，但联觉者样本仍为小型特殊群体（16人），可能限制效应估计的精确性。实验覆盖了主要的对比维度，较为充分。

### 6. 主要结论与发现

- **瞳孔大小客观反映联觉颜色的亮度**：联觉者在观看恒定亮度的数字时，瞳孔随其报告颜色的主观亮度而变化：亮色导致收缩，暗色导致扩张；非联觉者的瞳孔未表现出此模式。
- **感知真实性**：联觉颜色引发瞳孔动态与实际物理颜色相似，且其时间进程极快（约870 ms开始显著），排除了主动想象的可能（生成想象通常需更久且伴随努力性瞳孔扩张）。
- **反应强度与主观体验耦合**：瞳孔反应幅度与个体报告的形素-颜色耦合强度及投射倾向（PA分数）呈正相关。
- **联觉的不费力性**：主动对照组在报告颜色时表现出显著的任务引发瞳孔扩张（反映心理努力），而联觉者在同等任务下瞳孔扩张与无任务的被动对照组无差异，证明联觉体验是自动、不费力的。

### 7. 优点

- **创新性**：首次直接使用瞳孔测量法客观、量化联觉的主观色彩体验，突破了仅依赖行为测试和神经影像的局限。
- **方法论严谨**：
    - 严格控制物理亮度恒定，排除外部光线干扰。
    - 双对照组设计分离任务努力与联觉现象。
    - 使用线性混合模型充分考虑数据结构和所有试次，而非仅中位数划分。
- **多维度验证**：从感知亮度、个体差异（耦合强度、PA）、时间进程、努力程度等多角度交叉验证，证据链完整。
- **应用前景广阔**：不仅推进联觉研究，更为意识、内部生成感知、跨模态预测编码等领域提供了一种可推广的客观生理标记。

### 8. 不足与局限

- **样本限制**：联觉者仅16人，属于特定类型（字素-颜色），研究结论向其他联觉类型推广需谨慎。
- **颜色空间简化**：仅分析亮度维度，对色彩信息（色调、饱和度）的生理标记未探讨。
- **机制推论有限**：瞳孔反应证明联觉影响早期感官处理，但无法精确定位神经通路（如反馈连接）。时间估计基于假设内外亮度反应延迟相同，可能存在微小偏差。
- **未排除的混淆因素**：尽管物理亮度匹配，数字形状的细微差异仍可能影响瞳孔，但已通过亮度校正减轻；未记录基线情绪或唤醒度波动对瞳孔的可能影响。
- **因果方向**：瞳孔大小受多种因素（例如注意、唤醒）影响，虽然设计合理，但无法完全排除这些高级认知过程的贡献。
- **缺乏主动对照组的Block 2**：未测试主动对照组对真实物理颜色的瞳孔反应，无法进行直接比较。

（完）
