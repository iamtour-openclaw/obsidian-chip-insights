# Rethinking Chip Verification

## 📊 基本信息
- **日期**: 2026-06-29
- **时间**: 2026年6月
- **来源**: Semiconductor Engineering
- **作者**: Ann Mutschler
- **类型**: 技术分析
- **分类**: 设计/验证方法论
- **标签**: # verification #EDA #AI #规格工程

## 🔗 原文链接
- [Rethinking Chip Verification](https://semiengineering.com/rethinking-chip-verification/)

## 📝 摘要
芯片验证正在面临设计复杂度爆炸带来的瓶颈。传统验证痛点虽然被 AI 和现代工具部分缓解，但尚未触及根本问题。业界正在推动在 RTL 上方创建"黄金、无歧义的规格"——通过规格工程（Specification Engineering）将需求从规格到实现到验证全过程追踪，利用 AI 辅助检查层级和模块间的差距、冲突和不一致。

## 💡 关键点
- **瓶颈本质**：不是工具不够快，而是从需求到验证的链条不够清晰——规格模糊导致验证盲区
- **规格工程兴起**：创建一个高于 RTL 的"黄金规格"，使需求-实现-验证全链可追溯
- **AI 辅助验证**：AI 正在加速代码生成和验证断言（assertion），但信任问题仍是障碍
- **工具链碎片化**：MBSE 工具、需求数据库、验证管理、HLS、AI 代码生成器已经存在但互不连通

## 📈 影响分析
**对 EDA 产业的影响**：
- EDA 三巨头（Synopsys/Cadence/Siemens EDA）面临将碎片化工具链整合为一套完整"规格到验证"流程的压力
- 创业机会：专门提供 AI 驱动规格工程平台的公司可能成为 EDA 领域的"新秀"
- AI 生成的 RTL 代码质量参差不齐，需要新的形式化验证方法

**对制造的影响**：
- 验证前移趋势与制造中的测试前移形成呼应——"前移"成为行业共识
- 更好的验证流程可减少设计-制造来回迭代（Design-Tapeout-ECO cycle），直接缩短晶圆厂 NPI 周期
- AI 驱动的验证自动化有望缓解 EDA 验证工程师严重短缺问题

---
*由芯片制造洞察收集器生成*
