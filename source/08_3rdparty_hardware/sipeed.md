# Sipeed

## 公司简介

| 字段 | 内容 |
| --- | --- |
| 官网 | [Sipeed](https://www.sipeed.com/) |
| 简介 | Sipeed（深圳矽速科技有限公司）提供面向 AIoT、机器视觉和边缘计算的开发板、核心板及配套开发生态。M4N-Dock 是其面向多路视频和边缘 AI 场景推出的一体式计算盒。 |

## M4N-Dock（AX650N / AX8850N 边缘计算盒）

M4N-Dock 官方资料使用芯片名称 **AX650N**，其 CPU、NPU 和多媒体规格对应本站当前归类的 AX8850N 平台。为避免选型混淆，本页同时保留两个名称。

### 产品亮点与规格

| 字段 | 内容 |
| --- | --- |
| 芯片 | AX650N（AX8850N 平台）；八核 Cortex-A55 @ 1.7 GHz |
| AI 算力 | 72 TOPS@INT4 / 18 TOPS@INT8 |
| DDR | 8GB 64-bit LPDDR4x；系统内存和 AI CMM 占比可调，官方 TFCard/eMMC 镜像为模型加载预留 6GB |
| 系统存储 | 32GB eMMC 5.1 |
| SATA 扩展 | 3× SATA 3.0 6Gb/s（1× M.2、2× 标准 SATA） |
| 视频能力 | H.264/H.265 最高 8K@60fps 解码、8K@30fps 编码；实测支持 32 路 1080p@30fps 解码、16 路 1080p@30fps 编码 |
| 视频接口 | 2× HDMI 2.0a 输出，最高 4K@60fps；2× 4-lane MIPI-CSI 输入 |
| 网络 | 2× 千兆以太网，官方测试吞吐量 944Mbps |
| PCIe | Mini-PCIe 接口提供 PCIe 2.0 ×1 |
| USB | 1× USB 3.2 Gen1、3× USB 2.0；远离网口的蓝色 USB 口为 OTG 烧录口 |
| 工业接口 | 1× RS485、1× RS232、3× 用户 LED |
| 产品形态 | 一体式边缘计算盒 |
| 供电 | 正常运行必须使用 12V DC 供电，仅通过 USB 供电会导致系统不稳定 |

### 适用场景

- 多路安防视频接入、NVR、视频结构化和智能检索。
- 目标检测、行为分析、状态检测及 Transformer/视觉大模型推理。
- 需要 SATA 存储扩展的 AI NAS、智能相册和边缘存储设备。
- 带 RS485/RS232 的工业视觉、设备状态监测和边缘网关。

### SDK 编译

M4N-Dock 使用爱芯元智官方 AX650 SDK，板级编译目标为 `AX650_pipro_box`。在 SDK 根目录执行：

```bash
make p=AX650_pipro_box clean all install axp -jN
```

其中，`N` 为并行编译任务数，应根据编译主机的 CPU 和内存资源设置。编译完成后，镜像及相关产物位于：

```text
build/out/AX650_pipro_box/images
```

其他编译方式和 SDK 使用方法，请参考 [M4N-Dock 官方上手指南](https://wiki.sipeed.com/hardware/zh/maixIV/m4ndock/quick-start.html)及[《AX SDK 使用说明》](https://modelscope.cn/models/AXERA-TECH/AX650-Community-Hub/resolve/master/sdk/edge-computing-AX650_SDK_V3.10.2/01.%20Software%20Doc/board/00%20-%20AX%20SDK%20%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.pdf)。

### 资源与购买链接

- [M4N-Dock 中文产品介绍](https://wiki.sipeed.com/hardware/zh/maixIV/m4ndock/intro.html)
- [M4N-Dock 官方上手指南](https://wiki.sipeed.com/hardware/zh/maixIV/m4ndock/quick-start.html)
- [M4N-Dock 官方系统更新指南](https://wiki.sipeed.com/hardware/zh/maixIV/m4n_c-SoM/system-update.html)
- [M4N 官方 AI 模型部署教程](https://wiki.sipeed.com/hardware/zh/maixIV/m4n_c-SoM/axmodel-deploy.html)
- [硬件资料与系统镜像](https://dl.sipeed.com/shareURL/MaixIV/M4N-Dock)
- [AX SDK 使用说明](https://modelscope.cn/models/AXERA-TECH/AX650-Community-Hub/resolve/master/sdk/edge-computing-AX650_SDK_V3.10.2/01.%20Software%20Doc/board/00%20-%20AX%20SDK%20%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.pdf)
- [购买入口](https://item.taobao.com/item.htm?id=939632895211&skuId=5865914428216&spm=a1z10.3-c-s.w4002-24984917683.10.44333250QiVibB)
