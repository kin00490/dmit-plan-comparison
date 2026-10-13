# DMIT 套餐：洛杉矶/香港/东京三档线路全价格对照，Pro、EB、T1 到底该怎么选

搜「DMIT 套餐」的人，多半在官网卡过壳：一台 2 核 2G 的机器，价格能从每月十几美元跳到每月一百多美元，中间差的不是配置——是线路。再叠上洛杉矶、香港、东京三个机房，以及 AS3、AN4、AN5 三代硬件平台，在售 SKU 加起来八十多个。第一次进去看晕很正常。

这篇把整盘摊开：先讲清楚三档线路的区别，再把各机房套餐价格列全，最后给几条可以直接抄的选择建议。

有一点要先说在前面：DMIT 是补货制销售，热门低价款经常售罄，个别档位的报价在不同补货批次里也不完全一样。下面表里的数字取自近期的公开补货记录和第三方整理，**最终价格、库存和可用性以下单页面为准**。

## 先搞懂线路，再谈配置

DMIT 把产品线按网络质量分成三档，套餐名里的 Pro、EB、T1 说的就是它：

| 线路 | 中国方向 IPv4 路由（公开资料整理） | 谁适合 |
| --- | --- | --- |
| **Premium（Pro）** | 电信去程 CN2 GIA（AS4809），联通去程直连 AS4837，移动去程经香港移动 AS58453，三网回程统一走 CN2 GIA | 对大陆访问体验有硬要求，不接受晚高峰波动 |
| **Eyeball（EB）** | 电信在 AS9929 与 AS58807 之间负载，联通主要走 AS9929，移动主要走 AS58807（CMIN2 系） | 预算优先，但希望大陆住宅用户访问别太难看 |
| **Tier 1（T1）** | 纯国际 BGP，没有针对中国大陆的专项优化 | 国际业务、中转、备份、CI/CD 等纯海外流量场景 |

一句话版本：大陆体验优先选 Pro，性价比优先选 EB，只跑国际流量选 T1。

三档的价差有多大？拿洛杉矶同配置做个对照就很直观：

- `LAX.AS3.Pro.TINY`：1 核 / 2G / 20G / 1TB 流量 @1Gbps，$10.90/月
- `LAX.AS3.EB.TINY`：1 核 / 2G / 20G / **1.5TB** 流量 @**2Gbps**，$10.90/月

同样 $10.90，EB 给的是更大的流量和更宽的端口，Pro 多出来的是 CN2 GIA 回程。这个价位上你买的不是性能，是路由。

