# 大模型类算法

本页列出已在爱芯 NPU 平台完成适配的大语言模型 (LLM) 和视觉语言模型 (VLM)。所有模型均可通过 AXERA 模型仓库（[Hugging Face](https://huggingface.co/AXERA-TECH) | [ModelScope](https://modelscope.cn/organization/AXERA-TECH)）下载预编译 axmodel，使用 [ax-llm](https://github.com/AXERA-TECH/ax-llm) 运行时部署。

运行示例与上板命令见 [示例展示](samples_board.md)。

## LLM（文本大模型）

### Qwen3.5 系列

- Qwen3.5-0.8B-AX650-C128-P1152-CTX2047：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-0.8B-AX650-C128-P1152-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-0.8B-AX650-C128-P1152-CTX2047)
- Qwen3.5-0.8B-AX650-GPTQ-Int4-C128-P1152-CTX2047：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-0.8B-AX650-GPTQ-Int4-C128-P1152-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-0.8B-AX650-GPTQ-Int4-C128-P1152-CTX2047)
- Qwen3.5-0.8B-AX650-GPTQ-Int4-C256-P6K-CTX8K：W4A16 长上下文 8K，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-0.8B-AX650-GPTQ-Int4-C256-P6K-CTX8K) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-0.8B-AX650-GPTQ-Int4-C256-P6K-CTX8K)
- Qwen3.5-0.8B-AX650-C256-P6K-CTX8K：W8A16 长上下文 8K，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-0.8B-AX650-C256-P6K-CTX8K) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-0.8B-AX650-C256-P6K-CTX8K)
- Qwen3.5-2B-AX650-C128-P1152-CTX2047：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-2B-AX650-C128-P1152-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-2B-AX650-C128-P1152-CTX2047)
- Qwen3.5-2B-AX650-GPTQ-Int4-C128-P1152-CTX2047：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-2B-AX650-GPTQ-Int4-C128-P1152-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-2B-AX650-GPTQ-Int4-C128-P1152-CTX2047)
- Qwen3.5-2B-AX650-GPTQ-Int4-C256-P6K-CTX8K：W4A16 长上下文 8K，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-2B-AX650-GPTQ-Int4-C256-P6K-CTX8K) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-2B-AX650-GPTQ-Int4-C256-P6K-CTX8K)
- Qwen3.5-4B-AX650-GPTQ-Int4-C128-P1152-CTX2047：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-4B-AX650-GPTQ-Int4-C128-P1152-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-4B-AX650-GPTQ-Int4-C128-P1152-CTX2047)
- Qwen3.5-4B-AX650-GPTQ-Int4-C256-P10K-CTX12K：W4A16 长上下文 12K，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-4B-AX650-GPTQ-Int4-C256-P10K-CTX12K) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-4B-AX650-GPTQ-Int4-C256-P10K-CTX12K)
- Qwen3.5-4B-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-4B-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-4B-GPTQ-Int4)

### Qwen3 系列

- Qwen3-0.6B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-0.6B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-0.6B)
- Qwen3-0.6B-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-0.6B-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-0.6B-GPTQ-Int4)
- Qwen3-0.6B-AX637：AX637 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-0.6B-AX637) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-0.6B-AX637)
- Qwen3-1.7B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-1.7B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-1.7B)
- Qwen3-1.7B-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-1.7B-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-1.7B-GPTQ-Int4)
- Qwen3-4B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-4B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-4B)
- Qwen3-4B-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-4B-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-4B-GPTQ-Int4)
- Qwen3-4B-Instruct-2507-GPTQ-Int8：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-4B-Instruct-2507-GPTQ-Int8) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-4B-Instruct-2507-GPTQ-Int8)
- Qwen3-4B-Instruct-2507-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-4B-Instruct-2507-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-4B-Instruct-2507-GPTQ-Int4)

### Qwen2.5 系列

- Qwen2.5-0.5B-Instruct-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-0.5B-Instruct-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-0.5B-Instruct-GPTQ-Int4)
- Qwen2.5-0.5B-Instruct-CTX-Int8：W8A16 长上下文，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-0.5B-Instruct-CTX-Int8) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-0.5B-Instruct-CTX-Int8)
- Qwen2.5-1.5B-Instruct：W8A16 / W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-1.5B-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-1.5B-Instruct)
- Qwen2.5-1.5B-Instruct-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-1.5B-Instruct-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-1.5B-Instruct-GPTQ-Int4)
- Qwen2.5-3B-Instruct：W8A16 / W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-3B-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-3B-Instruct)
- Qwen2.5-3B-Instruct-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-3B-Instruct-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-3B-Instruct-GPTQ-Int4)
- Qwen2.5-7B-Instruct：W8A16 / W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-7B-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-7B-Instruct)
- Qwen2.5-7B-Instruct-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-7B-Instruct-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-7B-Instruct-GPTQ-Int4)
- Qwen2.5-7B-Instruct-TensorParallel：多芯级联，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-7B-Instruct-TensorParallel) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-7B-Instruct-TensorParallel)

