# Backside Power Delivery Creates Fab Tool, Thermal Dissipation Barriers

## 📊 基本信息
- **日期**: 2026-03-19
- **时间**: 08:00
- **来源**: Semiconductor Engineering
- **类型**: 技术报告
- **分类**: 先进制程/背面供电/晶圆制造
- **标签**: BSPDN、PowerVia、2nm制程、热管理

## 🔗 原文链接
- [Backside Power Delivery Creates Fab Tool, Thermal Dissipation Barriers](https://semiengineering.com/backside-power-delivery-creates-fab-tool-thermal-dissipation-barriers/)

## 📝 摘要
背面供电网络（BSPDN）将电力直接从晶圆背面输送到先进制程晶体管，是一种架构变更，可加快处理器性能、减少功率损耗并提高电源效率。但BSPDN也带来了许多新挑战，包括通孔对准、互连、热散逸等问题。Intel已将其18A制程（RibbonFET晶体管和PowerVia）投入生产；三星计划在2nm节点引入背面供电；台积电将在2nm引入GAA，并在16Å节点（A16）推出Super Power Rail。

## 💡 关键点
- **性能提升**：BSPDN使IR压降减少20-30%，最大频率提升2-6%，核心面积减少5-15%
- **三大挑战**：硅衬底几乎完全移除、对准精度、热预算约束
- **对准精度**：背面通孔与正面晶体管的源极/漏极对准，overlay budget约10nm
- **热问题**：imec高分辨率热模拟显示局部热 penalty 可高达14°C
- **GAA协同**：GAA纳米片晶体管和BPDN需共同设计，因为器件堆叠直接定义背面供电通孔的"着陆目标"
- **成本优化**：单次直接光刻降低掩模数量和步进 count 超过40%

## 📈 影响分析
背面供电对半导体制造的影响：

1. **设备制造**：需要新的fab工具处理薄晶圆（从775µm研磨到数十微米）
2. **材料选择**：评估氮化铝(AlN)等材料用于永久熔合键合以改善热传导
3. **对准技术**：双面对准、专用正面对准标记、 engineered etch-stops
4. **应力管理**：晶圆键合和剧烈研磨产生的应力和翘曲
5. **设计流程**：place-and-route流程修改，分离电源和信号布线
6. **应用场景**：最适合HPC、AI加速器、游戏芯片、图形处理器等高功率工作负载

---
*由芯片制造洞察收集器生成*