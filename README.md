<div align="center">

# 🌐 MCP Server & MCP Attack Dataset

**Model Context Protocol Server Collection & Security Attack Samples**

[![English](https://img.shields.io/badge/English-Click-yellow)](README.md)
[![简体中文](https://img.shields.io/badge/简体中文-点击查看-orange)](README-zh.md)
[![繁體中文](https://img.shields.io/badge/繁體中文-點擊查看-orange)](README-zh_TW.md)
[![日本語](https://img.shields.io/badge/日本語-クリック-blue)](README-ja.md)
[![한국어](https://img.shields.io/badge/한국어-클릭-yellow)](README-ko.md)

</div>

---

## 📑 Table of Contents

- [What is MCP?](#what-is-mcp)
- [Supported Clients](#supported-clients)
- [Server Categories](#server-categories)
- [Attack Categories](#attack-categories)

---

## 🤖 What is MCP?

**MCP (Model Context Protocol)** is an open protocol designed to enable seamless integration between AI models and external data sources, tools, and services. Developed by Anthropic, MCP standardizes how AI assistants can access and interact with various capabilities, making it easier to extend AI functionality beyond text generation.

Key features:
- 🔗 **Standardized Integration**: Universal interface for connecting AI to external tools
- 🛠️ **Tool Discovery**: Dynamic discovery and use of available capabilities
- 🔒 **Security-First**: Built with security considerations for safe tool execution
- 🌐 **Cross-Platform**: Works across different AI clients and frameworks

---

## 💻 Supported Clients

<div align="center">

| Client | Support | Description |
|--------|---------|-------------|
| ![Claude](https://img.shields.io/badge/Claude-Anthropic-CC785C?style=flat-square&logo=anthropic) | ✅ Full | Anthropic's AI assistant |
| ![Cursor](https://img.shields.io/badge/Cursor-Editor-000000?style=flat-square) | ✅ Full | AI-powered code editor |
| ![Windsurf](https://img.shields.io/badge/Windsurf-IDE-6366F1?style=flat-square) | ✅ Full | AI-native IDE |
| ![Cline](https://img.shields.io/badge/Cline-VSCode-007ACC?style=flat-square&logo=visualstudiocode) | ✅ Full | VS Code AI assistant |
| ![LangChain](https://img.shields.io/badge/LangChain-Framework-1C3C3C?style=flat-square) | ✅ Full | LLM application framework |

</div>

---

## 📁 Server Categories

<div align="center">

### 🔗 34 Categories

</div>

### 🧠 AI & LLM Integration

| Icon | Category | Description |
|:---:|:---|:---|
| 🤖 | `ai/` | General AI tools and utilities |
| 🔗 | `langchain/` | LangChain framework integrations |
| 🦙 | `llama/` | Llama model integrations |
| 🧩 | `llm-integration/` | General LLM integration tools |
| 🧮 | `mathgpt/` | Mathematical GPT models |
| 🔢 | `math-assistant/` | Mathematical assistant tools |

### 🛠️ Development Tools

| Icon | Category | Description |
|:---:|:---|:---|
| 💻 | `developer-tools/` | Developer utilities and SDKs |
| 📘 | `bucket_typescript/` | TypeScript-related tools |
| 🕷️ | `firecrawl/` | Web crawling and scraping tools |
| 🌐 | `browser-automation/` | Browser automation solutions |

### 🏢 Productivity & Workplace

| Icon | Category | Description |
|:---:|:---|:---|
| 💼 | `Workplace_&_Productivity/` | Workplace productivity tools |
| 📈 | `productivity-tools/` | General productivity utilities |
| 📅 | `calendar-management/` | Calendar and scheduling tools |
| ⏰ | `time/` | Time management tools |
| 🌍 | `timezone/` | Timezone conversion utilities |

### 📊 Data & Analytics

| Icon | Category | Description |
|:---:|:---|:---|
| 📈 | `data-analysis/` | Data analysis and visualization |
| 🧠 | `knowledge-and-memory/` | Knowledge base and memory systems |
| 📄 | `content-extraction/` | Content extraction tools |
| 🔍 | `research/` | Research and academic tools |

### ☁️ Cloud & Infrastructure

| Icon | Category | Description |
|:---:|:---|:---|
| ☁️ | `Cloud_Platforms/` | Cloud service integrations |
| 🗄️ | `redis/` | Redis database tools |
| 🔒 | `security/` | Security and authentication tools |
| 🔎 | `search-api/` | Search API integrations |

### 💬 Communication & Media

| Icon | Category | Description |
|:---:|:---|:---|
| 💬 | `Communication/` | Communication and messaging tools |
| 🔊 | `text-to-speech/` | TTS and voice synthesis tools |

### 🏭 Industry Applications

| Icon | Category | Description |
|:---:|:---|:---|
| 💰 | `finance/` | Financial and banking tools |
| 📢 | `Marketing/` | Marketing and analytics tools |
| 🎮 | `Gaming/` | Game development and gaming tools |
| ⚽ | `Sports/` | Sports and fitness tools |
| 🏠 | `Real_Estate/` | Real estate and property tools |
| 🚚 | `Delivery/` | Delivery and logistics tools |
| 🎨 | `Art_&_Culture/` | Art, culture, and creative tools |

### 🎨 Other Tools

| Icon | Category | Description |
|:---:|:---|:---|
| 🔧 | `Other_Tools_and_Integrations/` | Miscellaneous tools |
| 🏄 | `windsurf/` | Windsurf IDE specific tools |

---

## ⚠️ Attack Categories

<div align="center">

### 📡 Transmission Layer Attacks

</div>

```
🔑 凭证泄露/               - Credential Leakage
```

<div align="center">

### 🧠 Decision Layer Attacks

</div>

```
🎯 工具偏好操纵攻击/         - Tool Preference Manipulation Attack
🎭 傀儡攻击/               - Puppet Attack
⚡ 工具抢占攻击/            - Tool Squatting Attack
🔨 工具链开发攻击/          - Tool Chain Exploitation Attack
💬 提示词注入攻击/          - Prompt Injection Attack
```

<div align="center">

### ⚡ Execution Layer Attacks

</div>

```
☠️ 工具投毒攻击/            - Tool Poisoning Attack
👻 工具影子攻击/            - Tool Shadowing Attack
💻 命令注入攻击/            - Command Injection Attack
📡 远程监听攻击/            - Remote Listener Attack
🌐 网页投毒攻击/            - Webpage Poisoning Attack
🏃 沙箱逃逸攻击/           - Sandbox Escape Attack
🚪 后门攻击/               - Backdoor Attack
```

<div align="center">

### 📜 Protocol Layer Attacks

</div>

```
💰 Rug Pulls Attacks/      - Rug Pulls Attacks
🚫 未授权调用攻击/          - Unauthorized Invocation Attack
```

---

## 📊 Statistics

<div align="center">

| Dataset | Categories | Status |
|---------|------------|--------|
| **MCP Servers** | 34 Categories | 🟢 Active |
| **MCP Attack** | 17 Categories | 🟢 Active |

</div>

---

**Made with ❤️ for the MCP Community**

</div>