### DeepSeek-R1-Distill 系列

- DeepSeek-R1-Distill-Qwen-1.5B：W8A16 / W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/DeepSeek-R1-Distill-Qwen-1.5B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/DeepSeek-R1-Distill-Qwen-1.5B)
- DeepSeek-R1-Distill-Qwen-1.5B-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/DeepSeek-R1-Distill-Qwen-1.5B-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/DeepSeek-R1-Distill-Qwen-1.5B-GPTQ-Int4)
- DeepSeek-R1-Distill-Qwen-7B：W8A16 / W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/DeepSeek-R1-Distill-Qwen-7B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/DeepSeek-R1-Distill-Qwen-7B)
- DeepSeek-R1-Distill-Qwen-7B-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/DeepSeek-R1-Distill-Qwen-7B-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/DeepSeek-R1-Distill-Qwen-7B-GPTQ-Int4)

### MiniCPM 系列

- MiniCPM4-0.5B：W8A16，AX650 / AX630C | [HuggingFace](https://huggingface.co/AXERA-TECH/MiniCPM4-0.5B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/MiniCPM4-0.5B)
- MiniCPM5-1B：AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/MiniCPM5-1B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/MiniCPM5-1B)

### SmolLM 系列

- SmolLM2-360M-Instruct：W8A16，AX650 / AX630C | [HuggingFace](https://huggingface.co/AXERA-TECH/SmolLM2-360M-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/SmolLM2-360M-Instruct)
- SmolLM3-3B：AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/SmolLM3-3B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/SmolLM3-3B)

### Gemma 系列

- gemma-4-E2B-it：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/gemma-4-E2B-it) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/gemma-4-E2B-it)
- gemma-4-E2B-it-GPTQ-INT4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/gemma-4-E2B-it-GPTQ-INT4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/gemma-4-E2B-it-GPTQ-INT4)
- Gemma-3-1B-it-AX650：AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Gemma-3-1B-it-AX650) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Gemma-3-1B-it-AX650)
- gemma-3-270m-it-gptq-int4-ax620e：W4A16，AX620E | [HuggingFace](https://huggingface.co/AXERA-TECH/gemma-3-270m-it-gptq-int4-ax620e-c128-p512-ctx768) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/gemma-3-270m-it-gptq-int4-ax620e-c128-p512-ctx768)

### 翻译

- HY-MT1.5-1.8B_GPTQ_INT4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/HY-MT1.5-1.8B_GPTQ_INT4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/HY-MT1.5-1.8B_GPTQ_INT4)
- HY-MT1.5-1.8B_GPTQ_INT4-AX620E：W4A16，AX620E | [HuggingFace](https://huggingface.co/AXERA-TECH/HY-MT1.5-1.8B_GPTQ_INT4-AX620E) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/HY-MT1.5-1.8B_GPTQ_INT4-AX620E)

### Embedding

- Qwen3-Embedding-0.6B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-Embedding-0.6B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-Embedding-0.6B)
- Qwen3-Embedding-0.6B-GPTQ-Int8：GPTQ-Int8，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-Embedding-0.6B-GPTQ-Int8) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-Embedding-0.6B-GPTQ-Int8)
- jina-embeddings-v5-omni-small：AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/jina-embeddings-v5-omni-small) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/jina-embeddings-v5-omni-small)

## VLM（视觉语言模型）

### Qwen3.5-VL（多模态）

- Qwen3.5-0.8B-AX650-C128-P1152-CTX2047：W8A16 图文，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-0.8B-AX650-C128-P1152-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-0.8B-AX650-C128-P1152-CTX2047)
- Qwen3.5-0.8B-AX650-GPTQ-Int4-C128-P1152-CTX2047：W4A16 图文，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-0.8B-AX650-GPTQ-Int4-C128-P1152-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-0.8B-AX650-GPTQ-Int4-C128-P1152-CTX2047)
- Qwen3.5-2B-AX650-GPTQ-Int4-C128-P1152-CTX2047：W4A16 图文，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-2B-AX650-GPTQ-Int4-C128-P1152-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-2B-AX650-GPTQ-Int4-C128-P1152-CTX2047)
- Qwen3.5-4B-AX650-GPTQ-Int4-C128-P1152-CTX2047：W4A16 图文/视频，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3.5-4B-AX650-GPTQ-Int4-C128-P1152-CTX2047) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3.5-4B-AX650-GPTQ-Int4-C128-P1152-CTX2047)

### Qwen3-VL 系列

