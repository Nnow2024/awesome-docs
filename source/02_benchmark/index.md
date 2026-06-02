# 性能与基准测试

本章收录 AXERA 芯片在 CNN/Transformer 和大模型 (LLM/VLM) 上的性能数据，并记录 OS:CMM、卡端 DDR、固件/驱动等影响复现的关键资源信息。

当前状态：测试框架已定义，数据持续补充中。已有数据以 [ax-samples](https://github.com/AXERA-TECH/ax-samples) 为基础。

```{toctree}
:maxdepth: 1

overview
cnn_transformer
llm_vlm
```

## 本章内容

- **Benchmark 综述**：测试方法、环境与数据口径说明。
- **普通 CNN/Transformer 性能**：典型视觉模型推理速度与能效比。
- **LLM/VLM 专项性能**：解码速度 (Tokens/s)、首字延迟、并发路数、显存占用。
