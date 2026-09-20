# 搬瓦工套餐对比：CN2 GIA-E、SLA、香港日本机房全套餐价格一表看懂，附选购建议和优惠参考

搜“搬瓦工套餐对比”的人，十有八九卡在同一个问题：为什么配置几乎一样的两台机器，价格能差出十几倍？一台 1GB 内存、1TB 流量的 KVM 套餐年付 49.99 美元，另一台 1GB 内存、1TB 流量的香港 CN2 GIA 套餐月付就要 89.99 美元。差价不在内存条上，全在线路上。

这篇文章把搬瓦工（BandwagonHost）目前在售的全部套餐按系列拆开，配上当前价格和购买入口，看完你至少能搞清楚三件事：每个系列到底差在哪、你的用途该买哪档、哪些钱可以省下来。

## 先搞懂搬瓦工的产品线逻辑

搬瓦工的套餐命名看着眼花缭乱，其实只按一个维度分组：**回中国大陆的线路质量**。

- **KVM 常规套餐**：普通国际线路，不针对中国大陆优化，价格最低；
- **CN2 GIA-E**：电信双向 CN2 GIA，联通走 9929、移动走 CMIN2 的优质直连，是搬瓦工的招牌产品；
- **ECOMMERCE SLA**：和 GIA 同级别的线路，但加了 99.99% 在线率赔付协议和每两周免费换 IP，专做付费业务；
- **香港 / 东京 / 大阪 / 新加坡 CN2 GIA**：亚太机房，物理延迟低，价格也上了一个台阶；
- **迪拜**：服务中东市场的小众机房，国内用户基本不用看。

同一系列内部再按内存、硬盘、流量分档。所以选套餐的第一步不是看参数，是先确定线路档位，第二步才是在档位里挑配置。

## 全套餐对比：按系列逐一列出

以下价格和配置均来自搬瓦工当前订单页公开展示的信息，币种为美元。表格里的入口都走同一个推广链接体系，点击后会进入对应的购买页面。

### KVM 常规套餐（入门与海外业务）

机房可选洛杉矶 DC2/DC8、弗里蒙特、纽约、新泽西、荷兰等多个节点，其中 DC8 ZNET 对电信略有优化，但整体就是普通国际线路，晚高峰表现一般。

