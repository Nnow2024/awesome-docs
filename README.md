# awesome-docs 使用手册

[**在线文档预览**](https://awesome-npu-docs.readthedocs.io/zh-cn/latest/index.html#)

## 1. 项目背景

**awesome-docs** 是为了方便基于 AX650N DEMO Board（16+64GB）客户推广使用时快速评估 NPU 特性使用。

- 指导搭建评估 NPU 示例必要的系统软件环境;
- 指导搭建评估 NPU 示例必要的软件依赖环境;
- 各种 NPU 示例获取及上板运行示例；
- 促进社区开发人员共同维护文档。

## 2. 本地编译指南

### 2.1 git clone

```bash
git clone https://github.com/AXERA-TECH/awesome-docs.git
cd awesome-docs
```

### 2.2 编译中文文档

安装依赖：

```bash
pip install -r requirements.txt
```

在项目根目录下执行：

```bash
make clean
make html
```

编译后，使用浏览器打开 `build/html/index.html`。

### 2.3 编译英文文档

英文文档通过 Sphinx gettext 工作流生成：

```bash
# 提取可翻译文本并更新英文 .po 文件
make intl

# 翻译 locale/en/LC_MESSAGES/*.po 中的 msgstr

# 编译英文文档
make html-en
```

编译后，使用浏览器打开 `build/html-en/index.html`。

### 2.4 本地预览

```bash
make serve
```

默认访问地址：`http://localhost:8200/`。

## 3. 参考设计

这个项目基于 Sphinx，更多信息见 https://www.sphinx-doc.org/en/master/。

## 4. 在线发布

基于 [Read the Docs](https://readthedocs.org/) 平台发布在线 Web 服务。
