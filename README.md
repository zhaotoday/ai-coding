#### 产品
- [阿里云 OPC](https://opc.aliyun.com/)
- [lazycodex](https://lazycodex.ai/)
- [aionui](https://www.aionui.com/zh/)
- [讯飞星辰MaaS平台](https://maas.xfyun.cn/packageSubscription)
- [GLM Coding Plan](https://www.bigmodel.cn/glm-coding)
- [方舟 Coding Plan](https://www.volcengine.com/activity/codingplan)
- [qodo](https://www.qodo.ai/)
- [code.fun](https://code.fun/)
- [flowstep](https://flowstep.ai/)
- [iFlow CLI](https://platform.iflow.cn/cli/quickstart)
- [bolt.new](https://bolt.new/)
- [v0](https://v0.app/)
- [mastergo](https://mastergo.com/)
- [comate](https://comate.baidu.com/zh)
- [humanlayer](https://www.humanlayer.dev/)
- [CodeBuddy](https://copilot.tencent.com/ide/)
- [penpot](https://penpot.app/)
- [kiro](https://kiro.dev/)
- [trae](https://www.trae.ai/)
- [windsurf](https://windsurf.com/)
- [qoder](https://qoder.com/)
- [trypear](https://trypear.ai/)

#### 文档
- [OpenSpec-practise](https://github.com/ForceInjection/OpenSpec-practise)
- [OpenSpec 中文文档](https://openspec.radebit.com/)
- [Easy-Vibe](https://github.com/datawhalechina/easy-vibe)
- [详解8款AI编程工具：哪款更适合你？](https://r2eid0qxt4.feishu.cn/wiki/U5bQwejpBixYEjkCASJcsmdInfK)
- [AI辅助开发的基础概念](https://niunaiclub.online/posts/70)

#### 笔记
- [Cluade Code学习笔记](https://uahbgrt760r.feishu.cn/wiki/O9i6wr1CaixnBrkOrhQcHWmtnTM)

#### 规范驱动开发
- [GIthub 超火 AI 编程工作流 Matt Pocock Skills 、OpenSpec，保姆级教程详细讲解](https://www.bilibili.com/video/BV1c9M96LEoF/)
- [别让 AI 瞎写了！彻底吃透 Matt Pocock Skills：给 Coding Agent 装上真正的工程心智！](https://www.bilibili.com/video/BV1DpaT6pEwJ/)
- [精讲OpenSpec，从操作到原理，吃透这个AI编程提效的神器](https://www.bilibili.com/video/BV1eU5A6MERk)
- [从头脑风暴到代码审查：Superpowers 完整工作流指南](https://www.bilibili.com/video/BV1w2PPzGENp/)
- [OpenSpec 使用（规范驱动开发实战工具）](https://www.bilibili.com/video/BV1Kb5z6oEkP/)
- [抛弃Superpowers？深度拆解OpenSpec：轻量级AI编程框架的逆袭](https://www.bilibili.com/video/BV1UuT96HEWV/)
- [OpenSpec 规范驱动开发详解 让 AI 编程变得可预测 —— Spec-Driven Development](https://www.bilibili.com/video/BV1jpDZBnEhB/)
- [先对齐意图再写代码！OpenSpec让AI编程不再翻车｜AI编程实战 #04](https://www.bilibili.com/video/BV1hYwDzSE7A/)
- [让你的 Claude Code 和 Codex 效率提升 10 倍！Trellis 使用教程](https://www.bilibili.com/video/BV1RgGi6sENH)
- [Gstack 探究](https://www.bilibili.com/video/BV1meRvBEEVn)
- [superpowers 探究](https://www.bilibili.com/video/BV1gCVV6tEJM/)
- [AI编程实战：OpenSpec入门教程](https://www.bilibili.com/video/BV1AH5Y6MEz3)
- [comet](https://github.com/rpamis/comet)
- [superpowers](https://github.com/obra/superpowers)
- [OpenSpec](https://github.com/Fission-AI/OpenSpec)
- [mattpocock-skills-zh-CN](https://github.com/vinvcn/mattpocock-skills-zh-CN)
- [spec-kit](https://github.com/github/spec-kit)
- [gstack](https://github.com/garrytan/gstack)
- [potpie](https://github.com/potpie-ai/potpie)

#### 开源

Star 数取自 GitHub 页面，统计日期为 **2026-10-04**。同一仓库的重复链接已合并，地址改为当前仓库，介绍里保留原名单中的名字。每个分类内按 Star 从高到低排列。没有公开 Star 的站点放在该分类末尾。

##### 编程 Agent 与 IDE

直接在终端、编辑器或桌面里写代码、改代码、跑命令的编程助手。

- [opencode](https://github.com/anomalyco/opencode) · ⭐ 211,676

  开源 AI 编程 Agent，官网 [opencode.ai](https://opencode.ai)。提供终端 CLI，支持 npm、bun、pnpm、yarn、scoop、choco、brew 和 Arch 的 pacman 安装，文档有简体中文等多种语言。仓库已从 `sst/opencode` 迁到 `anomalyco/opencode`。它跑在本机项目目录里，用来读代码、改文件、执行命令，是目前名单里 Star 最高的编程 Agent 本体。

- [claw-code](https://github.com/ultraworkers/claw-code) · ⭐ 195,223

  用 Rust 做的一个「Agent 自己维护的展品」，由 LazyCodex、Gajae-Code 这类 harness 规划、执行、校验和打标签，作者明确说它不是拿来日常使用的生产级产品。仓库更像一座由 Agent 运营的博物馆：展示无人工介入也能把一个代码库长期养着。Star 很高，但不要把它当成 Claude Code 或 OpenCode 的替代品。

- [pi](https://github.com/earendil-works/pi) · ⭐ 112,301

  原名单中的 `badlogic/pi-mono`，现地址是 `earendil-works/pi`。一套可扩展的 Agent harness：统一的多供应商 LLM API、带工具调用的 Agent 循环、终端 UI，以及编码 Agent CLI。默认故意不做子 Agent 和 plan mode，改用扩展、skills、提示模板、主题和可通过 npm 或 git 分发的 Pi 包来定制。可以交互使用，也可以走 print、JSON、RPC，或用 TypeScript SDK 嵌进别的应用。Node.js 需要 22.19 以上。它本身不限制文件系统和网络权限，需要隔离时要自己放进容器。

- [goose](https://github.com/aaif-goose/goose) · ⭐ 54,927

  Linux 基金会 Agentic AI Foundation 下的开源 Agent，用 Rust 写，同时提供 macOS、Linux、Windows 桌面应用、CLI 和可嵌入的 API。不限于写代码，也可以做调研、写作、自动化和数据分析。支持 Anthropic、OpenAI、Google、Ollama、OpenRouter、Azure、Bedrock 等 15 家以上供应商，也能用已有的 Claude、ChatGPT、Gemini 订阅，并通过 MCP 接 70 多个扩展。

- [continue](https://github.com/continuedev/continue) · ⭐ 36,106

  早期有代表性的开源编程 Agent，提供 CLI、VS Code 扩展和 JetBrains 插件，配置方式集中在官方文档。仓库说明里写明 `continuedev/continue` 已不再积极维护，对所有用户只读，最后一次发布是打磨过的 2.0.0，去掉了匿名遥测和登录。可以当历史实现和本地配置参考，不适合当作还在迭代的主工具。

- [tabby](https://github.com/TabbyML/tabby) · ⭐ 33,893

  可自托管的 AI 编程助手，定位是 GitHub Copilot 的开源、本地部署替代。不依赖独立数据库或云服务，自带 OpenAPI，方便接到 Cloud IDE 等已有设施。有 Docker 镜像和中文、日文文档。适合必须把模型和补全服务留在内网的团队，而不是再套一层商业 IDE。

- [crush](https://github.com/charmbracelet/crush) · ⭐ 28,480

  Charm 团队做的终端编程 Agent，作者把更早的 `opencode-ai/opencode` 收进了这个项目。会话可以多开，中途能换模型且保留上下文，会用 LSP 补上下文，也能通过 MCP（http、stdio、sse）加能力。模型可以是内置列表，也可以接任何 OpenAI 或 Anthropic 兼容接口。macOS、Linux、Windows PowerShell 的终端都是一等支持。

- [kilocode](https://github.com/Kilo-Org/kilocode) · ⭐ 27,488

  覆盖 VS Code、JetBrains 和 CLI 的开源编程 Agent。模型列表超过 500 个，任务中途可以切换，按模型供应商原价计费、不加价，开始时也不强制自备 API key。适合已经有编辑器习惯、又不想被单一模型绑死的人。

- [Roo Code](https://github.com/RooCodeInc/Roo-Code) · ⭐ 24,289

  嵌在代码编辑器里的 AI 开发团队，而不是单轮补全。README 提供包括简体中文在内的多语言说明。它沿 Cline、Roo 这一支的 Agent 模式：在编辑器里读项目、改文件、跑命令，并把多角色协作放进同一套界面。适合希望 Agent 留在 IDE 里、而不是另开一个终端产品的人。

- [claude-code](https://github.com/claude-code-best/claude-code) · ⭐ 22,800

  社区维护的 Claude Code 兼容实现，项目自称可以本地构建、运行和调试，并跟进了部分原本要登录官方账号才能用的能力，同时关掉了一些对外上报点。配置上试图兼容官方 Claude Code。这不是 Anthropic 官方仓库。是否接入自己的账号和订阅，需要自行确认服务条款。

- [DeepCode](https://github.com/HKUDS/DeepCode) · ⭐ 16,669

  香港大学数据科学实验室的开放式 Agentic Coding 项目，强调 Agent harness、循环工程和多 Agent 编排。同一套本地服务上提供 TUI、桌面和 Web 客户端，桌面端能看到会话、目标、工具调用、代码改动和校验过程。适合想看「多 Agent 怎么分工写代码」的完整界面，而不只是一条 CLI。

- [plandex](https://github.com/plandex-ai/plandex) · ⭐ 15,688

  面向大任务和真实仓库的终端编程 Agent。可以规划和执行跨很多步、动几十个文件的改动；直接上下文大约到 2M token，单个文件约 10 万 token，再用 tree-sitter 项目地图索引更大的目录。生成的 diff 先放在沙箱里，确认后才落到项目文件。也支持本地自托管。

- [Aperant](https://github.com/AndyMik90/Aperant) · ⭐ 14,578

  原名单中的 Auto-Claude。自主多 Agent 编程框架，负责规划、实现和验证。作者说明项目没有停，正在把整个应用重写成 Aperant 3.0：在本地桌面之外加云能力，协议仍是 AGPL-3.0。因此现在的提交历史看起来会比较静，功能以 3.0 重建为准。

- [opencode](https://github.com/opencode-ai/opencode) · ⭐ 13,786

  用 Go 写的早期终端编程助手，仓库已归档。项目由原作者和 Charm 团队继续，新家是 [crush](https://github.com/charmbracelet/crush)。这里保留是因为原名单单独列了它；新工作不要再往这个地址提。

- [MonkeyCode](https://github.com/chaitin/MonkeyCode) · ⭐ 4,789

  长亭开源的企业级 AI 研发平台，不是个人向的氛围编程工具。内置开发环境、模型、任务和需求管理，可以在浏览器里直接开任务，也可以在企业内网私有部署。任务跑在服务端环境里，覆盖构建、测试和预览；模型侧接了 GLM、Kimi、MiniMax、Qwen、DeepSeek 等。有 iOS 和 Android 客户端，离开电脑后任务还能继续。在线入口是 monkeycode-ai.net。协议为 AGPL-3.0。

- [auto-dev](https://github.com/phodal/auto-dev) · ⭐ 4,553

  原名单中的 `unit-mesh/auto-dev`，现仓库是 `phodal/auto-dev`。AutoDev Xiuper 是基于 Kotlin Multiplatform 的多 Agent 开发平台，目标是同一套能力覆盖文档调研、编码、代码审查、数据查询、产物生成和 Web 交互，并跑在 IntelliJ、VS Code、CLI、桌面 JVM、Android、iOS、JS/WASM 和 Server 上。目前 README 标的是 3.0 Alpha。

- [costrict](https://github.com/zgsm-ai/costrict) · ⭐ 4,444

  原名单链接的是官网 [costrict.ai](https://costrict.ai/)，站点标题是「企业级 AI 研发基础设施」。对应开源仓库是 `zgsm-ai/costrict`，定位是面向企业的严格 AI 编程器，包含 AI Agent、AI Code Review 和 AI 补全，强调质量优先而不是一次性生成。Star 数是这个 GitHub 仓库的。

- [open-agent-sdk](https://github.com/codeany-ai/open-agent-sdk-typescript) · ⭐ 2,744

  进程内的 Agent SDK，用来替代必须拉起 `claude` 子进程的 Claude Agent SDK。Agent 循环跑在当前进程里，同时支持 Anthropic 和 OpenAI 兼容接口，因此可以部署到云函数、无服务器、Docker 和 CI。另有 Go 版本 `open-agent-sdk-go`。适合自己写产品、又不想绑定某一家 CLI 的人。

- [autoforge](https://github.com/AutoForgeAI/autoforge) · ⭐ 1,771

  原名单中的 `leonvanzyl/autocoder`。基于 Claude Agent SDK 的长时自主编程 Agent，用初始化 Agent 加编码 Agent 的两段式循环，跨多个会话把应用做完，并带一个 React 界面看进度。README 提醒：把 Claude 订阅登录接到第三方 Agent 可能违反 Anthropic 政策，建议改用控制台 API key。

- [neovate-code](https://github.com/neovateai/neovate-code) · ⭐ 1,560

  终端编程 Agent，npm 包是 `@neovate/code`。可以生成代码、修 bug、做审查、补测试，既能交互，也能 headless。各供应商走各自的 API key 环境变量，没有 key 时用 `/login` 选择供应商。项目站点是 neovateai.dev。

- [autobe](https://github.com/wrtnlabs/autobe) · ⭐ 1,361

  用自然语言描述后端需求，再生成 TypeScript 后端的 Agent。它靠编译器技能约束输出，目标是生成物能被编译、并带 e2e 测试，从而从原型走到可以继续开发的后端，而不是只吐出一段看起来能跑的代码。包名 `@autobe/agent`，文档在 autobe.dev。

- [eca](https://github.com/editor-code-assistant/eca) · ⭐ 1,022

  Editor Code Assistant，一套与编辑器无关的结对编程协议。聊天、重写和补全都走同一份配置，Emacs、VS Code、IntelliJ 和桌面端可以共用。可以配置多个 Agent 和子 Agent，模型不绑死在某一个编辑器插件里。适合已经有自己的编辑器、只想补一层统一 AI 能力的人。

- [an-codeAI](https://github.com/sparrow-js/an-codeAI) · ⭐ 727

  仓库 README 现在的产品名是 needware.dev / genfly.dev。浏览器里的开源全栈生成平台：描述应用后生成代码、预览并部署，技术栈是 Next.js、React 和 TypeScript。演示站是 genfly.dev。它更接近「在网页里做完整应用」，而不是本地 CLI。

- [Gemini-CLI-UI](https://github.com/cruzyjapan/Gemini-CLI-UI) · ⭐ 687

  给 Google Gemini CLI 做的响应式 Web 界面，桌面和手机都能用。可以看当前项目和会话、继续对话、开集成终端、在文件树里改文件，并带 Git 和会话管理。Gemini CLI 本身仍是执行引擎，这个仓库补的是随时可打开的图形壳。

- [mastra-code-ui](https://github.com/mastra-ai/mastra-code-ui) · ⭐ 58

  用 Mastra 和 Electron 做的桌面编程 Agent。通过 Mastra 的模型路由接 Claude、GPT、Gemini 等 70 多个模型，支持 Anthropic 和 OpenAI 的 OAuth 登录。会话按项目持久化，换 worktree 也能接着聊。工具包括看文件、按 AST 改代码、grep、glob、shell 和网页搜索，MCP 可按项目或全局配置，权限按工具类别做允许、询问或拒绝。

##### 工作台、编排与远程控制

自己不替代底层模型，而是把多个编程 Agent 放到同一块看板、桌面或手机上一起调度。

- [lobehub](https://github.com/lobehub/lobehub) · ⭐ 82,978

  LobeHub 现在的定位是「首席 Agent 运营者」：雇佣、排班并汇报一整支 AI 团队，让 Agent 按 7×24 运转，人不必一直守在线。有简体中文 README、官网、更新日志和文档。它已经从早期的聊天前端，转成以 Agent 为工作单位的运营台。默认分支是 `canary`。

- [multica](https://github.com/multica-ai/multica) · ⭐ 51,912

  可自托管的工作区，把任务派给编程 Agent，就像派给同事：Agent 领 issue、回报进度、提出阻塞，再交回给人审查。对接的是你已经在用的 Agent CLI，不把人锁进某一家模型。有云快速开始和自托管文档，源码可用。适合已经有 Claude Code 或 Codex，但缺一块人和 Agent 共用的任务板的团队。

- [AionUi](https://github.com/iOfficeAI/AionUi) · ⭐ 33,304

  开源 Cowork 应用，用来 7×24 驱动 OpenClaw、Hermes、Claude Code、Codex、OpenCode 等 20 多种 CLI Agent。支持自定义助手、把多个 Agent 编成一组、远程访问和跨平台。零配置即可用自带 Agent，也可以填任意 API key。官网 aionui.com，有中文社区。名单「产品」一节里的 aionui 官网和这个仓库是同一产品的站点与源码。

- [vibe-kanban](https://github.com/BloopAI/vibe-kanban) · ⭐ 28,257

  用看板管 Claude Code、Gemini CLI、Codex 等编程 Agent 的计划与执行。issue 用来排优先级和分工，工作区给 Agent 单独的分支、终端和开发服务器。作者已公告项目正在日落，仓库仍在，但不要把它当成长期维护的新产品。适合参考「人负责计划和审查、Agent 负责执行」这种分工，而不是作为新部署的第一选择。

- [t3code](https://github.com/pingdotgg/t3code) · ⭐ 24,878

  Agent harness 的控制面。本机已经登录的 Claude Code、Codex、Cursor、Grok Build、OpenCode、Google Antigravity，都可以从 iOS、Android、Web 和 Electron 桌面控。作者强调不卖订阅，做它是因为想要更好的多 Agent 操作体验。适合人在外面、Agent 还在自己电脑上跑的场景。

- [happy](https://github.com/slopus/happy) · ⭐ 24,004

  Claude Code 和 Codex 的手机与 Web 客户端，带实时语音和端到端加密。有 macOS 桌面、iOS、Android 和 app.happy.engineering。电脑上安装 `happy` CLI 后，手机端连的是你自己的会话，而不是把代码交到第三方托管 Agent。原名单里这条链接出现了两次，这里只保留一条。

- [paseo](https://github.com/getpaseo/paseo) · ⭐ 19,403

  在桌面和手机上同时编排多个编程 Agent 的界面。Agent 跑在你自己的机器和开发环境里，可用 Claude Code、Codex、Copilot、OpenCode、Pi、Antigravity 和 Muse Code。支持语音下达任务，以及 iOS、Android、桌面、Web 和 CLI。开始在工位、之后在手机上查看，是它主打的用法。

- [superset](https://github.com/superset-sh/superset) · ⭐ 14,865

  用来并行编排大量编程 Agent 的桌面 IDE。Claude Code、Codex 或其他 CLI Agent 可以带着你自己的订阅跑，同一个工作区里有终端、代码审查和浏览器预览。目前安装包以 macOS 为主，文档提供给人和 Agent 读的 Markdown 索引。注意它和 Apache Superset 不是同一个项目。

- [cc-haha](https://github.com/NanmiCoder/cc-haha) · ⭐ 14,855

  本地优先的跨平台桌面工作台，面向 Claude Code 和其他 Agent。一个应用里集中了多会话和全局搜索、用分支或 git worktree 启动、diff 审阅、内置浏览器预览、图形化权限审批、多模型（Claude、ChatGPT、Grok、本地端点）、MCP 和子 Agent 管理、Agent 团队、动态工作流、请求追踪、Computer Use、技能市场、桌面宠物，以及 H5、微信、飞书、钉钉、Telegram、WhatsApp 接入。macOS 上的 Computer Use 可以操作其他应用，同时不占用真实键鼠。站点 cchaha.ai。

- [ekko-studio](https://github.com/EKKOLearnAI/ekko-studio) · ⭐ 11,293

  原名单中的 hermes-studio。本地优先的多 Agent 工作区，桌面应用和可自托管的 Web 控制台都有，覆盖聊天、编码和可视化流程。支持 Hermes Agent、Ekko Agent、Claude Code、Codex、Pi、Grok、OpenCode 和 DeepSeek Harness。npm 包现为 `ekko-studio`，旧的 `hermes-web-ui` 命令还保留着。

- [open-vibe-island](https://github.com/Octane0411/open-vibe-island) · ⭐ 2,041

  macOS 菜单栏或刘海处的开源控制中心，用来看编程 Agent 的会话、批准操作，并一键跳回对应终端。本地优先，无账号无遥测，SwiftUI 原生应用，GPL-3.0。支持 Claude Code、Codex、Cursor、Gemini CLI、OpenCode、Pi 等 13 个 Agent，以及 Terminal、Ghostty、iTerm2、VS Code、JetBrains 等终端和 IDE。它是 Vibe Island 的开源替代，不是又一个会写代码的 Agent。

- [agentrove](https://github.com/Mng-dev-ai/agentrove) · ⭐ 332

  原名单中的 claudex。可自托管的编程工作区，用 ACP 适配器同时跑 Antigravity、Claude Code、Codex、Copilot、Cursor、Grok 和 OpenCode。每个工作区可以是 Docker 或本机沙箱，里面有聊天、编辑器、终端、文件树、diff、密钥和 git。工作区可以来自空目录、git clone、本地文件夹或 GitHub 仓库。

##### Harness、Skills 与工作流

给已有编程 Agent 加技能、角色、记忆、状态栏和固定流程的层。Agent 本体仍是 Claude Code、Codex、Cursor 或 OpenCode。

- [ECC](https://github.com/affaan-m/ECC) · ⭐ 272,524

  原名单里的 ECC 和 everything-claude-code 是同一个仓库，现名 ECC。它是 Agent harness 的性能与工程化系统：skills、instincts、记忆、安全，以及「先调研再写代码」，覆盖 Claude Code、Codex、OpenCode、Cursor 等。安装渠道作者只承认本仓库、npm 包 `ecc-universal` 和 `ecc-agentshield`、GitHub App，以及 ecc.tools。有简体中文文档。第三方转载不在维护范围内。

- [agency-agents](https://github.com/msitarzewski/agency-agents) · ⭐ 156,192

  一整套带人设、流程和交付物的专职 Agent 角色，从前端实现到社区运营、从「注入趣味」到「核对现实」都有。可以当成现成的专家花名册，装进自己的编程 Agent。另有 macOS、Linux、Windows 原生应用 agencyagents.app，用来浏览和安装这些角色。协议 MIT。

- [gstack](https://github.com/garrytan/gstack) · ⭐ 134,976

  Y Combinator CEO Garry Tan 公开的 Claude Code 配置，大约 23 个意见很强的工具，分别扮演 CEO、设计师、工程经理、发布经理、文档工程师和 QA。目标是让一个人用 Agent 按小团队的节奏交付。原名单在「规范驱动开发」和「开源」里都有它，这里按开源仓库收录。

- [ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) · ⭐ 132,883

  给编程 Agent 用的 UI/UX 设计技能，让生成界面时按一套设计情报来，而不是每次都从空白审美开始。覆盖多种平台和框架，站点 uupm.cc，有简体中文说明。适合在 Claude Code、Cursor、Codex 里做界面、又不想每次重写设计要求的人。

- [caveman](https://github.com/JuliusBrussee/caveman) · ⭐ 109,676

  一个故意把话说短的技能加代理，用来砍编程 Agent 的 token。代码保持精确，解释改成极简措辞。作者给出的数字包括：代理路径上输入 token 大约少三分之一，网页快照比 Playwright 小两个数量级，输出侧大约便宜 1.4 到 2.4 倍。Adobe Research 和 JetBrains 都讨论或测过同类「洞穴人说话」方式。它优化的是上下文成本，不是模型能力。

- [ruflo](https://github.com/ruvnet/ruflo) · ⭐ 73,826

  原名单中的 claude-flow，仓库现名 ruflo。面向 Claude Code 和 Codex 的 Agent 元 harness，用来部署多智能体群、协调自主工作流，并带自适应记忆、自学习、联邦和向量 RAG。npm 包名是 `ruflo`，另有 `@claude-flow/codex`。有简体中文 README。

- [oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent) · ⭐ 69,786

  OpenCode 生态里的增强层，简称 OmO。5.0 转向 Pi：用官方安装脚本装上之后，在提示里加上作者定义的关键词即可走多模型 ultracode，并带记忆系统和 CodeMode。README 把它描述成个人侧项目，由 OpenGateway 等赞助。适合已经在用 OpenCode 或 Pi、想要现成编排而不是自己写 harness 的人。

- [skills](https://github.com/vercel-labs/skills) · ⭐ 33,082

  原名单中的 `vercel-labs/add-skill`，现仓库是 `vercel-labs/skills`。开放 Agent skills 的 CLI，命令是 `npx skills`。可以把一个仓库里的 skill 装进 OpenCode、Claude Code、Codex、Cursor 等 70 多种 Agent，也可以不安装、只生成一段提示再交给某个 Agent。它是技能的分发器，本身不包含业务技能。

- [claude-code-templates](https://github.com/davila7/claude-code-templates) · ⭐ 32,360

  配置和监控 Claude Code 的 CLI，npm 包同名。用来管理模板、组件和运行状态，而不是另一个编程模型。仓库 README 以安装徽章和赞助说明为主，具体模板在仓库目录里。适合想把 Claude Code 的配置从手改 JSON 收成可复用模板的人。

- [claude-hud](https://github.com/jarrodwatts/claude-hud) · ⭐ 28,293

  Claude Code 状态栏插件，把上下文占用、速率限制、正在用的工具、在跑的子 Agent 和待办进度固定显示在输入框下方。通过插件市场安装，再用 `/claude-hud:setup` 指到状态栏。有中文文档。它不改模型行为，只让长时间会话看得见 Agent 正在做什么。

- [Archon](https://github.com/coleam00/Archon) · ⭐ 23,611

  开源的 AI 编程 harness 构建器，把规划、实现、验证、审查、开 PR 写成 YAML 工作流，再在各个项目里重复执行。类比是 Dockerfile 之于环境和 GitHub Actions 之于 CI。作者要解决的问题是：同一句「修这个 bug」，模型每次可能跳过计划或测试。原名单里这个仓库出现了两次，这里只保留一条。

- [teamai-cli](https://github.com/Tencent/teamai-cli) · ⭐ 5,114

  腾讯开源的 TeamAI，口号是让整个团队而不是个人变成 AI native。它把分散在各人机器和各个 Agent 上的做法收成团队共用的技能和约定，通过 `/teamai` 从零建团队或加入已有团队。安装方式是把仓库里的 teamai skill 交给你已经在用的 AI 工具。适合一个小组要共享同一套 Agent 工作方式，而不是每个人各写一份 CLAUDE.md。

- [vibe-tools](https://github.com/eastlondoner/vibe-tools) · ⭐ 4,826

  早期也叫 cursor-tools。给 Cursor 等 Agent 加一组现成命令和「AI 团队」技能，让单个 Agent 能转手调用更专门的能力。README 用一张命令表说明每个能力怎么触发。适合已经用 Cursor Agent、想少写重复提示的人。

- [claude-code-workflows](https://github.com/OneRedOak/claude-code-workflows) · ⭐ 3,897

  作者从 Claude Code 发布日起在自己的 AI 创业公司里积累的工作流和配置，配有 YouTube 讲解。其中包括一套自动代码审查：用 slash command 和 GitHub Actions 做双环，让 Agent 先处理语法、完整性和常规问题。它是可抄的流程样例，不是通用平台。

- [nuxt-skills](https://github.com/onmax/nuxt-skills) · ⭐ 716

  给 AI 编程助手用的 Vue、Nuxt 和 NuxtHub skills。和 Nuxt 社区关于「把 Agent skills 打进 Nuxt 模块」的 RFC 相关。装上之后，Agent 在写 Nuxt 项目时会按这些技能里的约定行事，而不是只靠模型对框架的模糊记忆。

- [seo-geo-claude-skills](https://github.com/aaron-he-zhu/seo-geo-claude-skills) · ⭐ 212

  现在是指路仓库。16 个 SEO 和 GEO（生成式引擎优化）技能已经迁到 `aaron-he-zhu/aaron-marketing-skills`，作为大约 120 个技能包里的一组，带统一契约和评测门禁。本仓库独立的 20 技能版本冻结在 tag `v9.9.12`，不再更新。新安装应指向新仓库。

##### 规范驱动与上下文工程

把需求、计划和项目约定写成仓库里的文件，让 Agent 下一轮还能读到，而不是只靠对话记忆。

- [OpenSpec](https://github.com/Fission-AI/OpenSpec) · ⭐ 71,013

  给 AI 编程助手用的规范驱动开发框架。作者强调流程是流动的、可迭代的、偏简单，并且优先照顾已有代码库而不是只适合从零开始的项目。新的 artifact 工作流用 `/opsx:propose` 从一句话提议开始，再生成可跟踪的规范产物。npm 包是 `@fission-ai/openspec`。原名单在「规范驱动开发」和「开源」里都有它。

- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) · ⭐ 27,278

  用仓库里的 markdown 做持久计划，面向长任务。`task_plan.md`、`findings.md` 和 `progress.md` 留在磁盘上，生命周期钩子每轮把计划重新注入上下文，所以 `/clear`、压缩上下文或崩溃之后还能接着做。作者用 Manus 式的文件规划做对照，并给出盲测对比。可从 npm、Claude Code 插件市场或 `npx skills` 安装，覆盖 Codex、Cursor、OpenCode 等 60 多种 Agent。

- [Trellis](https://github.com/mindfold-ai/Trellis) · ⭐ 14,870

  开箱即用的 AI 编程工程框架。规格、任务和记忆写进仓库，避免每个新会话都从零开始。`.trellis/spec/` 里的约定会在会话中自动注入；PRD、实现上下文、审查上下文和任务状态按任务收在一起。有简体中文文档。任何编程 Agent 都可以消费这套文件，它本身不是又一个模型。

- [context-engineering-intro](https://github.com/coleam00/context-engineering-intro) · ⭐ 13,888

  上下文工程入门模板，以 Claude Code 为中心，但方法可用于其他助手。仓库用 `CLAUDE.md` 放项目规则，用 `examples/` 放代码范例，让 Agent 在动手前就有约束和样例。作者把上下文工程放在提示词工程和氛围编程之上：先把完成任务所需的信息准备好，再让模型写。

- [plannotator](https://github.com/backnotprop/plannotator) · ⭐ 9,131

  本地浏览器里的标注面，插在 Claude Code、Codex、Copilot CLI、Gemini CLI、OpenCode、Kiro、Droid、Amp、Pi 等 Agent 的钩子上。Agent 给出计划、规格、markdown 或 HTML 时，人可以在实现前标注；也可以审 diff 和 PR，再把意见一键送回 Agent。它解决的是「计划在终端里一闪而过、人来不及改」的问题。

- [gsd-2](https://github.com/gsd-build/gsd-2) · ⭐ 7,777

  元提示、上下文工程和规范驱动系统，让 Agent 长时间自主工作时仍抓住总目标。这个仓库已经不再是开发主线，项目改在 [open-gsd/gsd-pi](https://github.com/open-gsd/gsd-pi) 继续，新仓库统计日 Star 为 1,288，npm 包是 `@opengsd/gsd-pi`。原名单指向的是旧地址，所以排序仍按旧仓库的 7,777。

- [vibe-coding-prompt-template](https://github.com/KhazP/vibe-coding-prompt-template) · ⭐ 3,125

  现在的流程叫 Vibe Workflow：先决定做什么，再检查什么是通的，坏了还能恢复。用 Claude Code、Cursor、Codex 或 Gemini CLI 在项目里运行 `npx vibeworkflow`，它会看现有代码，再分流到新项目、继续旧项目或故障恢复。Quick、Guided、Deep 三档问题量和项目规模成比例，用来生成 PRD、技术设计和 MVP 范围。

- [AI-Coding-Style-Guides](https://github.com/lidangzzz/AI-Coding-Style-Guides) · ⭐ 496

  给氛围编程和软件工程 Agent 用的编码风格指南，目标是既让模型写得更短，也让人还能读。可执行部分在 `AI_Coding_Style_Guide_prompts.toml`，把提示词拷进自己的规则系统即可。有中文 README。它约束的是生成代码的写法，不是项目流程。

##### 代码理解与知识图谱

把仓库变成可查询的图或文档，让 Agent 少读无关文件。

- [Understand-Anything](https://github.com/Egonex-AI/Understand-Anything) · ⭐ 85,219

  原名单中的 `Lum1104/Understand-Anything`。把代码库、知识库或文档做成可交互的知识图谱，再探索、搜索和提问。多 Agent 流水线分析项目，图里包含文件、函数、类和依赖。以 Claude Code 插件的形式提供，也适用于 Codex、Cursor、Copilot 和 Gemini CLI。有简体中文说明。适合接手一个自己没写过的大仓库。

- [codegraph](https://github.com/colbymchenry/codegraph) · ⭐ 73,155

  本地代码知识图谱，代码一变就自动同步，内核用 Rust。服务于 Claude Code、Codex、Gemini、Cursor、OpenCode、Antigravity、Kiro、Copilot 和 Hermes。目标是用更少的 token 和工具调用拿到刚好相关的符号，数据不出本机。npm 包 `@colbymchenry/codegraph`，文档在 colbymchenry.github.io/codegraph。

- [code-review-graph](https://github.com/tirth8205/code-review-graph) · ⭐ 31,913

  同样是本地代码图，但是为代码审查收窄上下文。用 tree-sitter 建结构图并增量更新，再通过 MCP 或 CLI 把「这次改动真正碰到的文件」交给 Agent，避免审查时把整个仓库重读一遍。有中文文档、GitHub Action 和可复现的基准测试。

- [deepwiki-open](https://github.com/AsyncFuncAI/deepwiki-open) · ⭐ 18,122

  DeepWiki 的开源实现。输入 GitHub、GitLab 或 Bitbucket 仓库后，分析结构、生成文档和示意图，整理成可浏览的 wiki，并提供以代码为中心的导览。有简体中文 README。适合给一个陌生仓库先出一份能点开的说明，而不是只返回聊天回答。

- [likec4](https://github.com/likec4/likec4) · ⭐ 5,806

  原名单链接的是官网 [likec4.dev](https://likec4.dev/)。LikeC4 是架构即代码：用代码描述架构，工具链生成始终跟代码一起演进的 C4 图，并支持协作。Star 数来自 `likec4/likec4`。适合要在仓库里维护架构图、而不是另存一份会过期的绘图文件的团队。

- [FastCode](https://github.com/HKUDS/FastCode) · ⭐ 2,288

  面向大仓库的代码理解框架，强调更少 token、更快速度和可接受的准确度。提供 MCP 服务，可接到 Cursor、Claude Code 和 Windsurf。和 DeepCode 同属 HKUDS，但这个仓库聚焦「看懂现有代码」，不是从零生成项目。

##### 代码审查

在 PR、合并请求或提交前，用模型或规则指出问题。

- [open-code-review](https://github.com/alibaba/open-code-review) · ⭐ 43,606

  阿里巴巴开源的 AI 代码审查 CLI。内部版本服务过大量开发者并报出大量缺陷，开源后只要配置模型端点即可使用。它读 Git diff，把改动交给可使用工具的 Agent，输出行级评论；Agent 可以再读完整文件。架构是确定性流水线加 LLM，内置空指针、线程安全、XSS、SQL 注入等多语言规则，兼容 OpenAI 和 Anthropic 接口。有简体中文文档。

- [react-doctor](https://github.com/millionco/react-doctor) · ⭐ 14,952

  确定性扫描 React 代码，查出状态与 effect、性能、架构、安全、无障碍和可维护性问题，并标出过于复杂的组件和适合再组合的重复 JSX。支持 Next.js、Vite、Astro、TanStack、React Native 和 Expo。`npx react-doctor@latest` 做审计，`install` 子命令把技能装进 Claude Code、Cursor、Codex、OpenCode，让 Agent 下次少犯同样的错。也可以在 CI 里只报告本次改动引入的问题。原名单里出现两次，这里只保留一条。

- [ChatGPT-CodeReview](https://github.com/anc95/ChatGPT-CodeReview) · ⭐ 4,467

  用 ChatGPT 做代码审查的 GitHub App。官方托管的 Bot 只适合试用，有速率限制，作者建议自己部署。仓库含中文 README。它是较早一波「PR 上自动评论」的实现，模型接入方式比现在的多模型审查工具更单一。

- [run-gemini-cli](https://github.com/google-github-actions/run-gemini-cli) · ⭐ 2,100

  Google 官方 GitHub Action，在仓库里调用 Gemini CLI。可以自动审 PR、给 issue 分诊、按评论里的 `@gemini-cli` 改代码或做分析，也能用 `GEMINI.md` 提供项目说明。工作流包括分发、分诊、PR 审查和通用助手。密钥用 `GEMINI_API_KEY`。它是 CI 里的 Gemini，不是本地 IDE 插件。

- [sourcery](https://github.com/sourcery-ai/sourcery) · ⭐ 1,871

  自动代码审查。对 GitHub 仓库的 PR 给出变更摘要、高层意见和必要的行内建议，目标是接近同事审查的反馈，并减少人花在初审上的时间。产品站点是 sourcery.ai。这个 Star 数是开源仓库的，线上审查服务以厂商当前方案为准。

- [AI-Codereview-Gitlab](https://github.com/sunmh207/AI-Codereview-Gitlab) · ⭐ 1,858

  面向 GitLab，也支持 GitHub 和 Gitea 的自动审查。模型可接 DeepSeek、智谱、OpenAI、Anthropic、通义千问和 Ollama。审查结果推到钉钉、企业微信或飞书，并能按提交记录生成日报。有可视化 Dashboard 和多种评论风格。可选的 Agentic 模式允许模型在本地克隆的仓库里读文件、跑受限制的命令后再下结论。提供 Docker 部署。

- [Code-Review-GPT-Gitlab](https://github.com/mimo-x/Code-Review-GPT-Gitlab) · ⭐ 818

  另一个面向 GitLab 的大模型审查服务，支持 GPT、DeepSeek 等，并规划多 Agent 分工。可以接私有化模型，避免代码出内网。README 以中文为主，包含架构说明和部署文档。和上一则相比，它更早、功能面更窄，适合要自己改审查流程的团队。

- [mr-agent](https://github.com/zixingtangmouren/mr-agent) · ⭐ 89

  Node.js 服务：收到 GitHub、GitLab 或 Bitbucket 的合并请求 webhook 后触发 AI 审查，标出问题并给出修改建议。README 目前就是这段定位说明，没有展开部署细节，适合当作轻量 webhook 审查的起点。

- [ai-pre-commit-reviewer](https://github.com/ispuppy/ai-pre-commit-reviewer) · ⭐ 24

  Git pre-commit 钩子里的 AI 审查，有中文文档。支持 OpenAI、DeepSeek、Ollama 和 LM Studio。只看有意义的 diff，忽略纯删除，规则可按安全、性能和风格定制，反馈分高、中、低。用 `npx add-ai-review` 或 husky 挂进仓库。问题在提交前就被拦住，而不是等到 PR。

- [AI-CodeReview](https://github.com/x-y-17/AI-CodeReview) · ⭐ 18

  可挂 Git 或 SVN 钩子的审查工具，分析的是已经 `git add` 的变更。默认推荐 DeepSeek，也支持 Moonshot 和 OpenAI 兼容接口。输出可以是 Markdown 或控制台，维度包括质量、安全和性能，界面和反馈为中文。npm 包 `@x648525845/ai-codereview`，需要 Node.js 18 以上。

- [ai-code-reviewer](https://github.com/rideWind97/ai-code-reviewer) · ⭐ 14

  原名单中的 AICR 和 ai-code-reviewer 已指向同一仓库。用 Go 写的 PR 自动审查服务：校验 GitHub 或 GitLab webhook，拉取 diff，拆成 review unit，调用模型，再把摘要、行内评论和状态发回去。还包含大 PR 分级、密钥扫描、PostgreSQL 队列，以及仓库内 `.ai-review/SKILL.md`。README 写明当前是 MVP。

##### 设计、UI 与可视化

设计工具、设计系统语料，以及让 Agent 按某个视觉风格出界面的资料。

- [awesome-design-md](https://github.com/VoltAgent/awesome-design-md) · ⭐ 119,467

  从真实网站整理出的 `DESIGN.md` 集合。`DESIGN.md` 是 Google Stitch 提出的纯文本设计系统，Agent 读它来保持视觉一致，对应关系类似 `AGENTS.md` 管怎么做、`DESIGN.md` 管看起来怎样。把一份文件放进项目再让 Agent 按它做页面即可。集合覆盖 Claude、Vercel、Cursor、Linear 一类产品的用色、字体和布局规则，站点是 getdesign.md。

- [archify](https://github.com/tt-a1i/archify) · ⭐ 76,907

  给 Claude Code、Codex 等 Agent 的技能：把一句话、一份计划或一个代码库变成可交互的 HTML 图。用途从行程、学习地图到系统结构都有，生成后可以自己改、自己分享。有简体中文说明和在线示例。它产出的是可浏览的可视化，不是另一份 Mermaid 源码。

- [penpot](https://github.com/penpot/penpot) · ⭐ 60,677

  面向产品团队的开源设计平台，可自托管，因此设计文件和基础设施可以留在自己的环境里，方便合规。基于开放格式做界面设计与协作，是 Figma 一类工具的自建替代。协议为 MPL-2.0。名单「产品」一节里的 penpot.app 是同一项目的托管站。

- [ai-website-cloner-template](https://github.com/JCodesMore/ai-website-cloner-template) · ⭐ 35,603

  给编程 Agent 的项目模板：提供一个网址，让 Agent 把站点重做成干净的 Next.js 应用。作者建议 Claude Code 配较强模型，也支持 Codex、Cursor 和 OpenCode。适合对照着改一个已有页面，而不是从空白组件开始。使用时需要自己处理目标站点的版权和资产授权。

- [awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) · ⭐ 33,914

  GPT Image 2 / 2.5 的提示词与案例库，中文 README 称有 530 多个案例、20 多套工业级模板和可复用 skills，并有 2.5 同提示词对比。英文站把 Sunburst 和 Flare 分开介绍：前者偏精确编辑，后者偏日常出图。适合把图像生成提示词当成可版本管理的代码来维护。

- [onlook](https://github.com/onlook-dev/onlook) · ⭐ 26,856

  面向设计师的开源工具，在真实代码上做可视化设计和修改，而不是只画一张不能运行的稿。项目处于早期访问，有中文 README 镜像。目标用户是要直接改前端代码的设计师，以及希望设计动作落回仓库的开发者。

- [grapesjs](https://github.com/GrapesJS/grapesjs) · ⭐ 26,289

  可嵌入的开源网页搭建框架，用来做「不写代码也能拼模板」的下一代编辑器。它是框架而不是托管建站服务：拖拽 HTML、调样式，再导出模板。很多自建的落地页编辑器和邮件模板工具以它为内核。和上面那些 AI 设计项目相比，它本身不调用大模型。

- [awesome-design-systems](https://github.com/alexpate/awesome-design-systems) · ⭐ 26,061

  设计系统目录。每个条目标注是否包含可运行组件、语气指南、设计师源文件和公开源码，名单里有 Adobe Spectrum、Ant Design、Atlassian、政府设计系统等。适合找现成设计系统来对照，或给 Agent 指定一个可引用的组件库。

- [awesome-gpt-image-2-prompts](https://github.com/EvoLinkAI/awesome-gpt-image-2-API-and-Prompts) · ⭐ 17,278

  原名单中的 `awesome-gpt-image-2-prompts`，仓库已改名。以提示词为主的 GPT Image 2 示例集，大约 462 条，覆盖生成、编辑、设计和广告，按类别浏览后即可复制。有简体中文 README。和上一份案例库互补：这份更偏精选提示词，上一份更偏工业模板和 2.5 对比。

- [A2UI](https://github.com/a2ui-project/a2ui) · ⭐ 16,588

  原 Google 仓库，现地址是 `a2ui-project/a2ui`。Agent 到用户界面的开放格式：Agent 生成或填充可更新的富 UI，而不是只返回文本，并提供一组渲染器。当前生产版本是 v0.9.1，v1.0 规范仍是候选发布，v0.8 已过时。适合做「模型输出一块真正的界面」的产品。

- [Claudable](https://github.com/anymorph-ai/Claudable) · ⭐ 4,054

  用本机 CLI Agent 做网页应用的开源构建器，原仓库在 `opactorai/Claudable`。描述一个应用后，由 Claude Code、Codex、Gemini CLI、Qwen Code 或 Cursor Agent 生成代码并给出预览，再部署到 Vercel，数据库可用 Supabase。体验上接近托管的 AI 建站产品，但执行发生在你自己的 Agent 上。

- [antd-components-mcp](https://github.com/zhixiaoqiang/antd-components-mcp) · ⭐ 245

  给大模型查 Ant Design 的 MCP 服务，用来减少组件 API 幻觉。提供系统提示、组件文档、API、示例和更新日志查询。数据预先处理，README 写的预处理版本是 Ant Design V6.6.3（2026-09-07），也可以再抽其他版本。npm 包 `@jzone-mcp/antd-components-mcp`。

- [awesome-design-md 预览](https://tool.keylen.xyz/) · 无公开 Star

  原名单里第二条 awesome-design-md，指向在线预览站，页面标题是 Awesome-design-md Preview。它没有独立 GitHub 仓库，因此没有 Star。和上面的 VoltAgent 集合是同一类 `DESIGN.md` 资料的浏览入口，不单独参与 Star 排序。

##### 模型网关、路由与额度

在编程工具和模型供应商之间做协议转换、换供应商、看配额。接入订阅或改写客户端标识前，先看对应服务的条款。

- [cc-switch](https://github.com/farion1231/cc-switch) · ⭐ 139,887

  跨平台桌面一体化助手，管理 Claude Code、Claude Desktop、Codex、Gemini CLI、Grok Build、OpenCode、OpenClaw、Hermes、Pi 和 MiniMax Code。一键切换 API 供应商，并把 MCP、Skills 和提示词放在同一处，避免手改 JSON、TOML 或 YAML。官方站点只认 ccswitch.io。用 Tauri 做桌面端，有中文 README。

- [free-claude-code](https://github.com/Alishahryar1/free-claude-code) · ⭐ 56,558

  独立项目，声明与 Anthropic 无关。把 Claude Code、Codex、VS Code、Pi、OpenCode 等编程外壳接到作者列出的几十个供应商，覆盖免费额度、付费、订阅和本地模型，并支持终端、应用、IDE、手机和浏览器会话。README 中的供应商数量和免费 token 规模会变，以仓库当前说明为准。

- [CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) · ⭐ 54,077

  把 Antigravity、ChatGPT Codex、Claude Code、Grok Build、Muse Code、Devin 等 CLI 包成 OpenAI、Gemini、Claude、Codex 兼容的本地 API，从而用现有 CLI 登录去接其他客户端。多账号可以挂在同一代理后面。作者另有带图形界面的 EasyCLIProxyAPI。有中文 README。是否允许把订阅流量转成 API，取决于各供应商条款。

- [claude-code-router](https://github.com/musistudio/claude-code-router) · ⭐ 37,532

  本地控制面：把编程 Agent 的请求路由到不同模型，并编排工具。内置供应商预设，例如把 Kimi 的按量 API 或 Kimi Code 订阅接进来，订阅端点按原协议转发，API 端点自动做适配，还能看余额。它站在 Claude Code 和其他 Agent 前面，决定这次请求实际发给谁。

- [9router](https://github.com/decolua/9router) · ⭐ 30,265

  本地 AI 路由。把 Claude Code、Codex、Cursor、Cline、Copilot、Antigravity、OpenCode 等接到 40 多个供应商、100 多个模型，并做自动降级。作者还宣传 RTK 能减少大约两到四成 token。有 npm 包和 Docker 镜像，站点 9router.com。

- [cockpit-tools](https://github.com/jlcodes99/cockpit-tools) · ⭐ 18,618

  通用 AI IDE 账号管理桌面工具。支持 Antigravity、Codex、GitHub Copilot、Windsurf、Kiro、Cursor、Gemini CLI、Grok CLI、CodeBuddy、Qoder、Trae、Zed、ZCode 等，功能包括多账号切换、配额监控、自动唤醒和应用多开。有中文 README。它管理的是本机已登录的账号，不是模型本身。

- [cc-gateway](https://github.com/motiful/cc-gateway) · ⭐ 3,057

  放在 Claude Code 和上游 API 之间的反向代理。项目把设备标识、环境指纹和进程指标收成一份固定画像，并去掉部分计费相关请求头，从而控制上报内容、让多台机器对外呈现同一身份。作者标明处于 Alpha，并建议先用非主账号。这里只记录定位，不写配置步骤。

- [gemini-mcp-tool](https://github.com/jamubc/gemini-mcp-tool) · ⭐ 2,286

  MCP 服务，让别的 AI 助手调用本机的 Gemini CLI，借 Gemini 的长上下文读大文件和整库。npm 包同名，文档在 jamubc.github.io/gemini-mcp-tool。典型用法是 Claude Code 或 Cursor 遇到超长代码时，把分析转给 Gemini，而不是把整个仓库塞进当前窗口。

- [gemini-cli-openai](https://github.com/GewoonJaap/gemini-cli-openai) · ⭐ 895

  Cloudflare Workers 上的适配层：用 Gemini CLI 那套 OAuth，把 Gemini 暴露成 OpenAI 兼容接口，从而不用单独的 Gemini API key。支持官方 OpenAI SDK、图像理解和工具调用。请求跑在 Worker 上，登录态来自 Google 账号。

- [free-ai-coding](https://github.com/inmve/free-ai-coding) · ⭐ 772

  汇总 Codex、Claude Code、Grok 等编程订阅的额度重置和额外用量，并附原始来源。可以只订阅某一个工具的重置通知仓库，或关注本仓库的 Release。它是公告和链接集，不是代理，也不提供账号。

- [gemini-cli-proxy](https://github.com/nettee/gemini-cli-proxy) · ⭐ 153

  用 Python 把本机 Gemini CLI 包成 OpenAI 兼容的 `/v1/chat/completions`，可用 `uvx` 零配置启动，基于 FastAPI。默认端口 8765。和上面的 Workers 版本相比，这个代理跑在你自己的机器上，Gemini CLI 需要先登录过。有中文 README。

- [CodingPlanQuota](https://github.com/MeIotCOM/CodingPlanQuota) · ⭐ 109

  用 uni-app x 做的手机应用，查看智谱 GLM、Kimi、MiniMax、ZenMux、OpenCode Go、火山方舟、DeepSeek 以及自定义中转的 5 小时、每周、每月编程套餐余量和重置倒计时。无后端，密钥不出设备。支持 Android、iOS 和 HarmonyOS NEXT。作者说桌面端继续用 cc-switch，这个应用补的是手机上的额度查看。

##### 沙箱与执行环境

让 Agent 生成的代码在隔离环境里跑，而不是直接打在开发机上。

- [daytona](https://github.com/daytonaio/daytona) · ⭐ 71,670

  跑 AI 生成代码的弹性基础设施，强调隔离和弹性伸缩。README 写明：2026 年 6 月起核心开发已转到私有代码库，这个公开仓库不再更新，但仍可按原许可证使用和分叉。后续官方资源在 github.com/daytona。Star 数仍高，是因为历史积累，不代表公开仓库还在发版。

- [vibesdk](https://github.com/cloudflare/vibesdk) · ⭐ 5,397

  Cloudflare 开源的氛围编程平台，用来搭你自己的「描述需求即可生成并部署全栈应用」的站点。Agent 循环跑在 Cloudflare 上，Durable Object 提供隔离工作区，预览、看错误和继续改都在同一条链路里。在线演示是 build.cloudflare.dev。适合要自建一个 Lovable 一类产品、并且愿意绑在 Cloudflare 技术栈上的团队。

- [code-interpreter](https://github.com/e2b-dev/code-interpreter) · ⭐ 2,419

  E2B 的代码解释器 SDK。在云端隔离沙箱里执行 AI 生成的 Python 或 JavaScript。JS 和 Python SDK 源码已迁到 `e2b-dev/E2B` 的 `packages/code-interpreter-*`，本仓库留下沙箱模板和图表数据提取。适合在自己的 AI 应用里安全地跑模型写出的代码。

- [vibekit](https://github.com/superagent-ai/vibekit) · ⭐ 1,861

  编程 Agent 的安全层。Claude Code、Gemini、Codex 或其他 Agent 跑在干净的隔离沙箱里，并带敏感信息脱敏和可观测性。CLI 是 `vibekit`，本地用 Docker 把 Agent 产物隔开，避免直接改宿主机。站点 vibekit.sh。

- [coding-agent-template](https://github.com/vercel-labs/coding-agent-template) · ⭐ 1,792

  Vercel 的多 Agent 编程平台模板。用 Vercel Sandbox 和 AI Gateway，在仓库上自动执行 Claude Code、Codex CLI、Copilot CLI、Cursor CLI、Gemini CLI 或 OpenCode 的任务。可以一键克隆到自己的 Vercel 项目。适合已经在 Vercel 上、想给每个任务一个一次性沙箱的产品。

##### 垂直应用

不是通用编程助手，但用大模型解决一类开发或增长问题。

- [SQLBot](https://github.com/dataease/SQLBot) · ⭐ 6,867

  DataEase 团队做的智能问数系统。配置大模型和数据源后，用对话生成 SQL 和图表，再继续做分析，技术路线是 LLM 加 RAG。工作空间隔离和细粒度数据权限用来把库表访问收在边界内。可以嵌进网页、弹窗，或通过 MCP 接到 n8n、Dify、MaxKB、DataEase。支持术语库、SQL 示例和自定义提示词，让问数随使用变准。Docker 一条命令可起服务。

- [Mentha](https://github.com/beenruuu/Mentha) · ⭐ 22

  开源的答案引擎优化（AEO / GEO）平台，不负责传统 SEO 文章。它用真实浏览器自动化记录 ChatGPT、Claude、Perplexity、Gemini 如何谈论一个品牌，再用 LLM-as-Judge 打分，从而衡量和调整品牌在对话式 AI 里的说法。技术栈包括 Next.js 和 Hono。

##### 教程与模板

用来学怎么做 Agent，或给新项目一套现成上下文。

- [how-to-build-a-coding-agent](https://github.com/ghuntley/how-to-build-a-coding-agent) · ⭐ 5,859

  手把手workshop：从调用 Claude API 的聊天机器人开始，逐步加上读文件、改代码、跑命令和搜索，最后得到一个自己的编程 Agent。不要求预先懂 Agent 框架。讲解文章在 ghuntley.com/agent。适合想知道 Cursor、Roo、OpenCode 里面那一层循环到底是什么的人。

- [aicodeguide](https://github.com/automata/aicodeguide) · ⭐ 2,733

  Vilson Vieira 和 Eric S. Raymond 写的 AI 编程路线图，把分散的模型、编辑器、氛围编程实践、MCP 等协议收成一份可以跟着走的说明。仓库定位是地图，不是工具。适合刚开始系统使用 AI 写代码、需要一份总览而不是又一个 CLI 的人。

- [claude-init](https://github.com/cfrs2005/claude-init) · ⭐ 1,359

  2025 年 7 月的 Claude Code 项目初始化模板，面向中文开发者，打包了中文化体验、MCP、上下文管理和安全扫描。作者已归档，并强调它不是 Claude 汉化包，只作学习参考，因为 Claude Code 本身迭代很快。不要把它当成还在跟进官方版本的安装器。

- [claude-code-design-guide](https://github.com/6551Team/claude-code-design-guide) · ⭐ 879

  写给开发者的 Claude Code 设计解析，从早期互联网里的设计模式讲到 AI Agent 怎么落地。内容覆盖工具调用、上下文工程、多 Agent、权限和扩展，目标是看懂一个 Agent 运行时怎么搭，而不是只学几条斜杠命令。中文为主，并有英文和韩文 README。读者从初学者到要自己做 Agent 系统的人都包括。

- [microwind](https://github.com/microwind) · ⭐ 288（组织内最高）

  这是一个 GitHub 组织，不是单个仓库，所以没有组织级 Star。它是 AI 编程知识库：设计模式、算法、提示词和 skills，并用多种语言写示例。统计日几个主要仓库是 [design-patterns](https://github.com/microwind/design-patterns) ⭐ 288、[algorithms](https://github.com/microwind/algorithms) ⭐ 178、[ai-skills](https://github.com/microwind/ai-skills) ⭐ 83、[ai-prompt](https://github.com/microwind/ai-prompt) ⭐ 57。排序按其中最高的 288。

- [vibe-coding-template](https://github.com/humanstack/vibe-coding-template) · ⭐ 250

  全栈氛围编程模板：Next.js 前端、Python FastAPI，再用 Supabase。把常见脚手架先放好，并附上 Cursor 规则和 Agent 说明，让模型少把 token 花在样板代码上。适合新项目想直接进入业务功能、又不想从空仓库开始的人。

- [ai-coding-lab](https://github.com/luzhenqian/ai-coding-lab) · ⭐ 151

  中文实战教程，从氛围编程做到 Agent 和 RAG。每个项目从零到可上线，用 AI 协作完成，而不是先讲语法。编程方向包括个人主页、博客、评论和看板；另一方向是 AI 应用开发。有英文 README。适合想靠做小项目学会跟 AI 配合的人。

- [vibe-coding-template](https://github.com/pea3nut/vibe-coding-template) · ⭐ 2

  另一个同名模板，作者说明只有「Vibe Coding 模板」这一句，仓库几乎没有展开的 README。和 humanstack 那份不是同一个项目。如果要一套能直接用的全栈脚手架，优先看 Star 更高的那份。

##### 资源清单

导航和资料汇编，本身通常不提供可运行的 Agent。

- [system-prompts-and-models-of-ai-tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) · ⭐ 144,014

  汇总各类 AI 产品的系统提示词、内部工具说明和模型资料，名单包括 Augment、Claude Code、Cursor、Devin、Kiro、Lovable、Manus、Perplexity、Replit、Trae、v0、Windsurf、VS Code Agent 等。仓库同时警告：泄露的提示词和模型材料会成为攻击面。适合研究这些工具怎么写系统提示，不适合把里面的内容当成自己的生产配置直接上线。

- [awesome-vibe-coding](https://github.com/filipecalegario/awesome-vibe-coding) · ⭐ 5,303

  氛围编程资料表，有中文版。分类包括浏览器工具、IDE、手机应用、插件、本地应用、命令行、AI 编程的任务管理和文档、社区与招聘。适合查「现在有哪些工具」，而不是学某一个工具的内部实现。

- [awesome-autoresearch](https://github.com/webfuse-com/awesome-autoresearch) · ⭐ 2,553

  原名单中的 `alvinreal/awesome-autoresearch`。围绕 Karpathy 的 autoresearch，收录自主改进循环、研究 Agent，以及通用衍生、研究系统、硬件移植、领域适配、评测和写得比较实的使用记录。适合在找「让实验自己跑起来」的项目时当索引。

- [awesome-ai-coding-tools](https://github.com/ai-for-developers/awesome-ai-coding-tools) · ⭐ 2,129

  AI 编程工具目录，按编辑器、Agent、补全、审查、测试等分类。面向开发者和团队，接受 PR 补充。和下面 Sourcegraph 那份相比，这份还在更新，分类也更接近 2026 年的工具形态。

- [awesome-code-ai](https://github.com/sourcegraph/awesome-code-ai) · ⭐ 1,694

  Sourcegraph 维护过的 AI 编程工具列表，覆盖助手、补全和重构。仓库已经归档，里面的产品名有不少已过时，例如早期的 Codeium、Fauxpilot。留作历史索引，新工具优先看还在更新的清单。

- [system-prompts-and-models-of-ai-tools-chinese](https://github.com/IsHexx/system-prompts-and-models-of-ai-tools-chinese) · ⭐ 1,241

  上一份系统提示词仓库的中文译本，面向想用中文阅读 Cursor、Devin、VS Code Agent、Windsurf、Lovable、Manus、v0 等工具提示词的人。作者声明仅供学习，理解这些助手如何被指示工作，并持续补充中文编程规则。

- [awesome-ai-coding](https://github.com/wsxiaoys/awesome-ai-coding) · ⭐ 765

  另一份 AI 编程主题列表，条目包括 BigCode、Fauxpilot、Neovim 里的 CodeGPT，以及把 markdown 提示栈编译成代码的 Vibe Compiler。更新频率和覆盖面都小于前面的工具大全，更像早期项目备忘。

- [awesome-vibe-coding-guide](https://github.com/analyticalrohit/awesome-vibe-coding-guide) · ⭐ 380

  氛围编程的实践说明，目标是在 Cursor、Windsurf、Lovable 一类工具里保持可控：发挥模型速度，同时用清楚的指示避免一次性改坏项目。内容来自作者自己的使用经验，是指南而不是工具目录。

- [Awesome-Vibe-Coding](https://github.com/YuyaoGe/Awesome-Vibe-Coding) · ⭐ 122

  一篇综述型仓库：作者说梳理了 1000 多篇论文，把氛围编程从代码模型、编程 Agent、开发环境到反馈机制串起来。它更接近文献地图，不是手把手教程，也不是软件工具列表。

#### 工具
- [cursor-auto-free](https://github.com/chengazhen/cursor-auto-free)

#### 文章
- [OpenSpec 完整使用流程笔记 （SDD)](https://juejin.cn/post/7615455795724648483)
- [7个神级技巧，彻底去除网站的 AI 味儿！](https://juejin.cn/post/7600967006892490761)
- [2026年新国内如何注册 Claude 账号保姆教程（成功率95%）](https://juejin.cn/post/7616281002122641408)
- [创业半年，我用5个AI Agent替代了一个团队](https://juejin.cn/post/7606728595557400611)
- [stagewise | 前端开发效率神器](https://juejin.cn/post/7516362698278109222)
- [OpenCode：你的开源 AI 编程助手完全指南](https://juejin.cn/post/7593607642552811546)
- [拒绝成为落后的开发者：用TRAE Skills构建你的10倍效能工具箱](https://juejin.cn/post/7597724783649685544)
- [AI + 可视化：Stagewise 如何让前端 UI 调试效率飞跃](https://juejin.cn/post/7535661303408050210)
- [DeepSite：基于DeepSeek的开源AI前端开发神器，一键生成游戏/网页代码](https://juejin.cn/post/7488906984072577024)
- [怕 AI 乱改代码？教你用 Hooks 给 Claude Code 戴上"紧箍咒"](https://juejin.cn/post/7592062873829867570)
- [AI提效这么多，为什么不试试自己开发N个产品呢？](https://juejin.cn/post/7569108298952769545)
- [9 个 超绝的 AI 控制电脑 GitHub 开源项目](https://juejin.cn/post/7586680977854906431)
- [AI Coding技巧与心得](https://juejin.cn/post/7551997631113199626)
- [Claude Code Review：让AI审核更懂你的代码](https://juejin.cn/post/7559009457171857450)
- [Antigravity：下一代 AI 编程助手完全指南](https://juejin.cn/post/7581423932612984872)
- [工作中的Ai工具汇总](https://juejin.cn/post/7561280655223570478)
- [Ultracite：为 AI 时代打造的零配置代码规范工具](https://juejin.cn/post/7575090551356686388)
- [iFlow CLI：强大的终端AI助手，开启智能编程新时代](https://juejin.cn/post/7574581079627317254)
- [“最新国产代码大杀器”——MiniMax-M2！](https://juejin.cn/post/7568192652287868982)
- [AGENTS.md](https://juejin.cn/post/7569532841870540826)
- [AI Coding技巧与心得](https://juejin.cn/post/7551997631113199626)
- [完整的AI编程全自动指南](https://juejin.cn/post/7567196232107196459)
- [🚀 程序员必看让AI编程100%可控！从1到N的开发神器OpenSpec规范驱动开发完整实战指南！支持Cursor、Claude Code、Codex！](https://juejin.cn/post/7562005346262646835)
- [🎨 市面上主流 Figma to Code MCP 对比](https://juejin.cn/post/7540470626210938906)
- [AI 代码审核](https://juejin.cn/post/7504567245265846272)
- [AI - Gemini CLI 摆脱终端限制](https://juejin.cn/post/7531685572214996992)
