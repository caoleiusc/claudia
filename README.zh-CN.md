<div align="center">
  <img src="https://github.com/user-attachments/assets/92fd93ed-e71b-4b94-b270-50684323dd00" alt="Claudia Logo" width="120" height="120">

  <a href="https://claudiacode.com"><h1>Claudia</h1></a>
  
  <p>
    <strong>一个为 Claude Code 设计的强大图形界面应用和工具包</strong>
  </p>
  <p>
    <strong>创建自定义智能体、管理交互式 Claude Code 会话、运行安全的后台智能体等等。</strong>
  </p>
  
  <p>
    <a href="#-功能特性"><img src="https://img.shields.io/badge/功能-✨-blue?style=for-the-badge" alt="功能"></a>
    <a href="#-安装"><img src="https://img.shields.io/badge/安装-🚀-green?style=for-the-badge" alt="安装"></a>
    <a href="#-使用方法"><img src="https://img.shields.io/badge/使用-📖-purple?style=for-the-badge" alt="使用"></a>
    <a href="#-开发"><img src="https://img.shields.io/badge/开发-🛠️-orange?style=for-the-badge" alt="开发"></a>
  </p>
</div>

![457013521-6133a738-d0cb-4d3e-8746-c6768c82672c](https://github.com/user-attachments/assets/a028de9e-d881-44d8-bae5-7326ab3558b9)

https://github.com/user-attachments/assets/bf0bdf9d-ba91-45af-9ac4-7274f57075cf

> [!TIP]
> **⭐ 给这个仓库点亮星星并关注 [@getAsterisk](https://x.com/getAsterisk) 的 X (推特) 账号，以获取 `asteria-swe-v0` 的早期访问权限。**

## 🌟 概述

**Claudia** 是一款功能强大的桌面应用程序，它将改变您与 Claude Code 的交互方式。基于 Tauri 2 构建，它提供了一个美观的图形用户界面，用于管理您的 Claude Code 会话、创建自定义智能体、追踪使用情况等等。

您可以将 Claudia 视为您的 Claude Code 指挥中心——它填补了命令行工具与可视化体验之间的鸿沟，使 AI 辅助开发更加直观和高效。

## 📋 目录

- [🌟 概述](#-概述)
- [✨ 功能特性](#-功能特性)
  - [🗂️ 项目与会话管理](#️-项目与会话管理)
  - [🤖 CC 智能体](#-cc-智能体)
  - [📊 使用分析仪表盘](#-使用分析仪表盘)
  - [🔌 MCP 服务器管理](#-mcp-服务器管理)
  - [⏰ 时间线与检查点](#-时间线与检查点)
  - [📝 CLAUDE.md 管理](#-claudemd-管理)
- [📖 使用方法](#-使用方法)
  - [快速入门](#快速入门)
  - [管理项目](#管理项目)
  - [创建智能体](#创建智能体)
  - [追踪使用情况](#追踪使用情况)
  - [使用 MCP 服务器](#使用-mcp-服务器)
- [🚀 安装](#-安装)
- [🔨 从源码构建](#-从源码构建)
- [🛠️ 开发](#️-开发)
- [🔒 安全性](#-安全性)
- [🤝 贡献](#-贡献)
- [📄 许可证](#-许可证)
- [🙏 致谢](#-致谢)

## ✨ 功能特性

### 🗂️ **项目与会话管理**
- **可视化项目浏览器**: 浏览位于 `~/.claude/projects/` 下的所有 Claude Code 项目。
- **会话历史**: 查看并恢复过去的编码会话，包含完整的上下文。
- **智能搜索**: 使用内置搜索快速查找项目和会话。
- **会话洞察**: 一目了然地查看首条消息、时间戳和会话元数据。

### 🤖 **CC 智能体**
- **自定义 AI 智能体**: 创建具有自定义系统提示和行为的专用智能体。
- **智能体库**: 为不同任务构建一个专门的智能体集合。
- **后台执行**: 在独立的进程中运行智能体，以进行非阻塞操作。
- **执行历史**: 追踪所有智能体运行的详细日志和性能指标。

### 📊 **使用分析仪表盘**
- **成本追踪**: 实时监控您的 Claude API 使用情况和成本。
- **令牌分析**: 按模型、项目和时间段提供详细的分类数据。
- **可视化图表**: 展示使用趋势和模式的精美图表。
- **数据导出**: 导出使用数据，用于记账和分析。

### 🔌 **MCP 服务器管理**
- **服务器注册表**: 从一个中央用户界面管理模型上下文协议（MCP）服务器。
- **简易配置**: 通过用户界面添加服务器或从现有配置导入。
- **连接测试**: 在使用前验证服务器的连通性。
- **Claude 桌面端导入**: 从 Claude 桌面端导入服务器配置。

### ⏰ **时间线与检查点**
- **会话版本控制**: 在编码会话的任何时刻创建检查点。
- **可视化时间线**: 通过一个可分支的时间线浏览您的会话历史。
- **即时恢复**: 一键跳回任何检查点。
- **会话分支**: 从现有检查点创建新的分支。
- **差异查看器**: 精确查看检查点之间的变更内容。

### 📝 **CLAUDE.md 管理**
- **内置编辑器**: 直接在应用内编辑 CLAUDE.md 文件。
- **实时预览**: 实时查看您的 Markdown 渲染效果。
- **项目扫描器**: 查找您项目中的所有 CLAUDE.md 文件。
- **语法高亮**: 全面的 Markdown 支持及语法高亮。

## 📖 使用方法

### 快速入门

1. **启动 Claudia**: 安装后打开应用程序。
2. **欢迎屏幕**: 在 CC 智能体和 CC 项目之间进行选择。
3. **首次设置**: Claudia 会自动检测您的 `~/.claude` 目录。

### 管理项目

```
CC 项目 → 选择项目 → 查看会话 → 恢复或开始新会话
```

- 点击任何项目以查看其会话。
- 每个会话都会显示首条消息和时间戳。
- 直接恢复会话或开始新会话。

### 创建智能体

```
CC 智能体 → 创建智能体 → 配置 → 执行
```

1. **设计您的智能体**: 设置名称、图标和系统提示。
2. **配置模型**: 在可用的 Claude 模型之间选择。
3. **设置权限**: 配置文件读取/写入和网络访问权限。
4. **执行任务**: 在任何项目上运行您的智能体。

### 追踪使用情况

```
菜单 → 使用分析仪表盘 → 查看分析数据
```

- 按模型、项目和日期监控成本。
- 导出数据用于报告。
- 设置使用警报（即将推出）。

### 使用 MCP 服务器

```
菜单 → MCP 管理器 → 添加服务器 → 配置
```

- 手动或通过 JSON 添加服务器。
- 从 Claude 桌面端配置导入。
- 使用前测试连接。

## 🚀 安装

### 前提条件

- **Claude Code CLI**: 从 [Claude 官方网站](https://claude.ai/code) 安装。

### 发行版可执行文件即将发布

## 🔨 从源码构建

### 前提条件

在从源码构建 Claudia 之前，请确保您已安装以下软件：

#### 系统要求

- **操作系统**: Windows 10/11, macOS 11+, 或 Linux (Ubuntu 20.04+)。
- **内存**: 最低 4GB (推荐 8GB)。
- **存储空间**: 至少 1GB 可用空间。

####所需工具

1. **Rust** (1.70.0 或更高版本)
   ```bash
   # 通过 rustup 安装
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   ```

2. **Bun** (最新版本)
   ```bash
   # 安装 bun
   curl -fsSL https://bun.sh/install | bash
   ```

3. **Git**
   ```bash
   # 通常已预装，但如果没有：
   # Ubuntu/Debian: sudo apt install git
   # macOS: brew install git
   # Windows: 从 https://git-scm.com 下载
   ```

4. **Claude Code CLI**
   - 从 [Claude 官方网站](https://claude.ai/code) 下载并安装。
   - 确保 `claude` 命令在您的系统路径 (PATH) 中可用。

#### 特定平台的依赖

**Linux (Ubuntu/Debian)**
```bash
# 安装系统依赖
sudo apt update
sudo apt install -y \
  libwebkit2gtk-4.1-dev \
  libgtk-3-dev \
  libayatana-appindicator3-dev \
  librsvg2-dev \
  patchelf \
  build-essential \
  curl \
  wget \
  file \
  libssl-dev \
  libxdo-dev \
  libsoup-3.0-dev \
  libjavascriptcoregtk-4.1-dev
```

**macOS**
```bash
# 安装 Xcode 命令行工具
xcode-select --install

# 通过 Homebrew 安装额外依赖 (可选)
brew install pkg-config
```

**Windows**
- 安装 [Microsoft C++ Build Tools](https://visualstudio.microsoft.com/visual-cpp-build-tools/)。
- 安装 [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) (通常在 Windows 11 上已预装)。

### 构建步骤

1. **克隆仓库**
   ```bash
   git clone https://github.com/getAsterisk/claudia.git
   cd claudia
   ```

2. **安装前端依赖**
   ```bash
   bun install
   ```

3. **构建应用程序**
   
   **用于开发 (带热重载)**
   ```bash
   bun run tauri dev
   ```
   
   **用于生产构建**
   ```bash
   bun run tauri build
   ```

## 🛠️ 开发

要了解更多关于本地开发、运行测试和贡献代码的信息，请查看我们的 [贡献指南](CONTRIBUTING.md)。

## 🔒 安全性

Claudia 在设计时就考虑到了安全性。有关详细信息，请查看我们的 [安全策略](https://github.com/getAsterisk/claudia/security/policy)。

## 🤝 贡献

我们欢迎各种形式的贡献！无论是报告错误、提交功能请求还是拉取请求，我们都非常感谢。

请在 [此处](CONTRIBUTING.md) 查看我们的贡献指南。

## 📄 许可证

本项目根据 [AGPL-3.0 许可证](LICENSE) 授权。

## 🙏 致谢

Claudia 离不开以下开源项目的支持：
- [Tauri](https://tauri.app/)
- [React](https://reactjs.org/)
- [Claude Code](https://claude.ai/code)
- 所有为我们使用的库做出贡献的人们！ 