<figure>
<img src="BL370_media/image3.jpeg" style="width:6.76597in;height:3.64861in" />
<figcaption><p>ARM工业计算机控制器技术规格书</p></figcaption>
</figure>

<figure>
<img src="BL370_media/image1.png" style="width:1.51875in;height:0.88611in" />
<figcaption><p>ARMxy BL370系列技术规格书</p></figcaption>
</figure>

|     |     |     |     |     |
|-----|-----|-----|-----|-----|
|     |     |     |     |     |
|     |     |     |     |     |

版本说明

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 19%" />
<col style="width: 18%" />
<col style="width: 43%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;">修改人</td>
<td style="text-align: center;">版本</td>
<td style="text-align: center;">日期</td>
<td style="text-align: center;">修改内容</td>
</tr>
<tr>
<td style="text-align: left;"><blockquote>
<p>Panghao</p>
</blockquote></td>
<td style="text-align: center;">V1.0</td>
<td style="text-align: center;">2024-10-19</td>
<td style="text-align: center;">初次发布</td>
</tr>
<tr>
<td style="text-align: center;">Panghao</td>
<td style="text-align: center;">V1.1</td>
<td style="text-align: center;">2026-07-15</td>
<td style="text-align: center;"><ol type="1">
<li><p>修改公司地址</p></li>
<li><p>新增复位按键自定义说明</p></li>
<li><p>新增codesys版本说明</p></li>
</ol></td>
</tr>
</tbody>
</table>

# 一、产品概述

ARMxy系列的ARM嵌入式计算机BL370系列是一款可灵活配置IO口的工业级AI边缘控制器，基于瑞芯微 RK3562/RK3562J处理器设计的四核ARM Cortex-A53 + 单核ARM Cortex-M0，主频高达1.8G/2.0GHz，搭载8/16/32GByte eMMC，1/2/4GByte LPDDR4X多种组合的RAM与ROM，支持丰富的IO接口，并且内置1TOPS算力NPU，支持深度学习。广泛应用于工业控制、边缘计算、AIoT、人工智能、通讯管理机、AGV机器人、机器视觉检测、机器人、工业物联网关、储能系统、自动化控制、交通轨道等领域。

BL370系列ARM嵌入式计算机提供1~3个可选的10/100M自适应RJ45网口、2xUSB2.0、1个可选的HDMI2.0、1个可选的X系列IO板，2个可选的Y系列IO板等丰富的接口，可用作通讯、PWM输出、脉冲计数等数据采集与控制，支持1080P@60fps H.264视频编码、4K@30fps H.265视频解码。内置Mini PCIE接口，支持蓝牙、WiFi、4G、5G模块通信。

BL370系列ARM嵌入式计算机支持Linux-5.10.198、Linux-RT-5.10.198内核，支持Ubuntu20.04、Buildroot-2021.11等操作系统、Docker容器、Node-Red以及Qt-5.15.2等图形界面开发工具。同时预装BLIoTLink工业协议转换软件用于工业数据采集与转换，快速接入各种主流物联网云平台与工业组态软件SCADA等功能；预装BLRAT远程访问工具实现远程访问与运维；预装QuickConfig快速配置工具，可以远程快速配置和调试设备，高工作效率；支持Node-Red可以快速实现物联网应用等。此外还可以通过AI辅助编写应用程序，支持“所述即所得”的编程方式。

BL370系列ARM嵌入式计算机经过专业的电气性能设计和高低温测试验证，可稳定可靠地工作在恶劣的电磁干扰与 -40~85℃温度下，DIN35导轨安装，可满足各种工业应用环境。

# 二、典型应用领域

✓ 工业控制 ✓ 储能系统EMS/BMS

✓ AIoT人工智能 ✓ 智能制造

✓ 通讯管理机 ✓ AGV机器人

✓ 机器视觉 ✓ 边缘计算

✓ 运动控制 ✓ 机器人

✓ 轨道交通 ✓ 智能设备

# 三、软硬件参数

<!-- -->

## 外观尺寸

1个网口的产品外观结构与尺寸如下图：

