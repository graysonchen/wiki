---
title: 地球内核结构
weight: 6
date: 2017-04-22
---

## 背景知识

-   半径：1220 km
-   组成：
    -   固态铁-镍合金
    -   少量轻元素（S, O, Si, H）
-   形成机制：
    -   地球形成早期只有一个液态铁核
    -   随着地球的不断冷却，液态铁核凝固形成固态内核，结晶速率 0.5 mm/year，结晶时间约10亿年
    -   凝固过程中会释放潜热和轻物质
        -   促进液态外核的流动->构成地磁发电机->形成地球磁场
        -   驱动地幔对流->板块运动

发现历史：

-   1906, Oldham, 发现外核
-   1936, Lehmann 在地核影区中发现 P 波，认为是内核边界反射波 PKiKP，并认为内核是固态
-   1940, Birch 从矿物学角度认为在内核的温压条件下内核一定是固态
-   1971, Dziewonski & Gilbert, 利用 normal mode 证明了内核是固态的

## 研究方法

1.  地震学
    -   体波: PKP, PKIKP, PKiKP, PKJKP
    -   Normal Mode
2.  矿物物理
    -   高温高压实验
    -   第一性原理计算
3.  地磁学
4.  动力学模拟

### 体波

-   中心频率 1 Hz 左右，高分辨率
-   只能约束 P 和 S 波速，无法约束密度
-   对内核采样不均匀（地震和台站分布不均）

**利用 PKIKP 震相研究内核结构**

震中距    | 内核采样深度 | 内核走时  | 参考震相  | 备注
---------|------------|----------|---------|---
120-130° | 0-15 km    | 10-30 s  | 无      |
130-143° | 10-90 km   | 30-100 s | PKiKP   | 与 PKIKP 极性相反
146.5-156.5° | 150-350 km | 100-150 s | PKPbc | 与 PKIKP 波形相同
155-180° | 350-1221 km  | 150-220 s  | PKPab/None | 是 PKIKP 的 Hilbert 变换

![PKIKP 射线路径](/Seismology/images/PKIKP-raypath.png)

### Normal mode

-   ~ 100 s
-   nSl，每个 mode 包含 2*l+1 个 singlets
-   非旋转、球状均匀球下，singlets 频率相同
-   旋转、不均匀、各向异性均会导致 singlets 频率不同，产生 mode splitting 现象

## 径向分层结构

1. 最外层100km：各向同性层
2. 中间层100-900：各向异性层
2. 内内核（300km）：各向异性层

### 内核各向异性

- Polar path 速度大于 equtorial path.
- 各向异性强度: ~3%

解释：

1.  hcp iron 定向排列
    1. 凝固过程中定向排列
    2. 凝固之后内核变形

### 衰减各向异性

## 东西半球差异

### 地震学观测

 | 各向同性速度 | 衰减 | 各向异性强度 |
---|---|---|---
东半球(40°E-180°E) | 快(+0.5%) | 高(Q=300) | 弱(0.5%)
西半球(180°W-40°E) | 慢(-0.3%) | 低(Q=600) | 强(3.0%)

### 动力学解释

1. 内核单向增长：一个半球熔化，另一个半球凝固
   - {{% paper "Alboussière et al., Nature, 2010" "10.1038/nature09257" %}}

2. 外核的热化学对流导致内核边界处不同的凝固条件

## PKJKP

## 矿物物理

铁相图:

1.  室温室压： bcc (body-centered cubic)
2.  升温：fcc (face-centered cubic)
3.  升压：hcp (hexagonal close-packed)
