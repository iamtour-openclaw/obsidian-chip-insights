# How To Build Billions of Bumps — Hybrid Bonding 实现前所未有的连接密度

- **日期**: 2026-06-18
- **来源**: Semiconductor Engineering
- **作者**: Bryon Moyer
- **链接**: https://semiengineering.com/how-to-build-billions-of-bumps/
- **分类**: #先进封装 #混合键合 #3D集成

## 摘要

混合键合（Hybrid Bonding）技术使得芯片封装可以实现数十亿甚至数万亿个连接。本文深入分析了混合键合如何实现1µm pitch的无凸块互连，以及随之而来的制造均匀性、检测和测试挑战。

## 关键点

1. **惊人的连接密度** — 1µm pitch的混合键合使每个毫米可容纳1000个"凸块"，全尺寸中介层+小芯片拼接轻松实现数十亿连接
2. **极端工艺均匀性要求** — 300mm晶圆上200nm pad pitch理论上可实现数万亿连接，但晶圆级别的工艺均匀性至关重要
3. **检测不可行** — 数十亿连接不可能逐个检测，必须依赖工艺可预测性和模块化架构
4. **测试策略** — 需要在I/O中加入测试基础设施，在键合前后验证连接的可靠性
5. **容忍缺陷的设计** — 从管理单个互连转向架构级控制，设计必须预设一定程度的缺陷

## 影响分析

混合键合是后摩尔时代最重要的封装技术之一。对于中国的HBM、AI芯片和Chiplet生态系统建设，该技术提供了跨越传统光刻限制的路径。但极端均匀性要求和检测挑战意味着掌握该技术需要长期工艺积累。

## 相关笔记

- [[Heterogeneous Integration Challenges Mount]]
- [[Better Data and Differentiation Through Chiplet-Based Designs]]
