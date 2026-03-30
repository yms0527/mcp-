<div align="center">

# 🌐 MCP服务器与MCP攻击数据集

**Model Context Protocol 服务器集合与安全攻击样本**

[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![简体中文](https://img.shields.io/badge/简体中文-点击查看-orange)](README-zh.md)
[![繁體中文](https://img.shields.io/badge/繁體中文-點擊查看-orange)](README-zh_TW.md)
[![日本語](https://img.shields.io/badge/日本語-クリック-blue)](README-ja.md)
[![한국어](https://img.shields.io/badge/한국어-클릭-yellow)](README-ko.md)

</div>

---

## 📑 目录

- [什么是 MCP?](#什么是-mcp)
- [支持的客户端](#支持的客户端)
- [服务器分类](#服务器分类)
- [攻击分类](#攻击分类)

---

## 🤖 什么是 MCP?

**MCP (Model Context Protocol，模型上下文协议)** 是一个开放协议，旨在实现AI模型与外部数据源、工具和服务之间的无缝集成。由Anthropic开发，MCP标准化了AI助手访问和交互各种能力的方式，使扩展AI功能变得更加简单。

主要特性：

- 🔗 **标准化集成**：连接AI与外部工具的通用接口
- 🛠️ **工具发现**：动态发现和使用可用功能
- 🔒 **安全优先**：内置安全考虑，确保工具执行安全
- 🌐 **跨平台**：适用于不同的AI客户端和框架

---

## 💻 支持的客户端

<div align="center">

| 客户端                                                                                                | 支持     | 描述             |
| -------------------------------------------------------------------------------------------------- | ------ | -------------- |
| ![Claude](https://img.shields.io/badge/Claude-Anthropic-CC785C?style=flat-square&logo=anthropic)   | ✅ 完全支持 | Anthropic的AI助手 |
| ![Cursor](https://img.shields.io/badge/Cursor-Editor-000000?style=flat-square)                     | ✅ 完全支持 | AI驱动的代码编辑器     |
| ![Windsurf](https://img.shields.io/badge/Windsurf-IDE-6366F1?style=flat-square)                    | ✅ 完全支持 | AI原生IDE        |
| ![Cline](https://img.shields.io/badge/Cline-VSCode-007ACC?style=flat-square&logo=visualstudiocode) | ✅ 完全支持 | VS Code AI助手   |
| ![LangChain](https://img.shields.io/badge/LangChain-Framework-1C3C3C?style=flat-square)            | ✅ 完全支持 | LLM应用框架        |

</div>

---

## 📁 服务器分类

<div align="center">

### 🔗 34个分类

</div>

### 🧠 AI与大语言模型集成

| 图标  | 分类                 | 描述            |
|:---:|:------------------ |:------------- |
| 🤖  | `ai/`              | 通用AI工具和实用程序   |
| 🔗  | `langchain/`       | LangChain框架集成 |
| 🦙  | `llama/`           | Llama模型集成     |
| 🧩  | `llm-integration/` | 通用大语言模型集成工具   |
| 🧮  | `mathgpt/`         | 数学GPT模型       |
| 🔢  | `math-assistant/`  | 数学助手工具        |

### 🛠️ 开发工具

| 图标  | 分类                    | 描述             |
|:---:|:--------------------- |:-------------- |
| 💻  | `developer-tools/`    | 开发者工具和SDK      |
| 📘  | `bucket_typescript/`  | TypeScript相关工具 |
| 🕷️ | `firecrawl/`          | 网页抓取和爬取工具      |
| 🌐  | `browser-automation/` | 浏览器自动化解决方案     |

### 🏢 生产力与工作场所

| 图标  | 分类                          | 描述        |
|:---:|:--------------------------- |:--------- |
| 💼  | `Workplace_&_Productivity/` | 工作场所生产力工具 |
| 📈  | `productivity-tools/`       | 通用生产力工具   |
| 📅  | `calendar-management/`      | 日历和日程安排工具 |
| ⏰   | `time/`                     | 时间管理工具    |
| 🌍  | `timezone/`                 | 时区转换工具    |

### 📊 数据与分析

| 图标  | 分类                      | 描述       |
|:---:|:----------------------- |:-------- |
| 📈  | `data-analysis/`        | 数据分析和可视化 |
| 🧠  | `knowledge-and-memory/` | 知识库和记忆系统 |
| 📄  | `content-extraction/`   | 内容提取工具   |
| 🔍  | `research/`             | 研究和学术工具  |

### ☁️ 云与基础设施

| 图标  | 分类                 | 描述         |
|:---:|:------------------ |:---------- |
| ☁️  | `Cloud_Platforms/` | 云服务集成      |
| 🗄️ | `redis/`           | Redis数据库工具 |
| 🔒  | `security/`        | 安全和认证工具    |
| 🔎  | `search-api/`      | 搜索API集成    |

### 💬 通信与媒体

| 图标  | 分类                | 描述           |
|:---:|:----------------- |:------------ |
| 💬  | `Communication/`  | 通信和消息工具      |
| 🔊  | `text-to-speech/` | 文本转语音和语音合成工具 |

### 🏭 行业应用

| 图标  | 分类               | 描述         |
|:---:|:---------------- |:---------- |
| 💰  | `finance/`       | 金融和银行工具    |
| 📢  | `Marketing/`     | 营销和分析工具    |
| 🎮  | `Gaming/`        | 游戏开发和游戏工具  |
| ⚽   | `Sports/`        | 体育和健身工具    |
| 🏠  | `Real_Estate/`   | 房地产和物业工具   |
| 🚚  | `Delivery/`      | 配送和物流工具    |
| 🎨  | `Art_&_Culture/` | 艺术、文化和创意工具 |

### 🎨 其他工具

| 图标  | 分类                              | 描述               |
|:---:|:------------------------------- |:---------------- |
| 🔧  | `Other_Tools_and_Integrations/` | 杂项工具             |
| 🏄  | `windsurf/`                     | Windsurf IDE特定工具 |

---

## ⚠️ 攻击分类

<div align="center">

### 📡 传输层攻击

</div>

```
🔑 凭证泄露/               - 凭证泄露
```

<div align="center">

### 🧠 决策层攻击

</div>

```
🎯 工具偏好操纵攻击/         - 工具偏好操纵攻击
🎭 傀儡攻击/               - 傀儡攻击
⚡ 工具抢占攻击/            - 工具抢占攻击
🔨 工具链开发攻击/          - 工具链开发攻击
💬 提示词注入攻击/          - 提示词注入攻击
```

<div align="center">

### ⚡ 执行层攻击

</div>

```
☠️ 工具投毒攻击/            - 工具投毒攻击
👻 工具影子攻击/            - 工具影子攻击
💻 命令注入攻击/            - 命令注入攻击
📡 远程监听攻击/            - 远程监听攻击
🌐 网页投毒攻击/            - 网页投毒攻击
🏃 沙箱逃逸攻击/           - 沙箱逃逸攻击
🚪 后门攻击/               - 后门攻击
```

<div align="center">

### 📜 协议层攻击

</div>

```
💰 Rug Pulls Attacks/      - Rug Pulls攻击
🚫 未授权调用攻击/          - 未授权调用攻击
```

---

## 📊 统计数据

<div align="center">

| 数据集        | 分类数   | 状态    |
| ---------- | ----- | ----- |
| **MCP服务器** | 34个分类 | 🟢 活跃 |
| **MCP攻击**  | 17个分类 | 🟢 活跃 |

</div>

---

**用 ❤️ 为MCP社区打造**

</div>