<img src="BL370_media/image4.jpeg" style="width:6.69375in;height:3.04792in" />

2个网口的产品外观结构与尺寸如下图：

<img src="BL370_media/image5.jpeg" style="width:4.74028in;height:2.82847in" />

3个网口的产品外观结构与尺寸如下图：

<img src="BL370_media/image6.jpeg" style="width:4.95972in;height:2.95903in" />

## 硬件参数

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 80%" />
</colgroup>
<tbody>
<tr>
<td rowspan="6">CPU</td>
<td>瑞芯微 RK3562J/RK3562，22nm</td>
</tr>
<tr>
<td><p>4x ARM Cortex-A53(64bit) +1x Cortex-M0</p>
<p>RK3562J 主频：normal mode 1.2GHz，overdrive mode 1.8GHz</p>
<p>RK3562 主频：2.0GHz</p>
<p>Cortex-M0主频：200MHz</p></td>
</tr>
<tr>
<td><p>NPU：1TOPS</p>
<p>支持 INT4/INT8/INT16/FP16</p>
<p>支持 TensorFlow/PyTorch/Caffe/MXNet 深度学习框架</p></td>
</tr>
<tr>
<td>GPU：Mali-G52-2EE，支持 OpenGL ES 1.1/2.0/3.2、OpenCL 2.0、Vulkan 1.1</td>
</tr>
<tr>
<td>Encoder：支持1080P@60fps H.264</td>
</tr>
<tr>
<td>Decoder：支持4K@30fps H.265、1080P@60fps H.264</td>
</tr>
<tr>
<td>ROM</td>
<td>8/16/32GByte eMMC</td>
</tr>
<tr>
<td>RAM</td>
<td>1/2/4GByte LPDDR4X</td>
</tr>
<tr>
<td>ETH</td>
<td>RJ-45 接口，1~3个10/100M自适应网口，ESD 3级，EFT 3级</td>
</tr>
<tr>
<td>USB</td>
<td>2x USB2.0 HOST(USB1、USB2)，速率高达 480Mbps ，ESD 3级</td>
</tr>
<tr>
<td>HDMI</td>
<td>1x HDMI2.0，支持 1080P@120fps、4K@60fps</td>
</tr>
<tr>
<td>IO槽</td>
<td><p>X系列IO板槽：1个，可选X系列IO板，支持RS485、CAN、RS232、DI、DO、GPIO等；</p>
<p>Y系列IO板槽：2个，可选Y系列IO板，支持RS485、RS232、DI、DO、继电器输出模块、AI、AO、PT100、PT1000、热电偶等。</p></td>
</tr>
<tr>
<td rowspan="2">LED</td>
<td>1x 电源指示灯</td>
</tr>
<tr>
<td>2x 用户可编程指示灯</td>
</tr>
<tr>
<td>Mini PCIE</td>
<td>1个，支持蓝牙、WiFi、4G模块等</td>
</tr>
<tr>
<td>SIMCard槽</td>
<td>1个，NANO</td>
</tr>
<tr>
<td>天线接口</td>
<td>2个，用于4G/5G/WIFI/GPS等</td>
</tr>
<tr>
<td>Debug</td>
<td>1个Micro USB调试口</td>
</tr>
<tr>
<td>SD卡槽</td>
<td>1个</td>
</tr>
<tr>
<td>复位按键</td>
<td>1个复位按键，支持自定义功能（购买前说清楚用途）</td>
</tr>
<tr>
<td>独立看门狗</td>
<td>板载独立硬件看门狗</td>
</tr>
<tr>
<td>电源</td>
<td>额定DC 24V，支持宽电压12-24VDC，具备反接保护，过流保护。2PIN带螺钉端子。</td>
</tr>
<tr>
<td>接地</td>
<td>1PIN接地连接点</td>
</tr>
<tr>
<td>安装方式</td>
<td>DIN35导轨安装、墙面固定安装</td>
</tr>
<tr>
<td>材质</td>
<td>铝合金外壳+不锈钢</td>
</tr>
<tr>
<td>尺寸</td>
<td>110*83*42mm或110*83*48mm</td>
</tr>
</tbody>
</table>

