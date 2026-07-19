---
title: "ROS2 小车自主导航项目"
date: 2026-07-19
draft: false
tags: ["ROS2", "项目"]
---

## 项目简介
本项目实现了基于 ROS2 Humble 的差速小车自主导航，使用了 Nav2 框架和 Cartographer SLAM。

## 硬件平台
- 树莓派 4B
- RPLIDAR A1
- 直流减速电机 + 编码器

## 软件栈
- Ubuntu 22.04
- ROS2 Humble
- Nav2
- Cartographer

## 踩坑记录
- 编码器噪声导致里程计漂移，通过扩展卡尔曼滤波融合 IMU 解决
