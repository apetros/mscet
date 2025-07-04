+++
title = "低成本微型PMU（μPMU）的开发"
date = "2025-06-01"
authors = ["Yazhou Dong"]
tags = ["微型PMU", "相量测量单元", "低成本仪器", "电网监测"]
publication_types = [7]
publication = "_塞浦路斯理工大学_"
publication_short = ""
abstract = ""
summary = ""
featured = false
projects = []
slides = ""
url_code = ""
url_dataset = ""
url_poster = ""
url_slides = ""
url_source = ""
url_video = ""
math = true
highlight = true
[image]
image = ""
caption = ""
+++

## 概述

本硕士论文《低成本微型PMU（μPMU）的开发》介绍了一种面向电网应用的低成本微型相量测量单元（μPMU）的设计、实现与评估。作者为Yazhou Dong，论文于2024年12月提交至塞浦路斯理工大学，旨在应对现代电力配电网络对经济高效、高精度监测解决方案的日益增长需求。论文由Petros Aristidou教授指导，隶属于电气工程、计算机工程与信息学系。

论文首先介绍了电力系统监测中的挑战与机遇，强调了传统SCADA系统的局限性以及PMU的优势。文献综述部分对SCADA、传统PMU和新兴μPMU技术进行了比较分析，突出低成本高精度测量方案的最新进展与持续难题。

## 主要贡献

- **全面对比**：本论文系统比较了SCADA、PMU和μPMU技术在功能、成本和精度方面的差异，为低成本μPMU的开发提供了明确的理论依据。

- **硬件与软件设计**：详细介绍了硬件和软件组件的设计方法。硬件部分涵盖了控制单元、信号处理电路、数据采集模块和无线通信系统的选择与集成。软件部分涉及系统架构、GPS数据解析、信号采集算法和无线数据传输。

- **算法实现**：论文实现并测试了包括插值离散傅里叶变换（IPDFT）在内的先进相量测量算法，在保持系统低成本的同时提升了测量精度。

- **实验验证**：通过大量测试评估了所开发μPMU的性能，包括硬件功能测试、同步数据采集、电压电流测量精度和误差分析。对比表总结了其与现有方案的性能差异。

- **云端集成**：论文还探讨了基于云的数据管理，实现了测量数据的可扩展远程访问，这对于现代智能电网应用至关重要。

## 影响与相关性

本论文通过展示如何利用低成本硬件和开源软件实现高精度相量测量，为电力系统监测领域做出了重要贡献。这为中小型公用事业和预算有限的发展中地区普及先进电网监测技术提供了可能。

论文为硬件和软件的详细设计提供了蓝图，为有意在实际配电网络中部署μPMU的研究人员和工程师提供了宝贵参考。云端集成进一步契合了数字化和智能电网发展的趋势。

本研究通过提供经过验证、可扩展且经济实用的PMU替代方案，填补了文献空白。其成果有望加速μPMU的应用，提高电网可靠性，并通过增强态势感知和数据驱动决策支持可再生能源的集成。