## 软件参数

<table>
<colgroup>
<col style="width: 19%" />
<col style="width: 80%" />
</colgroup>
<tbody>
<tr>
<td>内核</td>
<td>Linux-5.10.198、Linux-RT-5.10.198</td>
</tr>
<tr>
<td>操作系统</td>
<td><p>Buildroot-2021.11(Linux-5.10.198、Linux-RT-5.10.198)</p>
<p>Ubuntu 20.04</p></td>
</tr>
<tr>
<td>图形界面开发工具</td>
<td>Qt-5.15.10</td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>

## 软件生态

| **软件名称** | **类型** | **核心功能** | **主要应用场景** |
|:--:|:---|:---|:---|
| **BLIoTLink** | 自研 | 工业协议采集与转换（Modbus、BACnet、DLT645、IEC104等），对接云平台与SCADA | 楼宇自动化、工厂监控、智慧水务 |
| **Node-RED** | 开源 | 可视化流编程，拖拽构建物联网逻辑流（HTTP、MQTT、数据库等） | 边缘计算、多协议融合、自定义规则引擎 |
| **QuickConfig** | 自研 | 图形化一站式配置管理，含网络切换、系统监控、AI代码助手、远程运维 | 网关部署与运维、开发辅助 |
| **BLRAT** | 自研 | 免费远程访问工具，三步连接，多设备兼容 | 设备远程运维与访问 |
| **NEXPLC** | 自研 | 工业4.0软PLC，支持标准化编程、多语言、云对接 | 工业/楼宇/能源自动化控制 |
| **OpenPLC** | 开源 | IEC 61131-3标准软PLC，支持梯形图等5种语言 | 小型设备本地控制、安全联锁、边缘逻辑执行 |
| **FUXA** | 开源 | 基于Web的SCADA/HMI，拖拽式监控画面，支持Modbus/OPC UA/MQTT | 产线监控大屏、智慧水务、能源管理驾驶舱 |
| **Ignition** | 开源 | 集成SCADA、MES、IIoT的工业自动化平台，Web架构无客户端限制 | 工厂级中央监控与数据平台 |
| **Thingsboard IoT Gateway** | 开源 | 非IP设备（Modbus/CAN等）转MQTT/HTTP，对接Thingsboard平台 | 物联网数据采集与云桥接 |
| **Grafana** | 开源 | 时序数据可视化与分析，近百种数据源，丰富仪表盘 | 数据分析与运维监控驾驶舱 |
| **Vnode** | 开源 | 轻量级边缘计算/函数运行时，优化嵌入式环境 | 数据预处理、Node-RED补充/替代 |
| **Docker** | 开源 | 应用容器化，一键部署、隔离运行、统一管理 | 边缘多应用部署与运维 |
| **YOLOv5/8** | 开源 | 实时目标检测算法，支持自定义训练，适配边缘推理 | 工业质检、安全生产（安全帽/入侵识别）、仪表读数 |
| **OpenCV** | 开源 | 计算机视觉基础库（图像处理、特征检测、校准等） | 视觉类方案的底层算法支撑 |
| **其他** | \- | Python、C#、MySQL、SQLite等常用开发与数据组件 | 各类应用开发与数据存储 |

# 四、产品选型

ARMxy系列ARM嵌入式控制器采用灵活的设计理念，可以根据需要灵活选择不同的SOM板实现不同的ROM与RAM的组合，采用不同的X板、Y板实现丰富的IO组合，满足各种应用场景的需求。

产品命名规则为：

主机型号-SOM型号-X板型号-Y1板型号-Y2板型号-codesys版本

比如：

BL370-SOM370-X10-Pro-CR

表示1个以太网口，eMMC为8GByte，LPDDR4X为1GByte，2路RS485，-Pro-CR指带CNC+Robotics 高级运动控制功能。

如需增加WIFI，则在主型号后面加W表示，如BL370W-SOM370-X10-Pro-CR;

如需增加4G模块，则在主型号后面加L表示，如BL370L-SOM370-X10-Pro-CR。

**ARMxy BL370系列选型表**