- Qwen3-VL-2B-Instruct：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-VL-2B-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-VL-2B-Instruct)
- Qwen3-VL-2B-Instruct-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-VL-2B-Instruct-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-VL-2B-Instruct-GPTQ-Int4)
- Qwen3-VL-2B-Instruct-GPTQ-Int4-AX630C：W4A16，AX630C | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-VL-2B-Instruct-GPTQ-Int4-AX630C) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-VL-2B-Instruct-GPTQ-Int4-AX630C)
- Qwen3-VL-4B-Instruct：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-VL-4B-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-VL-4B-Instruct)
- Qwen3-VL-4B-Instruct-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-VL-4B-Instruct-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-VL-4B-Instruct-GPTQ-Int4)
- Qwen3-VL-8B-Instruct：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-VL-8B-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-VL-8B-Instruct)
- Qwen3-VL-8B-Instruct-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-VL-8B-Instruct-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-VL-8B-Instruct-GPTQ-Int4)
- Qwen3-VL-8B-Instruct-GPTQ-Int4-AX650-C128-P1152-CTX2047-TP4：W4A16 四芯 TensorParallel，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-VL-8B-Instruct-GPTQ-Int4-AX650-C128-P1152-CTX2047-TP4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-VL-8B-Instruct-GPTQ-Int4-AX650-C128-P1152-CTX2047-TP4)

### Qwen2.5-VL 系列

- Qwen2.5-VL-3B-Instruct：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-VL-3B-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-VL-3B-Instruct)
- Qwen2.5-VL-3B-Instruct-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-VL-3B-Instruct-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-VL-3B-Instruct-GPTQ-Int4)
- Qwen2.5-VL-7B-Instruct：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen2.5-VL-7B-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen2.5-VL-7B-Instruct)

### InternVL 系列

- InternVL2_5-1B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/InternVL2_5-1B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/InternVL2_5-1B)
- InternVL2_5-1B-MPO：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/InternVL2_5-1B-MPO) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/InternVL2_5-1B-MPO)
- InternVL3-1B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/InternVL3-1B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/InternVL3-1B)
- InternVL3-2B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/InternVL3-2B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/InternVL3-2B)
- InternVL3_5-1B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/InternVL3_5-1B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/InternVL3_5-1B)
- InternVL3_5-1B_GPTQ_INT4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/InternVL3_5-1B_GPTQ_INT4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/InternVL3_5-1B_GPTQ_INT4)
- InternVL3_5-2B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/InternVL3_5-2B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/InternVL3_5-2B)
- InternVL3_5-2B_GPTQ_INT4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/InternVL3_5-2B_GPTQ_INT4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/InternVL3_5-2B_GPTQ_INT4)

### MiniCPM-V 系列

- MiniCPM-V-4.6：BF16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/MiniCPM-V-4.6) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/MiniCPM-V-4.6)
- MiniCPM-V-4.6-GPTQ：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/MiniCPM-V-4.6-GPTQ) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/MiniCPM-V-4.6-GPTQ)

### FastVLM 系列

- FastVLM-0.5B：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/FastVLM-0.5B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/FastVLM-0.5B)
- FastVLM-1.5B：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/FastVLM-1.5B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/FastVLM-1.5B)
- FastVLM-1.5B-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/FastVLM-1.5B-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/FastVLM-1.5B-GPTQ-Int4)

### SmolVLM 系列

- SmolVLM-256M-Instruct：W8A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/SmolVLM-256M-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/SmolVLM-256M-Instruct)
- SmolVLM2-256M-Video-Instruct：W8A16 视频理解，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/SmolVLM2-256M-Video-Instruct_Ax650) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/SmolVLM2-256M-Video-Instruct_Ax650)
- SmolVLM2-500M-Video-Instruct：W8A16 视频理解，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/SmolVLM2-500M-Video-Instruct) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/SmolVLM2-500M-Video-Instruct)

### 其他 VLM

- Janus-Pro-1B：W8A16 图像理解+生成，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Janus-Pro-1B) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Janus-Pro-1B)
- PaddleOCR-VL-1.5：W4A16 端到端 OCR，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/PaddleOCR-VL-1.5) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/PaddleOCR-VL-1.5)
- Xiaomi-MiMo-VL-Miloco-7B-AX650-GPTQ-Int4：W4A16，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Xiaomi-MiMo-VL-Miloco-7B-AX650-GPTQ-Int4) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Xiaomi-MiMo-VL-Miloco-7B-AX650-GPTQ-Int4)
- Qwen3-VL-Embedding-2B：视觉 Embedding，AX650 | [HuggingFace](https://huggingface.co/AXERA-TECH/Qwen3-VL-Embedding-2B-AX650-C128_P1280_CTX1407) | [ModelScope](https://modelscope.cn/models/AXERA-TECH/Qwen3-VL-Embedding-2B-AX650-C128_P1280_CTX1407)

## ax-llm 运行时

[ax-llm](https://github.com/AXERA-TECH/ax-llm) 为 AX650/AX8850 平台提供 LLM/VLM 推理运行时，支持 CLI 交互和 OpenAI 兼容 API 服务。

安装方式和具体使用请参考 [示例展示](samples_board.md)。
