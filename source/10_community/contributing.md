# 文档共创指南

本仓库由原厂、社区开发者和板卡厂家共同维护。以下是参与贡献的流程和规则。

## 贡献方式

### 提交 Issue

发现内容错误、链接失效或有补充建议，请到
[awesome-docs Issues](https://github.com/AXERA-TECH/awesome-docs/issues) 提交。

### 提交 Pull Request

1. Fork 本仓库。
2. 基于 `dev` 分支创建特性分支（如 `feat/m5stack-llm8850`）。
3. 修改对应章节的 Markdown 文件。
4. 本地构建预览确认无误（见下文）。
5. 提交 PR 到本仓库的 **`dev`** 分支，描述改动内容。

```{note}
请勿直接提交到 `main` 分支。`main` 为稳定上线版本，所有改动先经 `dev` 集成验证。
```

## 目录与命名约定

- 每个章节为一个目录（`01_overview` ~ `08_community`），目录内 `index.md` 为章节入口。
- 新增页面使用小写下划线命名（如 `quick_start.md`）。
- 未完成内容用 `> 待补充：...` 标注。

## 本地构建预览

```bash
pip install -r requirements.txt
make clean && make html
# 打开 build/html/index.html 或：
python -m http.server 8200 --directory build/html
```

## 板卡厂家分权维护

[生态硬件](../08_3rdparty_hardware/index.md) 章节由各板卡厂家维护自家页面，要求：

- 用户无需原厂介入即可独立完成上板和性能评估；
- 内容包含：公司简介、产品亮点与规格、适用场景、资源/购买链接。

## 内容补充原则

多数资料已分散在 GitHub、Huggingface、知乎等渠道。贡献时先补充链接，再逐步扩充必要的正文内容。
