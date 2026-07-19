---
title: "面试复盘：具身智能 VLA 算法岗"
date: 2026-07-05
draft: false
tags: ["面试", "复盘"]
---

## 背景
- 公司：某具身智能独角兽（暂不公开）
- 岗位：VLA 模型算法实习生
- 流程：线上视频，1h 技术面

## 面试内容
### 1. 自我介绍
重点介绍了 ROS2 小车项目和目前在学的 π0 模型，提到了对 Sim-to-Real 的理解。

### 2. 手撕代码
实现一个简单的 `Transformer Encoder`（Python），要求写出 `self-attention` 和 `position-wise FFN`。写完后被问复杂度及优化方向。

### 3. 项目深挖
- “你的小车项目里，Nav2 用的全局规划器是哪种？为什么不用纯端到端学习？”
- “Cartographer 的回环检测原理是什么？”
- “如果地图规模扩大 10 倍，你如何优化？”

### 4. 开放问题
- “Sim-to-Real Gap 主要有哪些来源？你有哪些解决方法？”
- “如果你想用 VLA 控制一个机械臂抓取物体，数据怎么采集？如何处理动作滞后？”

## 改进方向
- 准备一个 VLA 模型的最小复现（如 OpenVLA + LIBERO 基准）
- 加强对 Domain Randomization 和 System Identification 的实践