| 套餐 | 内存 / CPU / SSD / 流量 / 带宽 | 价格 | 购买入口 |
| --- | --- | --- | --- |
| 20G KVM | 1GB / 2核 / 20GB / 1TB / 1Gbps | $49.99/年 | [ 购买 20G KVM](https://bandwagonhost.com/aff.php?aff=79616&pid=44) |
| 40G KVM | 2GB / 3核 / 40GB / 2TB / 1Gbps | $52.99/半年、$99.99/年 | [ 购买 40G KVM](https://bandwagonhost.com/aff.php?aff=79616&pid=45) |
| 80G KVM | 4GB / 4核 / 80GB / 3TB / 1Gbps | $19.99/月起、$199.99/年 | [ 购买 80G KVM](https://bandwagonhost.com/aff.php?aff=79616&pid=46) |
| 160G KVM | 8GB / 5核 / 160GB / 4TB / 1Gbps | $39.99/月起、$399.99/年 | [ 购买 160G KVM](https://bandwagonhost.com/aff.php?aff=79616&pid=47) |
| 320G KVM | 16GB / 6核 / 320GB / 5TB / 1Gbps | $79.99/月起、$799.99/年 | [ 购买 320G KVM](https://bandwagonhost.com/aff.php?aff=79616&pid=48) |
| 480G KVM | 24GB / 7核 / 480GB / 6TB / 1Gbps | $119.99/月起、$1199.99/年 | [ 购买 480G KVM](https://bandwagonhost.com/aff.php?aff=79616&pid=49) |

这系列的定位很清楚：练手、学 Linux、跑纯海外业务。受众不在国内的话，它是全产品线性价比最高的；受众在国内，晚高峰的体验会让你怀疑人生。

### CN2 GIA-E 套餐（主力推荐）

默认可选 DC6（CN2 GIA-E）、DC9（CN2 GIA）机房，也支持切换到大阪 JPOS_1（软银线路）、荷兰 EUNL_9 等节点。带宽从 2.5Gbps 起步，高配到 10Gbps。

| 套餐 | 内存 / CPU / SSD / 流量 / 带宽 | 价格 | 购买入口 |
| --- | --- | --- | --- |
| 20G CN2 GIA-E | 1GB / 2核 / 20GB / 1TB / 2.5Gbps | $49.99/季、$169.99/年 | [ 购买 20G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=87) |
| 40G CN2 GIA-E | 2GB / 3核 / 40GB / 2TB / 2.5Gbps | $89.99/季、$299.99/年 | [ 购买 40G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=88) |
| 80G CN2 GIA-E | 4GB / 4核 / 80GB / 3TB / 2.5Gbps | $56.99/月起、$549.99/年 | [ 购买 80G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=89) |
| 160G CN2 GIA-E | 8GB / 6核 / 160GB / 5TB / 5Gbps | $86.99/月起、$879.99/年 | [ 购买 160G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=90) |
| 320G CN2 GIA-E | 16GB / 8核 / 320GB / 8TB / 5Gbps | $159.99/月起、$1599.99/年 | [ 购买 320G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=91) |
| 640G CN2 GIA-E | 32GB / 10核 / 640GB / 10TB / 10Gbps | $289.99/月起、$2759.99/年 | [ 购买 640G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=92) |
| 1280G CN2 GIA-E | 64GB / 12核 / 1280GB / 12TB / 10Gbps | $549.99/月起、$5399.99/年 | [ 购买 1280G CN2 GIA-E](https://bandwagonhost.com/aff.php?aff=79616&pid=93) |

绝大多数人的“搬瓦工套餐怎么选”，答案就在这个系列里。入门的 20G 版本季付 49.99 美元、年付 169.99 美元，折算月成本 14 美元左右，换来的是三网直连的晚高峰表现。如果预算再紧一点，可以留意官方不定期补货的限量款，此前出现过年付 19 美元级别的 MINICHICKEN 之类的特殊套餐，库存秒没，属于蹲到就锁单的类型。

### ECOMMERCE SLA 套餐（付费业务专用）

位于洛杉矶 DC5 SLA 专属机房，CPU 为 AMD 独享核心，NVMe 硬盘。官方页面明确写了几项 KVM 和 GIA-E 套餐没有的东西：99.99% 在线率 SLA（达不到按时长赔付）、**每两周免费更换一次 IP**，线路为电信 CN2 GIA/CTGNet、联通 AS10099、移动 CMIN2 三网直连，机房有双路电源和冗余网络设计。

| 套餐 | 内存 / CPU / SSD / 流量 / 带宽 | 价格 | 购买入口 |
| --- | --- | --- | --- |
| 20G SLA | 1GB / 2核独享 / 20GB / 1TB / 2.5Gbps | $65.89/季、$239.99/年 | [ 购买 20G SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=164) |
| 40G SLA | 2GB / 3核独享 / 40GB / 2TB / 2.5Gbps | $116.99/季、$399.99/年 | [ 购买 40G SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=165) |
| 80G SLA | 4GB / 4核独享 / 80GB / 3TB / 2.5Gbps | $69.99/月起、$699.99/年 | [ 购买 80G SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=166) |
| 160G SLA | 8GB / 6核独享 / 160GB / 5TB / 5Gbps | $109.99/月起、$1099.99/年 | [ 购买 160G SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=167) |
| 320G SLA | 16GB / 8核独享 / 320GB / 8TB / 5Gbps | $199.99/月起、$1999.99/年 | [ 购买 320G SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=168) |
| 640G SLA | 32GB / 10核独享 / 640GB / 10TB / 10Gbps | $369.99/月起、$3699.99/年 | [ 购买 640G SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=169) |
| 1280G SLA | 64GB / 12核独享 / 1280GB / 12TB / 10Gbps | $699.99/月起、$6999.99/年 | [ 购买 1280G SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=170) |
| 1280G SLA 15TB | 64GB / 12核独享 / 1280GB / 15TB / 10Gbps | $879.99/月起 | [ 购买 15TB SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=171) |
| 1280G SLA 20TB | 64GB / 12核独享 / 1280GB / 20TB / 10Gbps | $1159.99/月起 | [ 购买 20TB SLA](https://bandwagonhost.com/aff.php?aff=79616&pid=172) |

同样 1GB 内存，SLA 比 CN2 GIA-E 入门版一年贵 70 美元。这个差价买的不是性能，是在线率承诺和换 IP 特权。做跨境电商独立站、TikTok 运营这类掉线就亏钱的业务，这笔钱花得有道理；个人博客就没什么必要。

### 香港 / 东京 CN2 GIA（极致低延迟）

两个系列的定价完全相同，都是月付 89.99 美元起步、年付 899.99 美元起步。香港机房位于 Equinix HK2，东京位于 Equinix TY8，都是电信 CN2 GIA 加联通、移动直连，国内访问延迟可以压到几十毫秒量级。区别在带宽：香港 1Gbps，东京 1.2Gbps。

| 套餐 | 内存 / CPU / SSD / 流量 / 带宽 | 价格 | 购买入口 |
| --- | --- | --- | --- |
| 香港 40G | 2GB / 2核 / 40GB / 0.5TB / 1Gbps | $89.99/月、$899.99/年 | [ 购买香港 40G](https://bandwagonhost.com/aff.php?aff=79616&pid=95) |
| 香港 80G | 4GB / 4核 / 80GB / 1TB / 1Gbps | $155.99/月起、$1559.99/年 | [ 购买香港 80G](https://bandwagonhost.com/aff.php?aff=79616&pid=96) |
| 香港 160G | 8GB / 6核 / 160GB / 2TB / 1Gbps | $299.99/月起、$2999.99/年 | [ 购买香港 160G](https://bandwagonhost.com/aff.php?aff=79616&pid=97) |
| 香港 320G | 16GB / 8核 / 320GB / 4TB / 1Gbps | $589.99/月起、$5899.99/年 | [ 购买香港 320G](https://bandwagonhost.com/aff.php?aff=79616&pid=98) |
| 香港 640G | 32GB / 10核 / 640GB / 6TB / 1Gbps | $989.99/月起、$9989.99/年 | [ 购买香港 640G](https://bandwagonhost.com/aff.php?aff=79616&pid=122) |
| 香港 1280G | 64GB / 12核 / 1280GB / 8TB / 1Gbps | $1889.99/月起、$18989.99/年 | [ 购买香港 1280G](https://bandwagonhost.com/aff.php?aff=79616&pid=124) |
| 东京 40G | 2GB / 2核 / 40GB / 0.5TB / 1.2Gbps | $89.99/月、$899.99/年 | [ 购买东京 40G](https://bandwagonhost.com/aff.php?aff=79616&pid=108) |
| 东京 80G | 4GB / 4核 / 80GB / 1TB / 1.2Gbps | $155.99/月起、$1559.99/年 | [ 购买东京 80G](https://bandwagonhost.com/aff.php?aff=79616&pid=109) |
| 东京 160G | 8GB / 6核 / 160GB / 2TB / 1.2Gbps | $299.99/月起、$2999.99/年 | [ 购买东京 160G](https://bandwagonhost.com/aff.php?aff=79616&pid=110) |
| 东京 320G | 16GB / 8核 / 320GB / 4TB / 1.2Gbps | $589.99/月起、$5899.99/年 | [ 购买东京 320G](https://bandwagonhost.com/aff.php?aff=79616&pid=111) |
| 东京 640G | 32GB / 10核 / 640GB / 6TB / 1.2Gbps | $989.99/月起、$9989.99/年 | [ 购买东京 640G](https://bandwagonhost.com/aff.php?aff=79616&pid=123) |
| 东京 1280G | 64GB / 12核 / 1280GB / 8TB / 1.2Gbps | $1889.99/月起、$18989.99/年 | [ 购买东京 1280G](https://bandwagonhost.com/aff.php?aff=79616&pid=125) |

注意流量，入门版每月只有 500GB。这两个系列服务的是金融交易、游戏加速这类对延迟有刚需的场景，普通建站用它们属于高射炮打蚊子。

### 大阪 / 新加坡 CN2 GIA（亚太“平价”替代）

大阪（JPOS_6）和新加坡（Equinix SG1）两个系列定价也相同：入门 2GB 内存、40GB SSD、500GB 流量、1.5Gbps 带宽，月付 49.99 美元、年付 499.99 美元。新加坡是 2026 年新上的节点。官方对大阪机房的描述是去程 CN2 GIA/CTG、联通、移动三网，回程电信 CN2 GIA/CTG。

| 套餐 | 内存 / CPU / SSD / 流量 / 带宽 | 价格 | 购买入口 |
| --- | --- | --- | --- |
| 大阪 40G | 2GB / 2核 / 40GB / 0.5TB / 1.5Gbps | $49.99/月、$499.99/年 | [ 购买大阪 40G](https://bandwagonhost.com/aff.php?aff=79616&pid=134) |
| 大阪 80G | 4GB / 4核 / 80GB / 1TB / 1.5Gbps | $86.99/月起、$869.99/年 | [ 购买大阪 80G](https://bandwagonhost.com/aff.php?aff=79616&pid=135) |
| 大阪 160G | 8GB / 6核 / 160GB / 2TB / 1.5Gbps | $165.99/月起、$1665.99/年 | [ 购买大阪 160G](https://bandwagonhost.com/aff.php?aff=79616&pid=136) |
| 大阪 320G | 16GB / 8核 / 320GB / 4TB / 1.5Gbps | $329.99/月起、$3199/年 | [ 购买大阪 320G](https://bandwagonhost.com/aff.php?aff=79616&pid=137) |
| 大阪 640G | 32GB / 10核 / 640GB / 6TB / 1.5Gbps | $549.99/月起、$5549.99/年 | [ 购买大阪 640G](https://bandwagonhost.com/aff.php?aff=79616&pid=138) |
| 大阪 1280G | 64GB / 12核 / 1280GB / 8TB / 1.5Gbps | $1059.99/月起、$10559.99/年 | [ 购买大阪 1280G](https://bandwagonhost.com/aff.php?aff=79616&pid=139) |
| 新加坡 40G | 2GB / 2核 / 40GB / 0.5TB / 1.5Gbps | $49.99/月、$499.99/年 | [ 购买新加坡 40G](https://bandwagonhost.com/aff.php?aff=79616&pid=173) |
| 新加坡 80G | 4GB / 4核 / 80GB / 1TB / 1.5Gbps | $86.99/月起、$869.99/年 | [ 购买新加坡 80G](https://bandwagonhost.com/aff.php?aff=79616&pid=174) |
| 新加坡 160G | 8GB / 6核 / 160GB / 2TB / 2.5Gbps | $165.99/月起、$1665.99/年 | [ 购买新加坡 160G](https://bandwagonhost.com/aff.php?aff=79616&pid=175) |
| 新加坡 320G | 16GB / 8核 / 320GB / 4TB / 2.5Gbps | $329.99/月起、$3199/年 | [ 购买新加坡 320G](https://bandwagonhost.com/aff.php?aff=79616&pid=176) |
| 新加坡 640G | 32GB / 10核 / 640GB / 6TB / 5Gbps | $549.99/月起、$5549.99/年 | [ 购买新加坡 640G](https://bandwagonhost.com/aff.php?aff=79616&pid=177) |
| 新加坡 1280G | 64GB / 12核 / 1280GB / 8TB / 5Gbps | $1059.99/月起、$10559.99/年 | [ 购买新加坡 1280G](https://bandwagonhost.com/aff.php?aff=79616&pid=178) |

年付 499.99 美元，比香港和东京便宜了近一半，延迟虽然略高于这两者，但比美西机房低不少。想要亚太节点又觉得 899 美元太贵的人，一般在这两档里做选择。另外，CN2 GIA-E 套餐本身支持把机房切到大阪 JPOS_1（软银线路），联通用户反馈这条线路表现不错——如果主要诉求是“低延迟”而不是“日本原生 IP”，先用 GIA-E 切机房试试，能省不少钱。

### 迪拜套餐（中东区域业务）

| 套餐 | 内存 / CPU / SSD / 流量 / 带宽 | 价格 | 购买入口 |
| --- | --- | --- | --- |
| 迪拜 20G | 1GB / 2核 / 20GB / 0.5TB / 1Gbps | $19.99/月、$169.99/年 | [ 购买迪拜 20G](https://bandwagonhost.com/aff.php?aff=79616&pid=114) |
| 迪拜 40G | 2GB / 3核 / 40GB / 1TB / 1Gbps | $32.99/月起、$299.99/年 | [ 购买迪拜 40G](https://bandwagonhost.com/aff.php?aff=79616&pid=115) |
| 迪拜 80G | 4GB / 4核 / 80GB / 2TB / 1Gbps | $56.99/月起、$549.99/年 | [ 购买迪拜 80G](https://bandwagonhost.com/aff.php?aff=79616&pid=116) |
| 迪拜 160G | 8GB / 6核 / 160GB / 3TB / 1Gbps | $86.99/月起、$879.99/年 | [ 购买迪拜 160G](https://bandwagonhost.com/aff.php?aff=79616&pid=117) |
| 迪拜 320G | 16GB / 8核 / 320GB / 4TB / 1Gbps | $159.99/月起、$1599.99/年 | [ 购买迪拜 320G](https://bandwagonhost.com/aff.php?aff=79616&pid=118) |
| 迪拜 640G | 32GB / 10核 / 640GB / 5TB / 1Gbps | $289.99/月起、$2759.99/年 | [ 购买迪拜 640G](https://bandwagonhost.com/aff.php?aff=79616&pid=119) |
| 迪拜 1280G | 64GB / 12核 / 1280GB / 6TB / 1Gbps | $549.99/月起、$5399.99/年 | [ 购买迪拜 1280G](https://bandwagonhost.com/aff.php?aff=79616&pid=120) |

普通国际线路，业务在中东才值得考虑。

## 按用途对号入座

对着几十个套餐挑确实费劲，直接按场景收敛：

- **个人博客、企业官网、外贸站（受众在国内）**：首选 CN2 GIA-E。20G 版季付 49.99 美元试水，跑得动再加到 40G 版。
- **跨境电商、TikTok 等付费业务**：SLA 套餐，99.99% 在线率加每两周免费换 IP，这两项是普通套餐没有的。
- **游戏加速、低延迟刚需**：香港或东京 CN2 GIA，预算减半考虑大阪、新加坡。
- **学习 Linux、跑测试、纯海外业务**：KVM 常规套餐，年付 49.99 美元那台就够了。
- **预算极低**：蹲限量款，官方偶尔放出 19 美元/年级别的小内存套餐，补货即空。

## 优惠码和促销节点怎么用

搬瓦工的优惠码是循环折扣，续费同样生效，常见力度在 6% 上下。但这类码不是常驻的：2026 年 2 月短暂出现过一次全场码，两天左右就失效了。真正稳定的大促节点是每年双十一和黑色星期五，折扣力度通常大于平时的循环码。下单前值得花两分钟搜一下当月有没有可用码，没有也别硬等——GIA 系列的热门套餐经常处于缺货状态，能下单的时候未必等得到促销。

## 购买前值得知道的几件事

- **付款方式**：支持支付宝，全程不需要国外信用卡。
- **控制面板**：全套套餐使用自家的 KiwiVM 面板，支持一键重装系统、免费自动备份、快照、rDNS 设置。
- **换机房**：KVM 和 CN2 GIA-E 支持在多个机房之间免费迁移，选错了线路可以后期调。
- **退款政策**：官网承诺 30 天退款，KVM 系列在线率标注为 99.95%，SLA 系列为 99.99%。
- **流量超额**：各套餐流量按月计，套餐间差异很大，香港入门版每月 500GB 和 GIA-E 高配的 12TB 不是一回事，按实际用量选。

回到开头那个差价问题：你多付的钱，买的从来不是 CPU 和内存，是从你家到机房之间那条路的质量。想明白这一点，搬瓦工这份看起来复杂的价目表其实很好读——先定线路，再定配置，最后看钱包。