|          |           |         |          |              |             |             |
|:--------:|:---------:|:-------:|:--------:|:------------:|:-----------:|:-----------:|
| **型号** |  **ETH**  | **USB** | **HDMI** | **X 板IO槽** | **Y板IO槽** |  **尺寸**   |
|  BL370   | 1x10/100M |    2    |    ×     |    1x6PIN    |      ×      | 42x83x110mm |
|  BL370A  | 1x10/100M |    2    |    ×     |   1x20PIN    |      ×      | 42x83x110mm |
|  BL370B  | 1x10/100M |    2    |    ×     |   1x20PIN    |      2      | 48x83x110mm |
|  BL370C  | 1x10/100M |    2    |    ×     |   1x10PIN    |      ×      | 42x83x110mm |
|  BL371   | 2x10/100M |    2    |    ×     |    1x6PIN    |      ×      | 42x83x110mm |
|  BL371A  | 2x10/100M |    2    |    ×     |   1x20PIN    |      ×      | 42x83x110mm |
|  BL371B  | 2x10/100M |    2    |    ×     |   1x20PIN    |      2      | 48x83x110mm |
|  BL372   | 3x10/100M |    2    |    1     |    1x6PIN    |      ×      | 42x83x110mm |
|  BL372A  | 3x10/100M |    2    |    1     |   1x20PIN    |      ×      | 42x83x110mm |
|  BL372B  | 3x10/100M |    2    |    1     |   1x20PIN    |      2      | 48x83x110mm |

**ARMxy BL370系列SOM选型表**

可以根据需求，选择合适的ROM、RAM以及温度等级。

|        |         |        |             |       |         |         |                |
|--------|---------|--------|-------------|-------|---------|---------|----------------|
| 型号   | MCU     | 主频   | 内核        | NPU   | eMMC    | LPDDR4X | 温度级别       |
| SOM370 | RK3562J | 1.8GHz | 4 x A53 +M0 | 1TOPS | 8GByte  | 1GByte  | 工业级 -40~85℃ |
| SOM371 | RK3562J | 1.8GHz | 4 x A53 +M0 | 1TOPS | 16GByte | 2GByte  | 工业级 -40~85℃ |
| SOM372 | RK3562J | 1.8GHz | 4 x A53 +M0 | 1TOPS | 32GByte | 4GByte  | 工业级 -40~85℃ |
| SOM373 | RK3562  | 2.0GHz | 4 x A53 +M0 | 1TOPS | 8GByte  | 1GByte  | 商业级 0~70℃   |
| SOM374 | RK3562  | 2.0GHz | 4 x A53 +M0 | 1TOPS | 16GByte | 2GByte  | 商业级 0~70℃   |
| SOM375 | RK3562  | 2.0GHz | 4 x A53 +M0 | 1TOPS | 32GByte | 4GByte  | 商业级 0~70℃   |

可以根据需求，选择合适的X系列IO板，X系列IO板的PIN数要与外壳适配。

