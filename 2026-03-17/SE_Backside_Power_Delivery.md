# Backside Power Delivery Creates Fab Tool, Thermal Dissipation Barriers

## 📊 基本信息
- **日期**: 2026-03-17
- **时间**: 08:00
- **来源**: Semiconductor Engineering
- **类型**: 技术报告
- **分类**: 先进制程/功率传输/晶体管技术
- **标签**: 背面功率传输、BSPDN、纳米片晶体管、2nm制程

## 🔗 原文链接
- [Backside Power Delivery Creates Fab Tool, Thermal Dissipation Barriers](https://semiengineering.com/backside-power-delivery-creates-fab-tool-thermal-dissipation-barriers/)

## 📝 摘要
背面功率传输网络(BSPDN)将功率从晶圆背面直接传输到先进晶体管，这是一种架构改进，可加快处理器性能、减少功率损耗并提高功率效率。但BSPDN也带来了许多新的制造挑战：需要移除大部分硅晶圆、精确对准纳米TSV与晶体管源/漏极、进行新建模以减少热量困在正面和背面互连层之间带来的热损失。领先的IC制造商正在取得重大进展：Intel的18A制程(RibbonFET + PowerVia)已投产，Samsung计划在2nm节点引入背面功率，TSMC将在2nm引入GAA并在16Å节点(A16)引入Super Power Rail。

## 💡 关键点
- **性能提升显著**：BSPDN可实现IR压降降低20%-30%，最大频率提升2%-6%，核心面积减少5%-15%
- **背面功率自然配合GAA器件**：提供比正面更直接、阻抗更低的晶体管源极路径
- **制造挑战严峻**：晶圆减薄至1-3微米、两次对准需要约10nm的叠加精度、热penalty高达14°C
- **新工艺流程**：先制造晶体管和PowerVia，然后制造正面BEOL，键合到载晶圆，再进行背面处理
- **成本降低**：Intel 18A利用背面功率减少正面互连密度，单次和直接 patterning降低掩模数量和步进次数超过40%
- **热管理更复杂**：晶体管被正面FEOL互连堆栈和背面功率传输堆栈夹在中间，形成"三明治"结构

## 📈 影响分析
背面功率传输网络是先进制程的关键技术突破，将成为2nm及以下节点的标配。它解决了传统正面功率传输的IR压降问题，提升芯片性能的同时降低功耗。对晶圆厂而言，BSPDN需要全新的制造设备和工艺：包括两面对准、专用背面加工、新的热管理方案等。Intel率先量产，Samsung和TSMC紧随其后。随着AI加速器、GPU等高功耗芯片需求激增，BSPDN将成为高性能计算应用的核心技术，推动半导体行业进入新一代功率传输架构时代。

---
*由芯片制造洞察收集器生成*