# M5Stack

## 公司简介

| 字段 | 内容 |
| --- | --- |
| 官网 | [M5Stack](https://m5stack.com/) |
| 简介 | M5Stack 面向开发者提供模块化开源硬件、边缘计算设备及配套软件生态。本页收录其基于 AX8850 的一体式 AI 计算盒和 M.2 AI 算力卡套件。 |

## AI Pyramid Pro（AX8850 AI 计算盒）

AI Pyramid Pro 是一款面向本地 AI 推理和边缘智能部署的一体式计算盒。设备集成 AX8850、内存、eMMC、网络、音视频、散热和状态显示模块，可直接作为边缘 AI 主机使用。

### 产品亮点与规格

| 字段 | 内容 |
| --- | --- |
| 芯片 | AX8850；八核 Cortex-A55 @ 1.7 GHz |
| AI 算力 | 24 TOPS@INT8 |
| DDR | 8GB 64-bit LPDDR4x 4266 Mbps；默认 4GB 系统内存 + 4GB AI/多媒体专用内存 |
| 存储 | 32GB eMMC 5.1、microSD 卡槽；机内预留 M.2 M-Key 2242/2230 接口 |
| 视频能力 | H.264/H.265 8K@30fps 编解码，支持 16 路 1080p 并行解码 |
| 显示与采集 | 2× HDMI 2.0（1× 输入、1× 输出），最高 4K@60fps |
| 网络 | 2× 千兆以太网 |
| USB 与扩展 | 4× USB-A 3.0（3× 外置、1× 内置）、2× USB Type-C、2× HY2.0-4P |
| 音频与交互 | ES8311 音频编解码、ES7210 四麦输入、扬声器、OLED、按键、48 颗 RGB LED |
| 散热 | 涡轮风扇，EC 智能温控 |
| 产品形态 | 一体式边缘 AI 计算盒 |
| 供电 | USB PD 输入，至少 9V@3A（27W）；5V 电源无法启动设备 |

```{note}
8GB 版本默认并非全部作为 Linux 系统内存使用，而是按“4GB 系统内存 + 4GB AI/多媒体专用内存”划分。评估可加载模型大小前，应先确认当前固件的内存划分。
```

### 适用场景

- 本地 LLM/VLM、语音识别、语音合成和多模态交互。
- Frigate 智能安防、Immich 智能相册、Home Assistant 等本地化服务。
- AI 视觉网关、多路视频分析、硬件编解码和转码。
- 桌面 AI PC、会议转录、离线助手和边缘智能终端原型验证。

### 上手注意事项

1. 使用支持 USB PD、输出不低于 9V@3A 的电源适配器，不能使用普通 5V USB 电源。
2. 首次使用时，按[AI Pyramid 官方快速上手教程](https://docs.m5stack.com/zh_CN/stackflow/ai_pyramid/getting_started)完成开关机、联网、OLED 查看 IP、SSH 登录和桌面 GUI 连接；镜像更新及内存划分方法以产品文档为准。
3. 如需在机内安装带高散热器的 M.2 设备，应先确认外壳净空，避免散热器与结构件干涉。
5. AI Pyramid 的内核和U-boot未合入官方SDK，如需修改内核和U-boot参考请参考[module_650_linux](https://github.com/dianjixz/module_650_linux) 和 [module_650_uboot](https://github.com/dianjixz/module_650_uboot)。

### 资源与购买链接

- [官方产品文档](https://docs.m5stack.com/zh_CN/ai_hardware/AI_Pyramid-Pro)
- [AI Pyramid 官方快速上手教程](https://docs.m5stack.com/zh_CN/stackflow/ai_pyramid/getting_started)
- [淘宝购买页面](https://item.taobao.com/item.htm?id=1020552657844&spm=a1z10.5-c-s.w4002-25874091579.15.49dc6198wJo5H1)

## AI-8850 LLM Acceleration M.2 Kit（4GB，AX8850）

该套件由 LLM-8850 Card 和 LLM-8850 PiHat 转接板组成，面向 Raspberry Pi 5 等带 PCIe 扩展能力的主机。核心算力卡采用 M.2 M-Key 2242 形态，通过 AXCL Runtime 向主机提供 AI 推理和视频编解码能力。

### 产品亮点与规格

| 字段 | 内容 |
| --- | --- |
| 芯片 | AX8850；八核 Cortex-A55 @ 1.7 GHz |
| AI 算力 | 24 TOPS@INT8 |
| DDR | 4GB 64-bit LPDDR4x 4266 Mbps（官方标注为 2GB + 2GB） |
| 启动存储 | 32Mbit QSPI NOR Flash，仅用于 Bootloader |
| 主机接口 | M.2 M-Key 2242，PCIe 2.0 ×2，可向下兼容 PCIe ×1 |
| 视频能力 | H.264/H.265 8K@30fps 编解码，支持 16 路 1080p 并行解码 |
| 散热 | 微型涡轮风扇 + CNC 铝合金散热器，EC 智能温控 |
| 产品形态 | M.2 算力卡 + Raspberry Pi 5 PiHat 转接板套件 |
| 算力卡功耗 | 7W@3.3V |
| 套件供电 | 通过 PiHat 的 USB PD 接口供电，要求 9V@3A（27W）以上 |

### 适用场景

- Raspberry Pi 5 的本地 AI 算力扩展。
- 多模态大模型、语音模型、目标检测和嵌入式视频分析。
- NVR/NAS 智能化改造、机器人感知和边缘 AI 网关。
- 在 ARM 或 x86 主机上验证 AXCL C/Python API。

### 上手注意事项

1. 本套件应从 PiHat 的 USB Type-C PD 接口为整套系统供电，不要从 Raspberry Pi 5 一侧反向供电。
2. 主机必须提供可用的 PCIe M.2 M-Key 通道；M.2 插槽的外形兼容不代表 NVMe 协议设备与本卡可以互换。
3. Raspberry Pi 5 的 PCIe 中断资源有限，部分多路 M.2 转接板无法同时连接 SSD 与算力卡，选购转接板前应查看官方兼容性说明。
4. 按[LLM-8850 Card 官方使用指南](https://docs.m5stack.com/zh_CN/guide/ai_accelerator/overview)依次完成硬件安装、环境配置和快速体验；该指南还提供视觉、大语言、多模态、音频和生成模型示例，以及 Frigate、Immich、OpenAI API、性能基准和常见问题等内容。
5. 官方文档列出的系统包括 Ubuntu 20.04/22.04/24.04、Debian 12/13 和 Windows 10/11；macOS、WSL、VMware、VirtualBox 不在支持范围内。

### 资源与购买链接

- [LLM-8850 Kit 官方文档](https://docs.m5stack.com/zh_CN/ai_hardware/LLM-8850_Kit)
- [LLM-8850 Card 官方文档](https://docs.m5stack.com/zh_CN/ai_hardware/LLM-8850_Card)
- [LLM-8850 Card 官方使用指南](https://docs.m5stack.com/zh_CN/guide/ai_accelerator/overview)
- [4GB 套件淘宝购买页面](https://item.taobao.com/item.htm?id=1058621793811&spm=a1z10.5-c-s.w4002-25874091579.17.49dc6198wJo5H1)