<table>
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<tbody>
<tr>
<td colspan="7" style="text-align: center;"><strong>X系列IO板选型表</strong></td>
</tr>
<tr>
<td style="text-align: center;"><strong>型号</strong></td>
<td style="text-align: center;"><strong>RS232/RS485</strong></td>
<td style="text-align: center;"><strong>CAN</strong></td>
<td style="text-align: center;"><strong>DI</strong></td>
<td style="text-align: center;"><strong>DO</strong></td>
<td style="text-align: center;"><strong>GPIO</strong></td>
<td style="text-align: center;"><strong>PIN数</strong></td>
</tr>
<tr>
<td style="text-align: center;">X10</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">6PIN</td>
</tr>
<tr>
<td style="text-align: center;">X11</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">6PIN</td>
</tr>
<tr>
<td style="text-align: center;">X12</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">6PIN</td>
</tr>
<tr>
<td style="text-align: center;">X13</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">6PIN</td>
</tr>
<tr>
<td style="text-align: center;">X14</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">6PIN</td>
</tr>
<tr>
<td style="text-align: center;">X15</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">6PIN</td>
</tr>
<tr>
<td style="text-align: center;">X16</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">6PIN</td>
</tr>
<tr>
<td style="text-align: center;">X20</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">10PIN</td>
</tr>
<tr>
<td style="text-align: center;">X21</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">10PIN</td>
</tr>
<tr>
<td style="text-align: center;">X22</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">10PIN</td>
</tr>
<tr>
<td style="text-align: center;">X23</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">20PIN</td>
</tr>
<tr>
<td style="text-align: center;">X24</td>
<td style="text-align: center;">3</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">20PIN</td>
</tr>
<tr>
<td style="text-align: center;">X25</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">20PIN</td>
</tr>
<tr>
<td style="text-align: center;">X26</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">8</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">20PIN</td>
</tr>
<tr>
<td style="text-align: center;">X27</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">8</td>
<td style="text-align: center;">4</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">20PIN</td>
</tr>
<tr>
<td style="text-align: center;">X28</td>
<td style="text-align: center;">2</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">20PIN</td>
</tr>
<tr>
<td style="text-align: center;">X29</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">1</td>
<td style="text-align: center;">12</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">20PIN</td>
</tr>
<tr>
<td style="text-align: center;">X30</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">×</td>
<td style="text-align: center;">16</td>
<td style="text-align: center;">20PIN</td>
</tr>
</tbody>
</table>

可以根据需求，选择合适的Y系列IO板，Y系列IO模块适用于所有Y槽。

<table style="width:100%;">
<colgroup>
<col style="width: 12%" />
<col style="width: 36%" />
<col style="width: 3%" />
<col style="width: 12%" />
<col style="width: 35%" />
</colgroup>
<tbody>
<tr>
<td colspan="5" style="text-align: center;"><strong>Y系列IO板选型表</strong></td>
</tr>
<tr>
<td style="text-align: center;"><strong>型号</strong></td>
<td style="text-align: center;"><strong>描述</strong></td>
<td rowspan="14" style="text-align: center;"></td>
<td style="text-align: center;"><strong>型号</strong></td>
<td style="text-align: center;"><strong>描述</strong></td>
</tr>
<tr>
<td style="text-align: center;">Y01</td>
<td style="text-align: center;">4DI+4DO模块 NPN</td>
<td style="text-align: center;">Y41</td>
<td style="text-align: center;">4路AO模块输出 0/4~20mA</td>
</tr>
<tr>
<td style="text-align: center;">Y02</td>
<td style="text-align: center;">4DI+4DO模块 PNP</td>
<td style="text-align: center;">Y43</td>
<td style="text-align: center;">4路AO模块输出 0~5/10V</td>
</tr>
<tr>
<td style="text-align: center;">Y11</td>
<td style="text-align: center;">8路DI模块NPN</td>
<td style="text-align: center;">Y46</td>
<td style="text-align: center;">4路AO模块输出 ±5V/±10V</td>
</tr>
<tr>
<td style="text-align: center;">Y12</td>
<td style="text-align: center;">8路DI模块PNP</td>
<td style="text-align: center;">Y51</td>
<td style="text-align: center;">2路RTD模块三线PT100</td>
</tr>
<tr>
<td style="text-align: center;">Y13</td>
<td style="text-align: center;">8路干节点DI模块</td>
<td style="text-align: center;">Y52</td>
<td style="text-align: center;">2路RTD模块三线PT1000</td>
</tr>
<tr>
<td style="text-align: center;">Y21</td>
<td style="text-align: center;">8路DO模块PNP</td>
<td style="text-align: center;">Y53</td>
<td style="text-align: center;">2路RTD模块四线PT100</td>
</tr>
<tr>
<td style="text-align: center;">Y22</td>
<td style="text-align: center;">8路DO模块NPN</td>
<td style="text-align: center;">Y54</td>
<td style="text-align: center;">2路RTD模块四线PT1000</td>
</tr>
<tr>
<td style="text-align: center;">Y24</td>
<td style="text-align: center;">4路DO模块继电器</td>
<td style="text-align: center;"><del>Y56</del></td>
<td style="text-align: center;"><del>电阻测量</del></td>
</tr>
<tr>
<td style="text-align: center;">Y31</td>
<td style="text-align: center;">4路AI模块单端输入 0/4~20mA</td>
<td style="text-align: center;"><del>Y57</del></td>
<td style="text-align: center;"><del>电压测量</del></td>
</tr>
<tr>
<td style="text-align: center;">Y33</td>
<td style="text-align: center;">4路AI模块单端输入 0~5/10V</td>
<td style="text-align: center;">Y58</td>
<td style="text-align: center;">4路TC模块</td>
</tr>
<tr>
<td style="text-align: center;">Y34</td>
<td style="text-align: center;">4路AI模块差分输入 0~5/10V</td>
<td style="text-align: center;">Y63</td>
<td style="text-align: center;">4路RS485/RS232可选模块</td>
</tr>
<tr>
<td style="text-align: center;">Y36</td>
<td style="text-align: center;">4路AI模块差分输入 ±5V/±10V</td>
<td style="text-align: center;">Y95</td>
<td style="text-align: center;">4路PWM输出+4路脉冲计数（1路高速3路低速），NPN</td>
</tr>
<tr>
<td style="text-align: center;"><del>Y37</del></td>
<td style="text-align: center;"><del>4路IEPE测量模块</del></td>
<td style="text-align: center;">Y96</td>
<td style="text-align: center;">4路PWM输出+4路脉冲计数（1路高速3路低速）,PNP</td>
</tr>
</tbody>
</table>