👉 [👉 打开 DMIT 官网查看当前在售套餐](https://www.dmit.io/aff.php?aff=12046)

## 洛杉矶 LAX 全套餐价格表

洛杉矶是 DMIT 套餐数量最多、补货最频繁的机房，先看这一套，其余两个机房的结构基本照搬。

### AS3 平台 Premium（CN2 GIA）

| 套餐 | 配置 | 流量 / 端口 | 超量后 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- | --- |
| LAX.AS3.Pro.TINY | 1核 / 2G / 20G SSD | 1TB @ 1Gbps | 限速 4Mbps 不限流 | $10.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.Pro.Pocket | 2核 / 2G / 40G SSD | 1.5TB @ 4Gbps | 限速 4Mbps 不限流 | $16.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.Pro.STARTER | 2核 / 2G / 80G SSD | 3TB @ 10Gbps | 限速 4Mbps 不限流 | $34.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.Pro.MINI | 4核 / 4G / 80G SSD | 5TB @ 10Gbps | 限速 8Mbps 不限流 | $62.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.Pro.MICRO | 4核 / 4G / 160G SSD | 7TB @ 10Gbps | 限速 8Mbps 不限流 | $87.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.Pro.MEDIUM | 6核 / 8G / 160G SSD | 14TB @ 10Gbps | 限速 10Mbps 不限流 | $199.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

### AS3 平台 Eyeball（CMIN2 系）

| 套餐 | 配置 | 流量 / 端口 | 超量后 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- | --- |
| LAX.AS3.EB.TINY | 1核 / 2G / 20G SSD | 1.5TB @ 2Gbps | 限速 4Mbps 不限流 | $10.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.EB.Pocket | 2核 / 2G / 40G SSD | 3TB @ 4Gbps | 限速 4Mbps 不限流 | $16.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.EB.STARTER | 2核 / 2G / 80G SSD | 5TB @ 10Gbps | 限速 4Mbps 不限流 | $34.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.EB.MINI | 4核 / 4G / 80G SSD | 10TB @ 10Gbps | 限速 8Mbps 不限流 | $62.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.EB.MICRO | 4核 / 4G / 160G SSD | 14TB @ 10Gbps | 限速 8Mbps 不限流 | $87.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.EB.MEDIUM | 6核 / 8G / 160G SSD | 30TB @ 10Gbps | 限速 10Mbps 不限流 | $199.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

同一个价位段上，EB 的流量基本是 Pro 的两倍上下。TINY、Pocket、STARTER 三档甚至价格完全一致——这就是为什么很多人会先买 EB 试水。差异在于回国路由，Pro 是全程 CN2 GIA，EB 是 9929 + CMIN2 的组合，实际体感取决于你用户用的是哪家宽带。

### AS3 平台 Tier 1（国际线路）

| 套餐 | 配置 | 流量 / 端口 | 超量后 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- | --- |
| LAX.AS3.T1.WEE | 1核 / 1G / 20G SSD | 1TB @ 4Gbps | 限速 100Mbps 不限流 | $36.90 | **年付** | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.T1.TINY | 1核 / 1G / 20G SSD | 2TB @ 4Gbps | 限速 200Mbps 不限流 | $6.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.T1.STARTER | 2核 / 2G / 40G SSD | 4TB @ 10Gbps | 限速 200Mbps 不限流 | $12.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.T1.MINI | 2核 / 4G / 80G SSD | 8TB @ 10Gbps | 限速 200Mbps 不限流 | $21.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.T1.MICRO | 4核 / 4G / 120G SSD | 16TB @ 10Gbps | 限速 500Mbps 不限流 | $32.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.T1.MEDIUM | 4核 / 8G / 160G SSD | 32TB @ 10Gbps | 限速 500Mbps 不限流 | $49.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.T1.LARGE | 8核 / 16G / 320G SSD | 64TB @ 10Gbps | 限速 500Mbps 不限流 | $99.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AS3.T1.GIANT | 8核 / 24G / 640G SSD | 128TB @ 10Gbps | 限速 1Gbps 不限流 | $199.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

$36.90/年 的 `T1.WEE` 是 DMIT 全系最低入手价。但请注意它的定位：国际 BGP，**没有中国大陆优化**。如果你的用户主要在国内，买 T1 大概率会比预期慢——这不是产品问题，是买错线了。

### AN5 平台 Premium（新一代硬件）

AN5 用的是 AMD EPYC 9005 系列，配置档位名和 AS3 一样，但价格整体上浮。以下价格来自近期补货记录：

| 套餐 | 配置 | 流量 / 端口 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- |
| LAX.AN5.Pro.TINY | 1核 / 2G / 20G SSD | 1TB @ 1Gbps | 约 $12.98–14.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AN5.Pro.Pocket | 1核 / 2G / 40G SSD | 1.5TB @ 4Gbps | 约 $18.90–21.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AN5.Pro.STARTER | 2核 / 2G / 80G SSD | 3TB @ 10Gbps | 约 $38.90–43.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AN5.Pro.MINI | 4核 / 4G / 80G SSD | 5TB @ 10Gbps | $79.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AN5.Pro.MICRO | 4核 / 4G / 160G SSD | 7TB @ 10Gbps | $110.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AN5.Pro.MEDIUM | 6核 / 8G / 160G SSD | 14TB @ 10Gbps | $289.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AN5.Pro.LARGE | 8核 / 16G / 320G SSD | 25TB @ 10Gbps | $499.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| LAX.AN5.Pro.GIANT | 12核 / 24G / 640G SSD | 50TB @ 10Gbps | $1009.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

入门三档的报价在不同补货批次里出现过差异，所以上面给的是区间。同一档位名，AN5 比 AS3 贵一截（MINI 差 $17、MICRO 差 $23），换来的主要是新平台和更高的单核性能。如果你只是建站或跑轻量服务，AS3 的性价比更实在。

## 香港 HKG 套餐

香港机房的卖点是物理距离近，配合 CN2 GIA 回程，延迟能压得很低。代价是价格明显高于洛杉矶同档位。

### HKG Premium AS3

| 套餐 | 配置 | 带宽 / 流量 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- |
| HKG.Pro.TINY | 1核 / 1G / 20G SSD | 1Gbps / 500GB | $39.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.Pro.STARTER | 1核 / 2G / 40G SSD | 1Gbps / 1.0TB | $79.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.Pro.MINI | 2核 / 2G / 60G SSD | 1Gbps / 1.5TB | $119.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.Pro.MICRO | 2核 / 4G / 80G SSD | 1Gbps / 2.0TB | $159.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.Pro.MEDIUM | 4核 / 4G / 160G SSD | 1Gbps / 2.5TB | $179.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.Pro.LARGE | 4核 / 8G / 240G SSD | 1Gbps / 3.0TB | $239.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.Pro.GIANT | 8核 / 16G / 320G SSD | 1Gbps / 4.8TB | $499.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

### HKG Premium AN5

AN5 版香港 Pro 的显著变化在硬盘：同档位给的 SSD 容量基本翻倍。

| 套餐 | 配置 | 带宽 / 流量 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- |
| HKG.AN5.Pro.MINI | 2核 / 2G / 80G SSD | 1Gbps / 1.5TB | $149.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AN5.Pro.MICRO | 2核 / 4G / 160G SSD | 1Gbps / 2.0TB | $159.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AN5.Pro.MEDIUM | 4核 / 4G / 160G SSD | 1Gbps / 2.5TB | $180.00 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AN5.Pro.LARGE | 4核 / 8G / 320G SSD | 1Gbps / 3.0TB | $240.00 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AN5.Pro.GIANT | 8核 / 16G / 640G SSD | 1Gbps / 6.0TB | $500.00 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

一个很实际的对比：`HKG.AN5.Pro.MICRO` 是 2核4G / 160G / 2TB，$159.90；`HKG.Pro.MICRO`（AS3）是 2核4G / 80G / 2TB，$159.90。同价，硬盘差一倍。新平台在香港这边已经算是在挤水分了。

### HKG Eyeball（间歇性上架）

香港 EB 系列不是长期在售，补货时才有。近期一次补货记录里的配置和价格是：

| 套餐 | 平台 | 配置 | 带宽 / 流量 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- | --- |
| HKG.AS3.EB.TINY | AS3 | 1核 / 1G / 20G SSD | 1Gbps / 800GB | $39.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.STARTER | AS3 | 1核 / 2G / 40G SSD | 1Gbps / 1.5TB | $79.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.MINI | AS3 | 2核 / 4G / 60G SSD | 1Gbps / 2.2TB | $126.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.MICRO | AS3 | 4核 / 4G / 80G SSD | 1Gbps / 3TB | $179.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AS3.EB.MEDIUM | AS3 | 4核 / 8G / 160G SSD | 1Gbps / 4TB | $239.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AN5.EB.TINY | AN5 | 4核 / 4G / 80G SSD | 1Gbps / 2.2TB | $149.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AN5.EB.STARTER | AN5 | 4核 / 4G / 160G SSD | 1Gbps / 3TB | $199.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AN5.EB.MINI | AN5 | 6核 / 8G / 160G SSD | 1Gbps / 4TB | $279.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AN5.EB.MICRO | AN5 | 8核 / 16G / 320G SSD | 1Gbps / 4.5TB | $359.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.AN5.EB.MEDIUM | AN5 | 12核 / 24G / 640G SSD | 1Gbps / 9TB | $759.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

注意香港 EB 和香港 Pro 的差价在这个表里体现得不明显（AS3 的 TINY 都是 $39.90），也就是说在香港机房，EB 的性价比优势不如洛杉矶明显。

### HKG Tier 1（国际 BGP）

| 套餐 | 配置 | 流量 | 价格 | 计费周期 | 购买 |
| --- | --- | --- | --- | --- | --- |
| HKG.T1.WEE | 1核 / 1G / 20G SSD | 1TB | $36.90 | **年付** | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.T1.TINY | 1核 / 1G / 20G SSD | 2TB | $6.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.T1.STARTER | 1核 / 2G / 40G SSD | 4TB | $12.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.T1.MINI | 2核 / 2G / 60G SSD | 8TB | $21.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.T1.MICRO | 4核 / 4G / 80G SSD | 16TB | $32.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.T1.MEDIUM | 4核 / 8G / 160G SSD | 32TB | $49.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.T1.LARGE | 8核 / 16G / 320G SSD | 64TB | $99.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| HKG.T1.GIANT | 8核 / 24G / 640G SSD | 128TB | $199.90 | 月付 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

## 东京 TYO 套餐

东京的价格结构跟香港接近，但 Pro 的入门门槛低不少。TYO 的 Pro 和 EB 都是月付、年付双报价。

| 套餐 | 线路 | 配置 | 流量 | 月付 | 年付 | 购买 |
| --- | --- | --- | --- | --- | --- | --- |
| TYO.Pro.TINY | CN2 GIA | 1核 / 1G / 20G SSD | 500GB | $21.90 | $262 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.Pro.STARTER | CN2 GIA | 1核 / 2G / 40G SSD | 1.0TB | $39.90 | $478 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.Pro.MINI | CN2 GIA | 2核 / 2G / 60G SSD | 1.5TB | $79.90 | $958 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.Pro.MICRO | CN2 GIA | 2核 / 4G / 80G SSD | 2.0TB | $159.90 | $1918 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.Pro.MEDIUM | CN2 GIA | 4核 / 4G / 160G SSD | 5.0TB | $259.90 | $3118 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.Pro.LARGE | CN2 GIA | 8核 / 16G / 320G SSD | 8.0TB | $429.90 | $5158 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.EB.TINY | CMIN2 | 1核 / 1G / 20G SSD | 1.0TB | $25.90 | $310 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.EB.STARTER | CMIN2 | 1核 / 2G / 40G SSD | 2.0TB | $55.90 | $670 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.EB.MINI | CMIN2 | 2核 / 2G / 60G SSD | 3.0TB | $85.90 | $1030 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.EB.MICRO | CMIN2 | 2核 / 4G / 80G SSD | 4.0TB | $119.90 | $1438 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |
| TYO.EB.MEDIUM | CMIN2 | 4核 / 4G / 160G SSD | 6.0TB | $179.90 | $2158 | [ 查看该套餐](https://www.dmit.io/aff.php?aff=12046) |

东京的 Tier 1 和香港同价同配，这里不重复列表：`TYO.T1.WEE` $36.90/年、`TINY` $6.90/月、`STARTER` $12.90/月、`MINI` $21.90/月、`MICRO` $32.90/月、`MEDIUM` $49.90/月、`LARGE` $99.90/月、`GIANT` $199.90/月。

一个值得留意的点：TYO.Pro.TINY 是 $21.90/月，TYO.EB.TINY 是 $25.90/月——**东京这边 EB 反而比 Pro 贵**。原因是两条线的流量额度不同（500GB vs 1TB），不是定价写错了。所以在东京机房，别默认 EB 一定更便宜，先比流量。

## 套餐之外，这几件事会直接影响你的实际体验

**流量跑完不会停机。** DMIT 全系的做法是把超量后的带宽限下来继续给流量，而不是掐掉服务。T1 线路限速在 100Mbps–1Gbps 之间，Pro 和 EB 则限到 4–10Mbps。区别很大：T1 超量后还能正常跑业务，Pro/EB 超量后基本只剩应急用。如果你经常把流量用满，T1 的容错空间反而更好。

**每套含 1 个 IPv4 和 1 个 IPv6 /64。** 按第三方整理的说法，IP 被墙后 Pro/EB 系列符合条件的话每 15 天可以免费更换一次，其他情况大约 $5/次。这条规则请以客服确认的当前政策为准，各系列不完全一样。

**付款方式对国内用户友好。** 支持支付宝、微信、PayPal 和信用卡，有中文工单，下单不需要实名。

**库存是补货制。** 低价款和特价机（例如 EB 系列那些以加州地名命名的限量款）放出来基本是抢的，看到有货还在犹豫，通常就没了。补货没有固定节奏。

**平台代号会影响价格。** AS3 = AMD EPYC 7003，AN4 = EPYC 9004，AN5 = EPYC 9005。同档位配置下，平台越新价格越高。如果只看性价比，AS3 目前是这几代里最便宜的。

## 优惠码：整理出来的循环折扣

DMIT 不搞大促，优惠码数量少、有效期短，且大多只针对特定线路和付款周期。以下是多个渠道整理过、出现过循环折扣记录的码：

| 优惠码 | 适用范围 | 折扣 |
| --- | --- | --- |
| `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF` | 洛杉矶 EB TINY 及以上，季付/年付 | 8 折（循环） |
| `202510_HKG_TYO_PRO_20OFF_RECURRING` | 香港 Pro / 东京 Pro，季付及以上 | 8 折（循环） |
| `202510_HKG_TYO_T1_30OFF_RECURRING` | 香港 T1 / 东京 T1，季付及以上（不含 WEE） | 7 折（循环） |
| `2025-TYO-T1-HI-GSL-NON-MONTHLY-30OFF` | 东京 T1 TINY 及以上，季付及以上 | 7 折 |
| `2025-TYO-T1-HI-GSL-MONTHLY-10OFF` | 东京 T1 TINY 及以上，月付 | 9 折 |
| `Lite-Annually-Recur-30OFF` | Lite / Standard 线路年付 | 7 折（循环） |
| `Lite-Semi-Annually-Recur-20OFF` | Lite / Standard 线路半年付 | 8 折（循环） |
| `2025-XMAS-LAX-PRO-EB-ANNUALLY-STARTER-AND-HIGHER-15OFF-RECURRING` | 洛杉矶 Pro/EB 年付 STARTER 及以上 | 15% 折扣 + 返现 |
| `2025-XMAS-LAX-PRO-EB-10-OFF-RECURRING` | 洛杉矶 Pro/EB 常规套餐 | 10% 折扣 + 返现 |
| `2025-XMAS-LAX-T1-10-OFF-RECURRING` | 洛杉矶 T1，不含 WEE | 10% 折扣 + 返现 |

必须说明的是：这些码来自促销记录整理，**不能保证此刻仍然有效**。DMIT 的码大多绑定了具体产品线和付款周期，跨线使用会验证失败。

用法很简单：在购物车选好套餐和付款周期，找到优惠码输入框，填入后点 `Validate Code`，只有验证通过才会显示折后价。

👉 [👉 去 DMIT 下单页试试优惠码是否还能用](https://www.dmit.io/aff.php?aff=12046)

## 三类需求，直接抄答案

**大陆访问体验优先。** 选 Pro 线。洛杉矶的话 `LAX.AS3.Pro.TINY`（$10.90/月）或 `Pocket`（$16.90/月）是最常见的起点；用户集中在华南、想要更低延迟，就把预算挪到香港 `HKG.Pro.TINY`（$39.90/月），但注意香港 Pro 的流量给得少（500GB），流量敏感的话并不划算。

**预算有限但国内用户得能正常访问。** 优先看 EB。洛杉矶 `LAX.AS3.EB.TINY` 和 `LAX.AS3.EB.Pocket` 与 Pro 同价，流量却是 1.5 倍和 2 倍，端口也更宽。EB 的短板只在回程路由，日常浏览、建站、看视频这类场景基本够用。

**纯国际业务、中转、备份、CI/CD。** 直接 T1。`LAX.AS3.T1.WEE` $36.90/年 是全系最低门槛，而且超量后还有 100Mbps 可以跑。只要不指望它改善大陆访问速度，它就是这个价位里最干脆的选择。

**配置怎么定。** 起步用 TINY，2G 内存跑 WordPress、面板、轻量服务足够。要跑数据库、Docker 多容器、编译任务，直接上 4G 内存档——`MINI` 系列在这个位置。DMIT 支持在线升级配置，所以别一上来就按三年后的需求买。

**平台怎么选。** 同一档位名，AS3 比 AN5 便宜十几到二十几美元一个月。如果只是常规业务，看不出必须上 AN5 的理由；如果你的负载确实吃单核性能，AN5 才值得加钱。

## 下单前值得先做的两件事

第一，用 looking glass 测一下。DMIT 各机房都有公开的测试入口和测试 IP，拿你自己常用的宽带 ping 一遍，比看任何评测都准：

| 机房 / 线路 | 测试 IPv4 |
| --- | --- |
| 洛杉矶 Pro | 154.17.2.2 |
| 洛杉矶 Tier 1 | 174.136.204.135 |
| 香港 Pro | 103.117.100.199 |
| 香港 Tier 1 | 154.12.176.28 |
| 东京 Pro | 154.12.190.32 |
| 东京 Tier 1 | 154.31.112.5 |

第二，确认套餐名再付款。DMIT 的套餐命名是「机房 + 平台 + 线路 + 档位」的组合，`LAX.AS3.Pro.TINY` 和 `LAX.AS3.T1.TINY` 只差一个字段，价格差好几倍，性能取向完全不同。买错线路之后再换，成本比一开始多花五分钟高得多。

👉 [👉 前往 DMIT 官网确认当前库存与价格](https://www.dmit.io/aff.php?aff=12046)
