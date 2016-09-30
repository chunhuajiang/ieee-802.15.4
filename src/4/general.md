# 4. 通用描述
## 4.1 概述
　　LR-WPAN 网络是一种结构简单、成本低廉的无线通信网络，它使得在低电能和低吞吐量的应用环境中使用无线连接成为可能。LR-WPAN 的主要目标是维护一个简单、灵活的协议，且实现安装简便、数据可靠传输、短距离操作，**低成本**，**长寿命**的功能。

　　本标准具有如下特性：

　　―― 支持星型和对等两种网络拓扑结构

　　―― 有 16 位短地址和 64 位扩展地址两种模式

　　―― 可选的 GTS 功能

　　―― 使用载波侦听多路访问/冲突避免(CSMA/CA) 或 ALOHA 访问信道

　　―― 支持确认（ACK）机制，保证传输可靠性

　　―― 低功耗
  
　　―― 能量检测 ED
  
　　―― 链路质量指示 LQI

　　本标准在多个频带范围内定义了多个 PHY 操作，详见 8.1.1 节。

　　IEEE 802.15.4 有两种设备：完整功能设备 FFD（full-function device）和简化功能设备 RFD（reduced-function device）。FFD 既可以与 FFD 通信，又可以与 RFD 通信；RFD 只能和 FFD 通信。RFD 设备主要用于简单的控制应用，如灯的开关、被动式红外线传感器等，传输的数据量较少，对传输资源和通信资源占用不多，这样 RFD 设备可以采用非常廉价的实现方案。

---

　　**本节专有名词**

 简写 | 英文全称 | 中文全称
 ---- | ---- | ----
 LR-WPAN | low rate wireless personal area network | 低速无线个人区域网
 GTS | guaranteed time slot| 有保证的时隙
 CSMA-CA  | carrier sense multiple access with collision avoidance | 载波侦听多路访问/冲突避免
 ED  | energy detection | 能量检测
 LQI  | link quality indication | 链路质量指示
 RFD |reduced-function device| 简化功能设备
 FFD |full-function device|	完整功能设备
  ALOHA || 