**codesys版本**

<table>
<colgroup>
<col style="width: 21%" />
<col style="width: 78%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>版本号</strong></td>
<td style="text-align: center;"><strong>功能</strong></td>
</tr>
<tr>
<td style="text-align: center;">无</td>
<td style="text-align: center;">不带codesys功能</td>
</tr>
<tr>
<td style="text-align: center;">Pro</td>
<td style="text-align: center;"><p>(专业版)搭载 CODESYS，可选择运动控制授权(仅Pro版本可选):</p>
<p>无后缀:CODESYS 基础版，不带运动控制</p>
<p>-SM:带基本运动控制功能</p>
<p>-CR:带CNC+Robotics 高级运动控制功能</p></td>
</tr>
</tbody>
</table>

# 五、电磁兼容性测试

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 17%" />
<col style="width: 15%" />
<col style="width: 11%" />
<col style="width: 21%" />
<col style="width: 7%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>测试类别</strong></td>
<td style="text-align: center;"><strong>测试项目</strong></td>
<td style="text-align: center;"><strong>测试标准</strong></td>
<td style="text-align: center;"><strong>测试等级</strong></td>
<td style="text-align: center;"><strong>测试条件</strong></td>
<td style="text-align: center;"><strong>测试结果</strong></td>
<td style="text-align: center;"><strong>备注</strong></td>
</tr>
<tr>
<td rowspan="2" style="text-align: center;"><strong>电磁发射</strong></td>
<td style="text-align: center;">传导发射</td>
<td style="text-align: center;"><p>GB/T 9254 Class A/</p>
<p><strong>CISPR 32</strong> Class A</p></td>
<td style="text-align: center;">Class A</td>
<td style="text-align: center;">150 kHz - 30 MHz</td>
<td style="text-align: center;">合格</td>
<td style="text-align: center;">满足普通工业环境限值要求</td>
</tr>
<tr>
<td style="text-align: center;">辐射发射</td>
<td style="text-align: center;"><p>GB/T 9254 Class A/</p>
<p><strong>CISPR 32</strong> Class A</p></td>
<td style="text-align: center;">Class A</td>
<td style="text-align: center;">30 MHz - 1 GHz</td>
<td style="text-align: center;">合格</td>
<td style="text-align: center;">满足普通工业环境限值要求</td>
</tr>
<tr>
<td rowspan="6" style="text-align: center;"><strong>抗扰度测试</strong></td>
<td style="text-align: center;">静电放电（ESD）</td>
<td style="text-align: center;">GB/T 17626.2/<strong>IEC 61000-4-2</strong></td>
<td style="text-align: center;">III 级</td>
<td style="text-align: center;"><p>接触放电 +/-4 kV</p>
<p>空气放电 +/-8 kV</p></td>
<td style="text-align: center;">合格</td>
<td style="text-align: center;">—</td>
</tr>
<tr>
<td style="text-align: center;">射频辐射抗扰度</td>
<td style="text-align: center;"><p>GB/T 17626.3/</p>
<p><strong>IEC 61000-4-3</strong></p></td>
<td style="text-align: center;">III 级</td>
<td style="text-align: center;"><p>场强 10 V/m，</p>
<p>80 MHz - 1 GHz</p></td>
<td style="text-align: center;">合格</td>
<td style="text-align: center;">—</td>
</tr>
<tr>
<td style="text-align: center;">电快速瞬变脉冲群（EFT）</td>
<td style="text-align: center;">GB/T 17626.4/ <strong>IEC 61000-4-4</strong></td>
<td style="text-align: center;">III 级</td>
<td style="text-align: center;"><p>电源线 2 kV</p>
<p>信号线 1 kV</p></td>
<td style="text-align: center;">合格</td>
<td style="text-align: center;">—</td>
</tr>
<tr>
<td style="text-align: center;">浪涌（Surge）</td>
<td style="text-align: center;">GB/T 17626.5/ <strong>IEC 61000-4-5</strong></td>
<td style="text-align: center;">III 级</td>
<td style="text-align: center;"><p>差模 2 kV</p>
<p>共模 4 kV</p></td>
<td style="text-align: center;">合格</td>
<td style="text-align: center;">—</td>
</tr>
<tr>
<td style="text-align: center;">电压暂降和中断</td>
<td style="text-align: center;">GB/T 17626.11/ <strong>IEC 61000-4-11</strong></td>
<td style="text-align: center;">III 级</td>
<td style="text-align: center;"><p>电压暂降70%</p>
<p>持续500ms，</p>
<p>完全中断10 ms</p></td>
<td style="text-align: center;">合格</td>
<td style="text-align: center;">—</td>
</tr>
<tr>
<td style="text-align: center;">工频磁场抗扰度</td>
<td style="text-align: center;">GB/T 17626.8/ <strong>IEC 61000-4-8</strong></td>
<td style="text-align: center;">III 级</td>
<td style="text-align: center;"><p>测试强度30 A/m</p>
<p>工频50 Hz</p></td>
<td style="text-align: center;">合格</td>
<td style="text-align: center;">—</td>
</tr>
</tbody>
</table>

