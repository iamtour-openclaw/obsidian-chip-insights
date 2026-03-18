# Backside Power Delivery Creates Fab Tool, Thermal Dissipation Barriers

## 📊 基本信息
- **日期**: 2026-03-18
- **时间**: 08:00
- **来源**: Semiconductor Engineering
- **类型**: 技术分析
- **分类**: 先进制程/电源管理/晶体管技术
- **标签**: 背面电源传输、BSPDN、GAA晶体管、PowerVia

## 🔗 原文链接
- [Backside Power Delivery Creates Fab Tool, Thermal Dissipation Barriers](https://semiengineering.com/backside-power-delivery-creates-fab-tool-thermal-dissipation-barriers/)

## 📝 摘要
背面电源传输网络（BSPDN）从晶圆背面直接向先进晶体管输送电力，是一种架构变更，可加快处理器性能、减少功率损失并提高电源效率。但BSPDN也带来了许多新的制造挑战，包括晶圆减薄、nanoTSV与晶体管源/漏极的精确对准，以及将热点晶体管限制在正面和背面互连堆栈之间带来的热惩罚建模。

## 💡 关键点
- **性能提升**：BSPDN可将IR压降降低20%至30%，最大频率提升2%至6%
- **面积优化**：核心面积减少5%至15%，利用率超过90%
- **制造成本降低**：Intel 18A利用背面电源将掩模数量和步进次数减少超过40%
- **对齐挑战**：背面处理发生在严重晶圆减薄之后，需要透明对准标记和着陆垫
- **热惩罚**：imec高分辨率热模拟显示BSPDN带来的局部热惩罚高达14°C
- **GAA兼容性**：背面电源自然补充栅极环绕（GAA）器件的垂直性质

## 📈 影响分析
背面电源对芯片行业的影响：

1. **Intel 18A**：Intel已将RibbonFET晶体管和PowerVia投入生产
2. **三星计划**：在3nm节点采用GAA后，计划在2nm节点（SF2）引入背面电源
3. **台积电路线**：将在2nm节点（N2）首次引入GAA，然后在16Å节点（A16）推出Super Power Rail
4. **正面互连**：移除正面电源布线后，正面有更多布线资源可用于信号，提高可布线性
5. **嵌入内存**：据报告细胞密度改善5%至10%

---
*由芯片制造洞察收集器生成*