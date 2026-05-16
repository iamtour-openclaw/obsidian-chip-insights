# AI 代理自主设计 RISC-V 芯片完整核心：Verkor.io 里程碑

## 📊 基本信息
- **日期**: 2026-05-15
- **来源**: IEEE Spectrum
- **类型**: 技术报道
- **分类**: AI芯片设计 / EDA工具
- **标签**: #AI芯片设计 #RISC-V #Verkor #EDA #AgenticAI #DesignConductor

## 🔗 原文链接
- [How Agentic AI Chip Design Built a Full RISC-V Core](https://spectrum.ieee.org/ai-chip-design)

## 📝 摘要
AI芯片设计初创公司 Verkor.io 宣布了一项里程碑成就：其代理式AI系统 Design Conductor 完全自主设计了一个名为 VerCore 的 RISC-V CPU 核心，主频达1.5GHz，性能与2011年英特尔 Celeron 相当。Design Conductor 并非单一AI模型，而是一个LLM编排框架，模拟人类芯片架构师的完整设计流程：规格分析、RTL编写调试、供电/信号时序/布局迭代。从219字的规格说明到最终GDSII文件，仅用了12小时。

## 💡 关键点
- **完全自主设计**：AI系统从219字规格说明出发，12小时内完成完整CPU核心设计，无需人工干预
- **性能对标**：VerCore 核心频率1.48GHz，CoreMark得分3,261，性能与英特尔Celeron SU2300（2011年）相当
- **技术架构**：基于 RISC-V 指令集架构（开放标准ISA），使用 ASAP7 7nm学术PDK完成布局
- **工具链**：Design Conductor 编排了多LLM子代理，调用 OpenROAD 等开源EDA工具完成布局布线
- **生成文件**：输出标准 GDSII 文件，可在现有EDA软件中流片使用
- **未来计划**：Verkor 计划在2026年DAC大会上展示FPGA实现，并开源设计文件

## 📈 影响分析
VerCore 的意义不在于性能超越 Intel/AMD，而在于AI首次完整自主完成了CPU核心的端到端设计。这表明芯片设计的门槛正在被大幅降低——无需庞大的EDA软件授权团队，无需数年经验的架构师，AI在12小时内可以完成一个可用核心。这与 Synopsys、Cadence 的AI辅助工具形成对比：Verkor 追求的是从规格到完成的完全自治。如果这种能力持续提升，可能在3-5年内重塑芯片设计行业格局，尤其是RISC-V生态的定制芯片市场。

---
*由芯片制造洞察收集器生成*
