# Designing Chips In The Context Of Rapidly Evolving AI

## 📊 基本信息
- **日期**: 2026-05-18
- **时间**: 07:45
- **来源**: Semiconductor Engineering
- **类型**: 专家讨论
- **分类**: AI芯片设计
- **标签**: 边缘AI, 芯片架构, AI代理, 内存层次, PPA

## 🔗 原文链接
- [Designing Chips In The Context Of Rapidly Evolving AI](https://semiengineering.com/designing-chips-in-the-context-of-rapidly-evolving-ai/)

## 📝 摘要
本文是 Semiconductor Engineering 组织的专家圆桌讨论，参与者来自 Arm、Cadence、Expedera、Mixel、Quadric、Rambus、Siemens EDA、Synopsys 等公司。讨论核心是：AI 模型的快速迭代（多模态、MoE、新格式）要求芯片架构具备可编程性和足够的余量。

## 💡 关键点
- 代理型边缘 AI 驱动长寿命、工具介导的循环，对算力、token 和内存有可变需求
- 边缘 PPA 受内存层次结构和数据移动主导，迫使严格的功能筛选和鲁棒的 RAS
- 快速模型更迭需要可编程、有余量的计算、互连和运行时
- Agentic AI 与生成式 AI 的关键区别：自主性、工具调用能力、内存访问、迭代规划
- 边缘代理目前涵盖感知、推理，以及机器人的规划和执行
- Rambus 指出边缘 AI 的整体系统协同工作比单纯的神经网络更重要

## 📈 影响分析
AI 模型的快速演进对芯片设计提出了前所未有的灵活性要求。芯片架构需要与 AI 算法共同进化，而非一次性地为固定模型优化。这意味着 AI 芯片设计需要更多地关注可编程性和架构余量，而非单纯的峰值算力。这对边缘 AI 芯片设计尤其重要，因为边缘场景下的模型变化更加频繁且多样化。

---
*由芯片制造洞察收集器生成*
