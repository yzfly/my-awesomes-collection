# 个人资源收藏库

个人收藏的一些指南，资源列表，有趣好玩的工具和网站。

## 目录

- [玩转 GitHub](#玩转-github)
  - [Github 加速 ✈️](#github-加速-️)
- [开发](#开发)
- [设计](#设计)
- [AI 相关](#ai-相关)
  - [AI 资源合集 Awesome List](#ai-资源合集-awesome-list)
  - [提示工程 Prompt Engineering](#提示工程-prompt-engineering)
  - [AI 开源应用](#ai-开源应用)
  - [作者的 Awesome 系列](#作者的-awesome-系列)
  - [更多 AI 资源](#更多-ai-资源)
- [作者](#作者)

## 玩转 GitHub

* [GitHub](https://github.com/) — 不限数量的公开代码库和私有代码库(协作者数量不限)。此外还提供了很多其他免费服务。
* [静态网站托管](https://pages.github.com)- 免费托管静态个人博客，网站。
* [云开发环境 Codespaces](https://github.com/codespaces) - 云开发环境，每个月提供 120-core 小时 and 15 GB 的免费额度。
* [CI/CD](https://github.com/features/actions)-公开代码库免费无限制, 私有库免费额度 2000 min/month)
* [智能编程助手 GitHub Copilot](https://github.com/features/copilot)—收费，学生认证免费
* [在线编辑 github.dev](https://github.dev)-将代码库 url 地址中的 github.com 修改为  github.dev 即可打开在线版 vscode 编辑代码，免费。
* [聊天 gitter.im](https://gitter.im/) — Github 在线聊天, 免费无限制创建公开和私密聊天室。  
* [代码分享 gist](https://gist.github.com/)- 免费分享代码（文本）片段
* [提问和贡献指南: issue and pr](https://github.com/datawhalechina/DOPMC/blob/main/GITHUB.md) - 如何提 issue 和 pull request 极简指南。

### Github 加速 ✈️

日常使用 GitHub 下载代码时如果遇到网速慢、无法连接的情况，可以使用下面的方法加速。

> 注意：GitHub 加速镜像站常因政策或运营原因变动，下面的镜像如失效，可访问 [ghproxy.link](https://ghproxy.link/) 查看最新可用域名，或参考方案三自建代理。

#### 方法一（推荐）：[ghfast.top](https://ghfast.top/)

常规的面向 GitHub 的 clone 命令可能如下：

```bash
git clone https://github.com/author/repo
```

使用 ghfast.top 代理加速（在原始地址前添加前缀即可）：

```bash
git clone https://ghfast.top/https://github.com/author/repo
```

同样支持 Release、Raw、Archive 等文件的加速下载，例如：

```bash
wget https://ghfast.top/https://github.com/author/repo/archive/refs/heads/main.zip
```

#### 方法二（推荐）：[gh-proxy.com](https://gh-proxy.com/)

用法与方法一相同，在原始 GitHub 地址前添加前缀 `https://gh-proxy.com/`：

```bash
git clone https://gh-proxy.com/https://github.com/author/repo
```

#### 方法三（进阶）：使用 Cloudflare Workers 自建代理

公共镜像站可能随时失效或限速，最稳妥的方式是自建一个属于自己的代理。推荐基于 Cloudflare Workers 部署 [hunshcn/gh-proxy](https://github.com/hunshcn/gh-proxy) 项目，免费、稳定、专属：

1. 注册 [Cloudflare](https://www.cloudflare.com/) 账号并进入 Workers 控制台；
2. 新建一个 Worker，将 [gh-proxy](https://github.com/hunshcn/gh-proxy) 提供的 `index.js` 代码粘贴进去并部署；
3. 部署后会得到一个形如 `https://你的域名.workers.dev/` 的地址，按方法一、二的方式作为前缀使用即可。

> 其他可选的高性能自建方案：[WJQSERVER-STUDIO/ghproxy](https://github.com/WJQSERVER-STUDIO/ghproxy)（基于 Go，支持 Docker 部署）。

## 开发

|名称|Star|简介|
|---|---|---|
|[:fire: 免费开发资源合集](https://github.com/ripienaar/free-for-dev)|![GitHub Repo stars](https://badgen.net/github/stars/ripienaar/free-for-dev) |各种免费优质的开发资源|
|[awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted)|![GitHub Repo stars](https://badgen.net/github/stars/awesome-selfhosted/awesome-selfhosted) |可自托管的免费软件网络服务和web应用程序资源合集|
|[project-based-learning](https://github.com/practical-tutorials/project-based-learning)|![GitHub Repo stars](https://badgen.net/github/stars/practical-tutorials/project-based-learning) |基于项目的学习资源合集|
|[敏感词词库](https://github.com/pennyliang/ciku)|![GitHub Repo stars](https://badgen.net/github/stars/pennyliang/ciku) |敏感词词库|

## 设计

|名称|简介|
|---|---|
|[:fire: Logo 设计](https://looka.com/)|免费 Logo 设计，Logo 设计简约漂亮|
|[:fire: 图片套壳美化](https://shots.so/)|免费图片套壳手机、悬浮背景，让图片更高大上|

## AI 相关

### AI 资源合集 Awesome List

|名称|Star|简介|
|---|---|---|
|[:fire: Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM)|![GitHub Repo stars](https://badgen.net/github/stars/Hannibal046/Awesome-LLM) |大语言模型 (LLM) 论文、框架、工具、课程的精选合集|
|[:fire: generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners)|![GitHub Repo stars](https://badgen.net/github/stars/microsoft/generative-ai-for-beginners) |微软出品的生成式 AI 入门课程，21 节课从零开始构建 AI 应用|
|[awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai)|![GitHub Repo stars](https://badgen.net/github/stars/steven2358/awesome-generative-ai) |现代生成式 AI 项目与服务的精选清单|
|[awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents)|![GitHub Repo stars](https://badgen.net/github/stars/e2b-dev/awesome-ai-agents) |AI 智能体 (Agents) 的精选合集，涵盖开源与闭源项目|
|[awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)|![GitHub Repo stars](https://badgen.net/github/stars/punkpeye/awesome-mcp-servers) |MCP (Model Context Protocol) 服务器精选合集|
|[Awesome-LLMOps](https://github.com/tensorchord/Awesome-LLMOps)|![GitHub Repo stars](https://badgen.net/github/stars/tensorchord/Awesome-LLMOps) |LLMOps 工具的精选合集，覆盖模型训练、部署、监控全流程|
|[Awesome-Chinese-LLM](https://github.com/AiHubCN/Awesome-Chinese-LLM)|![GitHub Repo stars](https://badgen.net/github/stars/AiHubCN/Awesome-Chinese-LLM) |中文大语言模型相关资源整理，开源模型、数据集、教程等|
|[Github ChatGPT Awesome 合集](docs/chatgpt.md)|—|精选的 ChatGPT 相关仓库与指南汇总（本仓库整理）|
|[awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin)|![GitHub Repo stars](https://badgen.net/github/stars/awesome-dsh-plugin/awesome-dsh-plugin) |DeepSeek Harness（dsh）插件精选列表|
|[awesome-remote-mcp-servers](https://github.com/punkpeye/awesome-remote-mcp-servers)|![GitHub Repo stars](https://badgen.net/github/stars/punkpeye/awesome-remote-mcp-servers) |可直接远程连接的 MCP Server 合集|
|[awesome-claude-video-skills](https://github.com/zhuyansen/awesome-claude-video-skills)|![GitHub Repo stars](https://badgen.net/github/stars/zhuyansen/awesome-claude-video-skills) |让 Claude Code、Codex 等编码 Agent 做视频的开源 Skill 与工具|
|[awesome-short-drama-skills](https://github.com/UnderleveledBuilder/awesome-short-drama-skills)|![GitHub Repo stars](https://badgen.net/github/stars/UnderleveledBuilder/awesome-short-drama-skills) |AI 短剧 / 漫剧 Skill 精选：剧本、改编、分镜与视频提示词|

### 提示工程 Prompt Engineering

|名称|Star|简介|
|---|---|---|
|[:fire: awesome-chatgpt-prompts](https://github.com/f/prompts.chat)|![GitHub Repo stars](https://badgen.net/github/stars/f/prompts.chat) |最知名的 ChatGPT 提示词合集（现已更名 prompts.chat）|
|[:fire: Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide)|![GitHub Repo stars](https://badgen.net/github/stars/dair-ai/Prompt-Engineering-Guide) |系统的提示工程指南，包含论文、技巧与实践|
|[awesome-seedance](https://github.com/LearnPrompt/awesome-seedance)|![GitHub Repo stars](https://badgen.net/github/stars/LearnPrompt/awesome-seedance) |Seedance 2.x 视频提示词库，案例均追溯到原帖|

### AI 开源应用

|名称|Star|简介|
|---|---|---|
|[AI 驱动的数据库: evadb](https://github.com/georgia-tech-db/evadb)|![GitHub Repo stars](https://badgen.net/github/stars/georgia-tech-db/evadb) |用 SQL 调用 AI 模型查询图像视频文本（注：项目已归档，仅作参考）|

### 作者的 Awesome 系列

|名称|Star|简介|
|---|---|---|
|[:fire: Awesome-MCP-ZH](https://github.com/yzfly/Awesome-MCP-ZH)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/Awesome-MCP-ZH) |MCP 中文资源精选，MCP 指南、Claude MCP、MCP Servers / Clients|
|[awesome-context-engineering](https://github.com/yzfly/awesome-context-engineering)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/awesome-context-engineering) |上下文工程 (Context Engineering) 的资源、论文、工具与最佳实践合集|
|[awesome-chatgpt-zh](https://github.com/EmbraceAGI/awesome-chatgpt-zh)|![GitHub Repo stars](https://badgen.net/github/stars/EmbraceAGI/awesome-chatgpt-zh) |ChatGPT 中文指南，调教指南、应用开发指南、精选资源清单|
|[LangGPT](https://github.com/langgptai/LangGPT)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/LangGPT) |结构化提示词方法论与社区|
|[wonderful-prompts](https://github.com/langgptai/wonderful-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/wonderful-prompts) |精选优质提示词合集|
|[awesome-claude-prompts](https://github.com/langgptai/awesome-claude-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-claude-prompts) |Claude 提示词精选|
|[awesome-deepseek-prompts](https://github.com/langgptai/awesome-deepseek-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-deepseek-prompts) |DeepSeek 提示词与 V4 使用指南|
|[Awesome-AGI-Agents](https://github.com/yzfly/Awesome-AGI-Agents)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/Awesome-AGI-Agents) |AGI Agent 项目与论文清单|
|[awesome-okf](https://github.com/yzfly/awesome-okf)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/awesome-okf) |Google 开放知识格式（OKF）中文落点：规范译文、工具与生态清单|
|[awesome-skills-zh](https://github.com/yzfly/awesome-skills-zh)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/awesome-skills-zh) |Agent Skills 中文精选|
|[awesome-dsh-skills](https://github.com/yzfly/awesome-dsh-skills)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/awesome-dsh-skills) |DeepSeek Harness 技能 / 插件精选|
|[awesome-voice-agents](https://github.com/whobot-ai/awesome-voice-agents)|![GitHub Repo stars](https://badgen.net/github/stars/whobot-ai/awesome-voice-agents) |语音 Agent 全栈资源（STT / TTS / VAD / 框架）|
|[awesome-music-prompts](https://github.com/yzfly/awesome-music-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/awesome-music-prompts) |AI 音乐生成提示词|
|[awesome-design-html](https://github.com/yzfly/awesome-design-html)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/awesome-design-html) |118 套品牌风格 HTML 设计稿，作为 Claude Code Skill 使用|
|[awesome-jev-zh](https://github.com/yzfly/awesome-jev-zh)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/awesome-jev-zh) |Jev / TypeSafe 中文精选：官方资料、SDK、应用、Agent 工具与评测，每日自动收录热门项目|
|[awesome-computer-use](https://github.com/yzfly/awesome-computer-use)|![GitHub Repo stars](https://badgen.net/github/stars/yzfly/awesome-computer-use) |AI 电脑操作与自动化精选：浏览器、桌面、CLI、手机与云环境，附选型指南|
|[awesome-gemini-prompts](https://github.com/langgptai/awesome-gemini-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-gemini-prompts) |Gemini 提示词与官方提示指南（含 Gemini 4）|
|[awesome-grok-prompts](https://github.com/langgptai/awesome-grok-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-grok-prompts) |Grok 提示词与系统提示|
|[awesome-doubao-prompts](https://github.com/langgptai/awesome-doubao-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-doubao-prompts) |豆包结构化提示词与模型动态|
|[awesome-qwen-prompts](https://github.com/langgptai/awesome-qwen-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-qwen-prompts) |通义千问提示词与 Qwen 模型速览|
|[awesome-llama-prompts](https://github.com/langgptai/awesome-llama-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-llama-prompts) |Llama 提示模板与写法（含 Meta Muse 说明）|
|[Awesome-Multimodal-Prompts](https://github.com/langgptai/Awesome-Multimodal-Prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/Awesome-Multimodal-Prompts) |多模态（图像 / 视频 / 音频）提示词与模型清单|
|[awesome-system-prompts](https://github.com/langgptai/awesome-system-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-system-prompts) |各家大模型与 AI 产品的系统提示词收集|
|[awesome-deep-research-prompts](https://github.com/langgptai/awesome-deep-research-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-deep-research-prompts) |Deep Research 提示词与工具速览|
|[awesome-voice-prompts](https://github.com/langgptai/awesome-voice-prompts)|![GitHub Repo stars](https://badgen.net/github/stars/langgptai/awesome-voice-prompts) |语音 Agent 系统提示模板与语音模型清单|

### 更多 AI 资源

* [Github ChatGPT awesome 合集](docs/chatgpt.md)
* [泛函工具收集](https://zl49so8lbq.feishu.cn/wiki/wikcnu3kSXr75E50w8PFefhJMYf)
* [AI 研习社](https://zl49so8lbq.feishu.cn/wiki/wikcnu3kSXr75E50w8PFefhJMYf)

## 作者

作者：云中江树

微信公众号：云中江树
