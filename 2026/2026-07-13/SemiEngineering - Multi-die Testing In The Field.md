# Multi-die Testing In The Field Must Build On Established Test Methodologies

## 📊 基本信息
- **日期**: 2026-07-07
- **时间**: 00:00
- **来源**: SemiEngineering
- **类型**: 技术深度分析
- **分类**: 芯片测试 / 多芯片 / 可靠性
- **标签**: `#芯片测试` `#DFT` `#系统级测试` `#可靠性` `#chiplets` `#PCIe` `#SLM` `#SemiEngineering` `#数据中心`

## 🔗 原文链接
- [Multi-die Testing In The Field Must Build On Established Test Methodologies](https://semiengineering.com/multi-die-testing-in-the-field-must-build-on-established-test-methodologies/)

## 📝 摘要
AI 革命的推进速度已远超 IC 行业对多芯片系统进行充分测试的能力。2.5D 系统的大规模采用和 3D-IC 的发展推动了现场系统内测试（in-system testing）的迫切需求——设备在初始阶段"工作正常"已不再保证其整个生命周期的可靠性。文章详细探讨了多芯片系统面临的新型测试挑战：silent data errors（静默数据错误）、latent defects（潜伏缺陷）和 intermittent defects（间歇性缺陷）在现场环境中频发，而制造阶段的测试难以完全覆盖。PCIe 高速接口正在被重新用于芯片测试，从 2005 年的通用扩展总线演变为今天的测试通信骨干。同时，UCIe、AIB、HBM4 等新标准提供了备用 lane/pin 机制，配合 on-chip monitors 和 SLM（芯片生命周期管理），实现芯片的"自修复"能力。

## 💡 关键点
- **制造测试不够用**：晶体管应力不足导致潜伏缺陷在 AI 训练等长期运行中暴露为静默数据错误
- **现场测试三大关键窗口**：上电时、运行时、断电时——掉电/启停阶段故障最容易被忽视
- **PCIe 的"第二人生"**：从通用扩展总线演变为芯片测试高速通信骨干，替代慢速 GPIO
- **芯片自修复**：结合 SLM 数据 + DFT + UCIe/AIB/HBM4 备用 lane/pin 实现现场自动故障切换
- **冗余策略**：双模冗余（DMR）、三模冗余（TMR）架构允许故障 flip-flop 被"投票"排除
- **老化预测**：proteanTecs 等公司已在使用时间-故障模型预测数据中心环境的可靠性退化
- **microbump 测试难题**：微凸点太小无法直接探测，需用牺牲测试焊盘

## 🏢 涉及行业巨头
- **Siemens EDA (Tessent)** — Peter Orlando（DFT 产品总监）、Nilanjan Mukherjee（工程 VP），Silicon Lifecycle Solutions
- **Synopsys** — Adam Cron（杰出架构师），讨论自修复能力；Ash Patel（产品营销总监），PCIe 重新用于测试
- **proteanTecs** — Eidan Mendelsohn（工程 VP），时间-故障建模与预测分析

## 📈 影响分析
(1) 随着 AI 芯片的复杂度持续攀升，"出厂即丢弃"的传统测试模式已不可持续，芯片全生命周期管理（SLM）将成为行业标配；(2) PCIe 重用于测试意味着高速接口 IP 的标准制定需考虑测试需求，对 EDA 工具和 ATE 设备供应商提出新要求；(3) chiplet 的"现场可修复"能力将成为数据中心/AI 芯片的关键卖点，推动芯片冗余设计和备用通路的经济性研究；(4) 对于测试设备厂商（Advantest、Teradyne 等），系统级测试（SLT）的需求将继续增长，尤其是在 AI 训练芯片和自动驾驶芯片领域；(5) 静默数据错误（SDC）是 AI 数据中心面临的"隐形杀手"，对芯片可靠性提出了前所未有的要求。

---
*由芯片制造洞察收集器自动生成 · 2026-07-13*