测试结论

本边缘网关设备在普通工业环境的**电磁兼容性测试**中完全符合**GB/T系列标准**的要求，具备良好的电磁兼容性能，可在工业现场稳定运行。

# 六、环境适应性测试

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 19%" />
<col style="width: 10%" />
<col style="width: 23%" />
<col style="width: 10%" />
<col style="width: 16%" />
</colgroup>
<tbody>
<tr>
<td style="text-align: center;"><strong>测试项目</strong></td>
<td style="text-align: center;"><strong>测试标准</strong></td>
<td style="text-align: center;"><strong>等级要求</strong></td>
<td style="text-align: center;"><strong>测试条件</strong></td>
<td style="text-align: center;"><strong>测试结果</strong></td>
<td style="text-align: center;"><strong>备注</strong></td>
</tr>
<tr>
<td style="text-align: center;"><strong>低温启动与运行试验</strong></td>
<td style="text-align: center;">GB/T 2423.1-2008/<strong>IEC 60068-2-1</strong></td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;"><p>环境温度 -40℃ 下，</p>
<p>设备启动并正常运行</p></td>
<td style="text-align: center;">符合要求</td>
<td style="text-align: center;">满足工业环境基本低温启动需求。</td>
</tr>
<tr>
<td style="text-align: center;"><strong>高温启动与运行试验</strong></td>
<td style="text-align: center;">GB/T 2423.2-2008/<strong>IEC 60068-2-2</strong></td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;"><p>环境温度 +85℃ 下，</p>
<p>设备启动并正常运行</p></td>
<td style="text-align: center;">符合要求</td>
<td style="text-align: center;">满足工业环境基本高温启动需求。</td>
</tr>
<tr>
<td style="text-align: center;"><strong>恒定湿热试验</strong></td>
<td style="text-align: center;">GB/T 2423.3-2016/<strong>IEC 60068-2-78</strong></td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;"><p>环境温度 +40℃，相对湿度 85%，</p>
<p>通电运行 48 小时</p></td>
<td style="text-align: center;">符合要求</td>
<td style="text-align: center;">确保设备在潮湿环境中运行稳定。</td>
</tr>
<tr>
<td style="text-align: center;"><strong>正弦振动试验</strong></td>
<td style="text-align: center;">GB/T 2423.10-2019/<strong>IEC 60068-2-6</strong></td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">频率范围5 Hz至500 Hz，加速度2g，三个轴向各10次循环</td>
<td style="text-align: center;">符合要求</td>
<td style="text-align: center;">验证设备在运输和安装过程中的抗振能力。</td>
</tr>
<tr>
<td style="text-align: center;"><strong>自由跌落试验</strong></td>
<td style="text-align: center;">GB/T 2423.7-2018/<strong>IEC 60068-2-31</strong></td>
<td style="text-align: center;">N/A</td>
<td style="text-align: center;">带包装状态下，从0.8米高度自由跌落，6 个面各跌落 1 次</td>
<td style="text-align: center;">符合要求</td>
<td style="text-align: center;">确保设备在运输过程中的抗冲击能力。</td>
</tr>
<tr>
<td style="text-align: center;"><strong>防护等级测试</strong></td>
<td style="text-align: center;">GB/T 4208-2017/<strong>IEC 60529</strong></td>
<td style="text-align: center;">IP30</td>
<td style="text-align: center;">防尘性能：防止2.5mm直径和更大的固体外来体探测器进入；</td>
<td style="text-align: center;">符合要求</td>
<td style="text-align: center;">满足工业环境的防护要求。</td>
</tr>
</tbody>
</table>

