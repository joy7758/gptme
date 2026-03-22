<!-- language-switch:start -->
[English](./README.md) | [中文](./README.zh-CN.md)
<!-- language-switch:end -->

<p align="center">
<img src="https://gptme.org/media/logo.png" width=150 />
</p>

<h1 align="center">gptme</h1>

<p align="center">
<i>/ʤiː piː tiː miː/</i>
</p>

<!-- Links -->
<p align="center">
<a href="https://gptme.org/docs/getting-started.html">Getting Started</a>
  •
<a href="https://gptme.org/">Website</a>
  •
<a href="https://gptme.org/docs/">Documentation</a>
</p>

<!-- Badges -->
<p align="center">
<a href="https://github.com/gptme/gptme/actions/workflows/build.yml">
<img src="https://github.com/gptme/gptme/actions/workflows/build.yml/badge.svg" alt="Build Status" />
</a>
<a href="https://github.com/gptme/gptme/actions/workflows/docs.yml">
<img src="https://github.com/gptme/gptme/actions/workflows/docs.yml/badge.svg" alt="Docs Build Status" />
</a>
<a href="https://codecov.io/gh/gptme/gptme">
<img src="https://codecov.io/gh/gptme/gptme/graph/badge.svg?token=DYAYJ8EF41" alt="Codecov" />
</a>
<br>
<a href="https://pypi.org/project/gptme/">
<img src="https://img.shields.io/pypi/v/gptme" alt="PyPI version" />
</a>
<a href="https://pepy.tech/project/gptme">
<img src="https://img.shields.io/pepy/dt/gptme" alt="PyPI - Downloads all-time" />
</a>
<a href="https://pypistats.org/packages/gptme">
<img src="https://img.shields.io/pypi/dd/gptme?color=success" alt="PyPI - Downloads per day" />
</a>
<br>
<a href="https://discord.gg/NMaCmmkxWv">
<img src="https://img.shields.io/discord/1271539422017618012?logo=discord&style=social" alt="Discord" />
</a>
<a href="https://x.com/gptmeorg">
<img src="https://img.shields.io/twitter/follow/gptmeorg?style=social" alt="X.com" />
</a>
<br>
<a href="https://gptme.org/docs/projects.html">
<img src="https://img.shields.io/badge/powered%20by-gptme%20%F0%9F%A4%96-5151f5?style=flat" alt="Powered by gptme" />
</a>
</p>

<p align="center">
📜 终端中的个人AI 智能体，带有工具，可以：<br/>
使用终端、运行代码、编辑文件、浏览网页、使用视觉等等；<br/>
一个很棒的编码代理，但它是通用的，可以协助各种知识工作。
</p>

<p align="center">
一个不受约束的本地免费开源<a href="https://gptme.org/docs/alternatives.html">alternative</a> to Claude Code, Codex, Cursor Agents, etc.<br/>
创建的首批智能体 CLI 之一（2023 年春季）仍在积极开发中。
</p>

## 📚 目录

- 📢 [新闻](#news)
- 🎥 [演示](#-demos)
- 🌟 [特点](#-features)
- 🚀 [入门](#-getting-started)
- 🛠 [使用方法](#-usage)
- 📊 [统计](#-stats)
- 🔗 [链接](#-links)

## 📢 新闻

- **即将推出** - [gptme.ai](https://gptme.ai) 服务，用于在云中运行代理； [gptme 桌面](https://github.com/gptme/gptme-tauri) 应用程序，方便本地使用。
- **2026-01** - [gptme-agent-template](https://github.com/gptme/gptme-agent-template) v0.4：[Bob](https://github.com/TimeToBuildBob) 达到 1000 多个自主会话、自主运行循环、增强的上下文生成
- **2025-12** - [v0.31.0](https://github.com/gptme/gptme/releases/tag/v0.31.0)：后台作业、表单工具、成本跟踪、内容寻址存储
- **2025-11** - [v0.30.0](https://github.com/gptme/gptme/releases/tag/v0.30.0)：插件系统、上下文压缩、子代理规划器模式
- **2025-10** - [v0.29.0](https://github.com/gptme/gptme/releases/tag/v0.29.0)：用于上下文指导、MCP 发现和动态加载、令牌感知的课程系统； [Bob](https://github.com/TimeToBuildBob) 开始通过 GitHub 监控进行自主运行
- **2025-08** - [v0.28.0](https://github.com/gptme/gptme/releases/tag/v0.28.0)：MCP 支持、用于快速编辑的变形工具、自动提交、重新设计的服务器 API
- **2025-03** - [v0.27.0](https://github.com/gptme/gptme/releases/tag/v0.27.0)：预提交集成、macOS 计算机使用、Claude 3.7 Sonnet、DeepSeek R1、带有 Kokoro 的本地 TTS
- **2025-01** - [gptme-contrib](https://github.com/gptme/gptme-contrib) 创建：社区插件，包括 Twitter/X、Discord 机器人、电子邮件工具、联盟（多智能体）
- **2024-12** - [gptme-agent-template](https://github.com/gptme/gptme-agent-template) v0.3：持久代理模板
- **2024-11** - 生态系统扩展：创建 [gptme-webui](https://github.com/gptme/gptme-webui)、[gptme-rag](https://github.com/gptme/gptme-rag)、[gptme.vim](https://github.com/gptme/gptme.vim)、[Bob](https://github.com/TimeToBuildBob)（第一个自治智能体）
- **2024年10月** - [第一条病毒推文](https://x.com/rohanpaul_ai/status/1841999030999470326)引起广泛关注
- **2024-08** - [显示 HN](https://news.ycombinator.com/item?id=41204256)、Anthropic Claude 支持、tmux 工具
- **2023-09** - [首次公开发布](https://news.ycombinator.com/item?id=37394845) 在 HN、[Reddit](https://www.reddit.com/r/LocalLLaMA/comments/16atlia/)、[Twitter](https://x.com/ErikBjare/status/1699097896451289115)
- **2023-03** - [初始提交](https://github.com/gptme/gptme/commit/d00e9aae68cbd6b89bbc474ed7721d08796dc) - 第一个智能体 CLI 之一


<!-- source of truth: docs/timeline.rst and docs/changelog.rst -->
有关更多历史记录，请参阅[时间线](https://gptme.org/docs/timeline.html) 和[变更日志](https://gptme.org/docs/changelog.html)。

## 🎥 演示

> [！笔记]
> 这些演示来自 2023 年。有关最新示例，请参阅[文档][文档示例]。

<table>
<tr>
<th>斐波那契</th>
<th>蛇与诅咒</th>
</tr>
<tr>
<td width="50%">

[![使用 asciinema 进行演示截屏](https://github.com/ErikBjare/gptme/assets/1405370/5dda4240-bb7d-4cfa-8dd1-cd1218ccf571)](https://asciinema.org/a/606375)

<details>
<summary>步骤</summary>
<ol>
<li> 创建一个新目录“gptme-test-fib”并 git init
<li> 将fib函数写入fib.py，提交
<li> 创建公共仓库并推送到 GitHub
</ol>
</details>

</td>

<td width="50%">

[![621992-resvg](https://github.com/ErikBjare/gptme/assets/1405370/72ac819c-b633-495e-b20e-2e40753ec376)](https://asciinema.org/a/621992)

<details>
<summary>步骤</summary>
<ol>
<li> 创建一个蛇游戏与诅咒到snake.py
<li> 运行失败，请gptme修复一个bug
<li> 游戏运行
<li> 要求gptme添加颜色
<li> 小斗争
<li> 青蛇和红苹果派完成游戏！
</ol>
</details>
</td>
</tr>

<tr>
<th>Mandelbrot 与诅咒</th>
<th>回答来自 URL 的问题</th>
</tr>
<tr>
<td width="50%">

[![曼德尔布罗诅咒](https://github.com/ErikBjare/gptme/assets/1405370/570860ac-80bd-4b21-b8d1-da187d7c1a95)](https://asciinema.org/a/621991)

<details>
<summary>步骤</summary>
<ol>
<li> 将带有诅咒的 mandelbrot 渲染到 mandelbrot_curses.py
<li> 程序运行
<li> 添加颜色
</ol>
</details>

</td>

<td width="25%">

[![superuserlabs-ceo](https://github.com/ErikBjare/gptme/assets/1405370/bae45488-f4ed-409c-a656-0c5218877de2)](https://asciinema.org/a/621997)

<details>
<summary>步骤</summary>
<ol>
<li> 询问 Superuser Labs 的 CEO 是谁，传递网站 URL
<li> gptme浏览网站，并回答正确
</ol>
</details>
</td>
</tr>

<tr>
<th>终端UI</th>
<th>Web UI</th>
</tr>
<tr>
<td width="50%">

<!--[![terminal-ui](https://github.com/ErikBjare/gptme/assets/1405370/terminal-ui-demo)](https://asciinema.org/a/terminal-demo)-->

<details>
<summary>特点</summary>
<ul>
<li> 强大的终端接口
<li> 便捷的 CLI 命令
<li> 差异和语法突出显示
<li> 制表符补全
<li> 命令历史
</ul>
</details>

</td>
<td width="50%">

<!--[![web-ui](https://github.com/ErikBjare/gptme/assets/1405370/web-ui-demo)](https://chat.gptme.org)-->

<details>
<summary>特点</summary>
<ul>
<li> 从浏览器与 gptme 聊天
<li> 访问所有工具和功能
<li> 现代、响应式界面
<li> 自托管
<li> 可在 <a href="https://chat.gptme.org">chat.gptme.org</a>
</ul>
</details>

</td>
</tr>
</table>

您可以在[文档][文档]中找到更多[演示][文档演示]和[示例][文档示例]。

## 🌟特点

- 💻 代码执行
  - 使用 [shell][docs-tools-shell] 和 [python][docs-tools-python] 工具在本地环境中执行代码。
- 🧩 读取、写入和更改文件
  - 使用 [patch][docs-tools-patch] 工具进行增量更改。
- 🌐 搜索和浏览网页。
  - 可以通过 Playwright 和 [browser][docs-tools-browser] 工具使用浏览器。
- 👀 愿景
  - 可以查看提示中引用的图像、桌面屏幕截图和网页。
- 🔄 自我修正
  - 输出被反馈给助手，使其能够做出响应和自我纠正。
- 📚 [课程系统][文档课程]
  - 相关时自动包含上下文指导和最佳实践
  - 基于关键词和工具的匹配
  - 适应交互模式与自主模式
- 🤖 支持多个 LLM [提供者][文档提供者]
  - 使用 OpenAI、Anthropic、OpenRouter，或使用 `llama.cpp` 进行本地服务
- 🌐 Web UI 和 REST API
  - 现代 Web 界面位于 [chat.gptme.org](https://chat.gptme.org) ([gptme-webui])
  - Python 包中包含简单的内置 Web UI
  - [服务器][文档服务器] 使用 REST API
  - PyInstaller 提供独立的可执行版本
- 💻 [计算机使用][docs-tools-computer] 工具，由 [Anthropic][anthropic-computer-use] 宣传（参见 [#216](https://github.com/gptme/gptme/issues/216)）
  - 为助手提供对完整桌面的访问权限，使其能够与 GUI 应用程序进行交互。
- 🤖 长时间运行的代理和高级代理架构（请参阅 [#143](https://github.com/gptme/gptme/issues/143) 和 [#259](https://github.com/gptme/gptme/issues/259)）
  - 使用 [gptme-agent-template][agent-template] 创建您自己的持久代理，例如 [Bob][bob]。
- ✨ 许多小功能可确保出色的体验
  - 🚰 通过 `stdin` 或作为参数在上下文中进行管道传输。
    - 传递文件名作为参数将读取该文件并将其包含为上下文。
  - → 智能完成和突出显示：
    - 命令和路径的选项卡补全和突出显示
  - 📝 对话自动命名
  - ✅ 检测并集成[预提交](https://github.com/pre-commit/pre-commit)
  - 🗣️ [文本转语音][docs-tools-tts] 支持，使用 Kokoro 本地生成
  - 🔊 工具声音：不同工具操作的悦耳通知声音
    - 使用 `GPTME_TOOL_SOUNDS=true` 启用
    - shell命令、文件操作、屏幕截图等的不同声音
  - 🎯 高级使用的功能标志，请参阅[配置文档][docs-config]

### 🛠 使用案例

- 🖥 **开发：** 在人工智能的帮助下更快地编写和运行代码。
- 🎯 **Shell Expert：** 使用自然语言获取正确的命令（不再需要记住标志！）。
- 📊 **数据分析：** 直接在终端中处理和分析数据。
- 🎓 **互动学习：** 亲自尝试新技术或代码库。
- 🤖 **代理和工具：** 在本地环境中试验代理和工具。

### 🛠 开发者福利

- ⭐ 创建的首批智能体 CLI 之一（2023 年春季）仍在积极开发中。
- 🧰 易于扩展
  - 大多数功能都可以使用 [tools][docs-tools]、[hooks][docs-hooks] 和 [commands][docs-commands] 来实现，从而可以轻松添加新功能。
  - 试图保持[微小][文档-arewetiny]。
  - [插件][文档插件] 允许轻松打包扩展。
- 🧪 广泛测试，高覆盖率。
- 🧹 清理代码库，使用 `mypy`、`ruff` 和 `pyupgrade` 进行检查和格式化。
- 🤖 [GitHub Bot][docs-bot] 请求评论更改！ （参见[#16](https://github.com/gptme/gptme/issues/16)）
  - 在此仓库中运行！ （例如参见[#18](https://github.com/gptme/gptme/issues/18)）
  - 完全在 GitHub Actions 中运行。
- 📊 [评估套件][docs-evals] 用于测试不同模型的能力
- 📝 [gptme.vim][gptme.vim] 轻松与 vim 集成

### 🚧 进行中

- 🌳 基于树的对话结构（参见[#17](https://github.com/gptme/gptme/issues/17)）
- 📜 RAG 自动包含本地文件中的上下文（请参阅 [#59](https://github.com/gptme/gptme/issues/59)）
- 🏆 用于测试前沿能力的高级评估

## 🚀 开始使用

使用 pipx 安装：

```sh
# requires Python 3.10+
pipx install gptme
```

现在，开始运行：

```sh
gptme
```

以下是一些示例：

```sh
gptme 'write an impressive and colorful particle effect using three.js to particles.html'
gptme 'render mandelbrot set to mandelbrot.png'
gptme 'suggest improvements to my vimrc'
gptme 'convert to h265 and adjust the volume' video.mp4
git diff | gptme 'complete the TODOs in this diff'
make test | gptme 'fix the failing tests'
```

有关更多信息，请参阅[入门][docs-getting-started]指南和[文档][docs]中的[示例][docs-examples]。

## 🛠 用法

```sh
$ gptme --help
Usage: gptme [OPTIONS] [PROMPTS]...

  gptme is a chat-CLI for LLMs, empowering them with tools to run shell
  commands, execute code, read and manipulate files, and more.

  If PROMPTS are provided, a new conversation will be started with it. PROMPTS
  can be chained with the '-' separator.

  The interface provides user commands that can be used to interact with the
  system.

  Available commands:
    /undo         Undo the last action
    /log          Show the conversation log
    /edit         Edit the conversation in your editor
    /rename       Rename the conversation
    /fork         Create a copy of the conversation
    /summarize    Summarize the conversation
    /replay       Replay tool operations
    /export       Export conversation as HTML
    /model        Show or switch the current model
    /models       List available models
    /tokens       Show token usage and costs
    /context      Show context token breakdown
    /tools        Show available tools
    /commit       Ask assistant to git commit
    /compact      Compact the conversation
    /impersonate  Impersonate the assistant
    /restart      Restart gptme process
    /setup        Setup gptme
    /help         Show this help message
    /exit         Exit the program

  See docs for all commands: https://gptme.org/docs/commands.html

  Keyboard shortcuts:
    Ctrl+X Ctrl+E  Edit prompt in your editor
    Ctrl+J         Insert a new line without executing the prompt

Options:
  --name TEXT            Name of conversation. Defaults to generating a random
                         name.
  -m, --model TEXT       Model to use, e.g. openai/gpt-5, anthropic/claude-
                         sonnet-4-20250514. If only provider given then a
                         default is used.
  -w, --workspace TEXT   Path to workspace directory. Pass '@log' to create a
                         workspace in the log directory.
  --agent-path TEXT      Path to agent workspace directory.
  -r, --resume           Load most recent conversation.
  -y, --no-confirm       Skip all confirmation prompts.
  -n, --non-interactive  Non-interactive mode. Implies --no-confirm.
  --system TEXT          System prompt. Options: 'full', 'short', or something
                         custom.
  -t, --tools TEXT       Tools to allow as comma-separated list. Available:
                         append, browser, chats, choice, computer, gh,
                         ipython, morph, patch, rag, read, save, screenshot,
                         shell, subagent, tmux, tts, vision, youtube.
  --tool-format TEXT     Tool format to use. Options: markdown, xml, tool
  --no-stream            Don't stream responses
  --show-hidden          Show hidden system messages.
  -v, --verbose          Show verbose output.
  --version              Show version and configuration information
  --help                 Show this message and exit.
```

## 📊 统计数据

### ⭐ 随着时间的推移观星者

[![随时间变化的观星者](https://starchart.cc/gptme/gptme.svg)](https://starchart.cc/gptme/gptme)

### 📈 下载统计数据

- [佩皮][佩皮]
- [PyPiStats][pypistats]

[佩皮]：https://pepy.tech/project/gptme
[pypistats]：https://pypistats.org/packages/gptme

## 🔗 链接

- [网站][网站]
- [文档][文档]
- [GitHub][github]
- [不和谐][不和谐]

<!-- links -->

[网址]：https://gptme.org/
[不和谐]：https://discord.gg/NMaCmmkxWv
[github]：https://github.com/gptme/gptme
[gptme.vim]: https://github.com/gptme/gptme.vim
[gptme-webui]: https://github.com/gptme/gptme-webui
[代理模板]：https://github.com/gptme/gptme-agent-template
[鲍勃]：https://github.com/TimeToBuildBob
[文档]：https://gptme.org/docs/
[文档入门]：https://gptme.org/docs/getting-started.html
[文档示例]：https://gptme.org/docs/examples.html
[文档演示]：https://gptme.org/docs/demos.html
[文档提供者]：https://gptme.org/docs/providers.html
[文档工具]：https://gptme.org/docs/tools.html
[文档工具-python]：https://gptme.org/docs/tools.html#python
[文档工具外壳]：https://gptme.org/docs/tools.html#shell
[文档工具补丁]：https://gptme.org/docs/tools.html#patch
[文档工具浏览器]：https://gptme.org/docs/tools.html#browser
[文档工具计算机]：https://gptme.org/docs/tools.html#computer
[文档工具-tts]：https://gptme.org/docs/tools.html#tts
[文档课程]：https://gptme.org/docs/lessons.html
[文档机器人]：https://gptme.org/docs/bot.html
[文档服务器]：https://gptme.org/docs/server.html
[文档评估]：https://gptme.org/docs/evals.html
[文档配置]：https://gptme.org/docs/config.html
[文档-arewetiny]：https://gptme.org/docs/arewetiny.html
[文档插件]：https://gptme.org/docs/plugins.html
[文档挂钩]：https://gptme.org/docs/hooks.html
[文档命令]：https://gptme.org/docs/commands.html
[人择计算机使用]：https://www.anthropic.com/news/3-5-models-and-computer-use