测试结论

经基本的环境适应性测试，本设备完全符合中国**GB/T 系列国家标准**的基本要求，能够在常规工业环境下稳定运行。\
以下结果确保设备满足广泛的工业应用场景：

- **低温与高温试验**：验证设备在基本工业环境下的运行能力。

- **振动与跌落试验**：确保设备在运输和安装过程中的可靠性。

- **防护等级测试**：符合工业环境基本防护需求。

# 七、出货包装

ARM嵌入式控制器一台

DIN35安装支架一套

BLIoTLink软件预装

BLRAT软件预装

Ubuntu文件系统

免压接端子按照选购配件配置

当选购了WIFI、4G、5G模块时，则会附带WIFI、4G、5G天线。

# 八、技术支持&服务

✓提供系统固化镜像、文件系统镜像、内核驱动源码，以及丰富的 Demo 程序；

✓提供完整的平台开发包、入门教程，节省软件整理时间，让应用开发更简单；

✓提供丰富的开发案例供参考，让应用开发更简单，主要包括：

➢ Linux、Linux-RT、Qt 应用开发案例

➢ BLIoTLink工业协议采集与接入云平台开发案例

➢ BLRAT远程访问使用案例

➢ Node-Red物联网应用开发案例

➢ Docker 容器技术、B 码授时、MQTT 通信协议案例

➢ Baremetal（裸机）、RT-Thread(RTOS)开发案例

➢ Cortex-A53 与 Cortex-M0 核间通信案例

➢ 图形界面开发工具 Qt-5.15.10 软件开发套件

➢ Debian、Ubuntu、Android 操作系统演示案例

➢ 基于 Debian 的 ROS 操作系统演示案例

➢ IgH EtherCAT 主站、CAN 开发案例

➢ NPU、ISP、OpenCV 开发案例

➢ 4G/5G/WIFI/蓝牙开发案例

➢ X板、Y板等外设驱动程序

✓协助进行产品二次开发；

✓定制研发与生产；

✓提供长期的售后服务。

深圳市钡铼技术有限公司

官网：https://www.bliiot.cn
