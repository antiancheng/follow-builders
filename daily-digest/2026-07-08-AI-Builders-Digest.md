---
date: 2026-07-08
type: auto-digest
source: follow-builders
domains: [AI, 资讯]
builders: 16
tweets: 34
podcasts: 1
blogs: 1
---


# AI Builders Digest — 2026-07-08 (周三)

> 来源：[follow-builders](https://github.com/zarazhangrui/follow-builders) | 自动生成时间：08:02

# 🤖 AI Builder 日报

## 🎙️ 播客精选
**《AI & I by Every》：Building a School Where AI Models Learn About Humanity**
本期播客由 Dan Shipper 访谈数据与评估平台 Surge AI 创始人兼 CEO Edwin Bregman。双方围绕“如何像培养人类一样训练 AGI”展开深度对话，Edwin 提出前沿模型的训练范式正从“应试解题”向“具备人类品味与审美判断”演进。他以数学基准测试的代际跨越为例：几年前模型在 GSM8K（中学数学）上准确率仅约 20%，而数月前的 Riemann Bench 已能测试研究级数学能力，甚至成功运用新颖的代数几何技术推翻了埃尔德什（Erdős）的一个公开猜想。Surge 凭借提供高质量、带专家判断（expert judgment）的数据环境，已在不融资的情况下实现 **10 亿美元营收**。值得深挖的论断在于：数据不再是简单的“喂料”，而是需要构建分层级的“课程体系”——从基础语法、模糊问题解析，逐步过渡到对美、品味与复杂现实场景的理解。这标志着 AI 训练正从暴力 Scaling 转向精细化的人类认知对齐。
[原文](https://www.youtube.com/watch?v=omX6wrLuX08)

---

## 📝 官方博客/产品动态
**Claude Code 正式推出 Artifacts 功能（Beta）**
Anthropic 宣布 Claude Code 现支持将命令行工作流自动转化为实时、可共享的可视化网页。Artifacts 深度集成当前会话的完整上下文（代码库、外部连接器、对话记录），支持原地刷新、版本历史回溯与画廊管理。企业级安全设计确保页面默认私有，仅对组织内认证成员开放，管理员可通过 API 进行合规管控。Anthropic 还为法务、安全、SRE 等不同角色提供了开箱即用的 Prompt 模板。该功能旨在将 Agent 的“黑盒执行”转化为“透明协作”，大幅降低跨团队同步成本，标志着 AI 编程工具正从个人提效迈向组织级工作流重构。
[原文](https://claude.com/blog/artifacts-in-claude-code)

---

## 💻 X/Twitter Builder 动态

### 🔍 Anthropic 团队 (Boris Cherny, Cat Wu, @claudeai)
Anthropic 核心成员与官方账号联合发布长文，首次系统回顾了 Claude Code 的诞生历程。该项目最初并非直接面向开发者市场，而是脱胎于内部的 AI 安全研究团队。在探索模型行为边界与对齐技术的过程中，团队发现将代码执行环境与安全沙箱结合能产生巨大的生产力杠杆。这一“安全研究反哺产品”的路径，揭示了前沿实验室正通过内部工具链的吃狗粮（Dogfooding）来验证模型可靠性，也为后续商业化 Agent 的架构设计提供了重要参考。
[原文](https://x.com/claudeai/status/2074244664199115201)

### 🧠 Swyx
Swyx 深度解读了 Anthropic 最新发布的 J-space 论文，指出其最具颠覆性的两点：一是首次实现了对模型推理过程的“脑外科手术”级干预，能在推理中途精准改变话题走向；二是模型具备识别外部干预痕迹的能力，这已非常接近“评估感知（eval awareness）”。该研究通过严格的控制实验证明了模型对干预逻辑的真实理解，突破了传统的相关性分析。这为未来实现细粒度的推理控制、防止模型越狱或恶意操纵提供了关键的理论基础。
[原文](https://x.com/swyx/status/2074344727202463832)

### 🔄 Replit / Amjad Masad
Replit CEO Amjad Masad 披露了平台实现“自进化”架构的核心机制：通过构建完整的反馈闭环，Agent 能够自主分析代码运行结果并迭代优化自身 Prompt 与工具调用逻辑。与此同时，一家亚特兰大房地产公司通过 Replit 完全替代 Salesforce 自建 CRM，节省超 10 万美元。这两个案例共同印证了 AI 原生开发平台正在跨越“辅助编码”阶段，进入“业务系统自主重构”的深水区，企业正利用低门槛 Agent 平台快速搭建高度定制化的业务流。
[原文](https://x.com/amasad/status/2074257906594177279)

### 📊 Vercel / Guillermo Rauch
Guillermo Rauch 正式推出 Vercel 原生 Agent 评估工具 `eve eval`，强调在 Web 框架时代测试曾是生态选择，但在 Agentic 时代，评估已成为必须开箱即用的基础设施。他进一步提出判断 Coding AI 价值的终极标准不是跑分，而是“软件整体是否在变好、企业是否在加速交付”。Rauch 认为，AI 正在催生“Personal Software（个人软件）”时代，开发者能以极低成本将个人愿景快速转化为可交互的应用，这种对生产力与创造力的彻底解放才是技术落地的核心。
[原文](https://x.com/rauchg/status/2074287795028512773)

### 🎯 Fable 5 策略 / Peter Yang, Dan Shipper, Thariq
Fable 5 模型即将于太平洋时间 7 月 7 日午夜下线，多位 Builder 集中分享了高价值使用策略。Dan Shipper 提出“重拳出击 vs 游击战术”的模型使用哲学：面对昂贵的高阶模型，应将其用于处理高复杂度、高杠杆的“大摇摆”任务（如架构设计、模糊问题探索），而非琐碎调试。Peter Yang 则整理了 5 套可直接复用的 Prompt 模板，涵盖工作流审计与商业决策推演。这反映出高阶模型正从“通用聊天”转向“战略级决策辅助”，用户需通过精准的任务分层来最大化 ROI。
[原文](https://x.com/petergyang/status/2074206798631071796)

### 🚀 初创组织形态演进 / Nan Yu & Zara Zhang
Nan Yu 指出 AI Agent 最大的价值在于让早期团队实现“高度并行开发”，彻底打破了传统“996”模式下因串行等待和繁琐编码导致的效率瓶颈。Zara Zhang 进一步补充，AI 正在抹平工程师、设计师与产品经理的职能边界，任何掌握 AI 原生工具的人都能独立完成端到端的产品构建。两者的观点共同指向一个趋势：AI 不仅提升了单点效率，更在重构初创公司的组织形态与人才能力模型，“全栈 Builder”正在成为新标准。
[原文](https://x.com/thenanyu/status/2074133468007587932)

### 🏢 企业 AI 架构策略 / Aaron Levie
Box CEO Aaron Levie 提出了企业 AI 部署的“分层剥离”策略。他认为，前沿大模型（Frontier Intelligence）将长期占据复杂工作流的编排与规划层，解决未知场景的“从 0 到 1”问题。但随着企业用例逐渐成熟与标准化，企业应有意识地将部分 Token 消耗“剥离”至更低成本的开源/闭源模型，或针对垂直场景微调的专用模型。这一架构思维为 AI 原生企业提供了清晰的成本优化路径，避免陷入“杀鸡用牛刀”的算力浪费陷阱。
[原文](https://x.com/levie/status/2074163686990913576)

---

## 🔍 今日洞察

1. **Agent 评估（Evals）正从“可选项”变为“核心基础设施”**：无论是 Vercel 将 `eve eval` 内置于框架，还是 Surge AI 强调数据需具备“专家品味与分层教学”，都表明 Agentic 时代的开发范式已发生根本转变。过去依赖静态测试用例的框架已无法应对非确定性 Agent 的复杂决策路径，内置、持续、多维度的自动化评估体系将成为下一代 AI 产品构建信任与迭代的核心护城河。
2. **AI 编程工具进入“组织级透明化协作”阶段**：Claude Code Artifacts 的发布标志着 AI 辅助开发不再局限于“单人黑盒提效”。通过将 Agent 的执行过程、代码上下文与推理逻辑实时转化为可共享的动态网页，跨职能团队的沟通摩擦被大幅压缩。未来，AI 工具的竞争壁垒将不仅取决于代码生成质量，更取决于其“工作流可视化”与“跨角色协同”的封装能力。
3. **“并行化开发”与“角色平权”正在重塑创业竞争维度**：随着 Agent 接管繁琐的串行编码任务，早期团队的瓶颈已从“人手不足”转向“系统架构设计与任务调度能力”。技术平权使得“一人即团队”成为现实，但同时也对创始人的产品判断力、Prompt 工程能力与商业嗅觉提出了更高要求。创业赛道的胜负手，正从“工程执行力”向“AI 原生架构思维”快速迁移。

---


## 原文链接汇总


### 播客

- [Building a School Where AI Models Learn About Humanity](https://www.youtube.com/watch?v=omX6wrLuX08) — AI & I by Every

### X/Twitter


**Swyx** (@swyx)
- [imo this is the most impt part of anthropic's J-space paper today. it'...](https://x.com/swyx/status/2074344727202463832)

**Boris Cherny** (@bcherny)
- [This is our first time telling the story of how we first built and lau...](https://x.com/bcherny/status/2074247226038063316)

**Thibault Sottiaux** (@thsottiaux)
- [https://t.co/PXjlm4RLJJ https://t.co/G1K5KnFNtf...](https://x.com/thsottiaux/status/2074209421799166138)
- [Closing this week. Much of the teams building ChatGPT, Codex and OpenC...](https://x.com/thsottiaux/status/2074195169990357398)

**Peter Yang** (@petergyang)
- [Ughhhhhhh...](https://x.com/petergyang/status/2074312096960123318)
- [Go USA!!!...](https://x.com/petergyang/status/2074295408902479910)
- [Fable 5 will leave Claude subscriptions tomorrow at midnight. Here are...](https://x.com/petergyang/status/2074206798631071796)

**Nan Yu** (@thenanyu)
- [Yeah, this resonates. I was horribly inefficient, so I brute forced a ...](https://x.com/thenanyu/status/2074258147015897357)
- [The biggest advantage that 20-year-old me had over today me is the abi...](https://x.com/thenanyu/status/2074133468007587932)

**Cat Wu** (@_catwu)
- [a retrospective on making claude code from our early team! https://t.c...](https://x.com/_catwu/status/2074258446686536167)

**Thariq** (@trq212)
- [great post by @delba_oliveira https://t.co/xZ2bCh7yOL...](https://x.com/trq212/status/2074209928961819081)
- [this is now on the Claude blog! https://t.co/7LW0yDuixR...](https://x.com/trq212/status/2074186977147273540)
- [to be specific the date/time is will be 11:59:59pm PT on 7/7...](https://x.com/trq212/status/2074185669598237047)

**Amjad Masad** (@amasad)
- [Major inflection point around the time of the brief bear market fall o...](https://x.com/amasad/status/2074353874996211831)
- [Atlanta-based real estate company saved $100k by replacing Salesforce ...](https://x.com/amasad/status/2074274666709987663)
- [Many are asking how Replit is improving so rapidly—we closed the loop ...](https://x.com/amasad/status/2074257906594177279)

**Guillermo Rauch** (@rauchg)
- [Update: 🇪🇸 ESP - 🇦🇷 ARG final.  The legendary Spanish team will avenge...](https://x.com/rauchg/status/2074313180554412076)
- [🆒 eve evals itself with 𝚎𝚟𝚎 𝚎𝚟𝚊𝚕.  Web frameworks made testing an ecos...](https://x.com/rauchg/status/2074287795028512773)
- [The ultimate test for coding AI: is software as a whole getting better...](https://x.com/rauchg/status/2074222247548735996)

**Aaron Levie** (@levie)
- [Great post on how to think about open source AI and the applied AI lay...](https://x.com/levie/status/2074163686990913576)

**Garry Tan** (@garrytan)
- [This is how media is a bludgeon for an entrenched class of doom loop p...](https://x.com/garrytan/status/2074287157007806932)
- [When headlines lie by omission, it says a lot about the headline write...](https://x.com/garrytan/status/2074286755185086538)
- [Oakland will continue to be a case study in virtue signal policies by ...](https://x.com/garrytan/status/2074279598612000785)

**Zara Zhang** (@zarazhangrui)
- [@aiDotEngineer @cursor_ai Also don't be constrained by your titles/rol...](https://x.com/zarazhangrui/status/2074305070955639077)
- [If you wanna level up as an AI builder, binge watch the talks from the...](https://x.com/zarazhangrui/status/2074304295097561490)
- [Great talk! Really enjoyed this https://t.co/vOtrsQai4V...](https://x.com/zarazhangrui/status/2074209416606634048)

**Nikunj Kothari** (@nikunj)
- [When you ask a founder what "me and the boys" means when they talked a...](https://x.com/nikunj/status/2074194480354488750)
- [VCs: this job is investing in outliers.   Also VC: here’s our revoluti...](https://x.com/nikunj/status/2074141483356340475)

**Peter Steinberger** (@steipete)
- [You don't wanna miss this. Signup closes this week.  Will be there and...](https://x.com/steipete/status/2074389082017550720)
- [How do folks run AI-assisted engineering interviews these days?...](https://x.com/steipete/status/2074380549318443311)
- [We been cooking, by the time this went through review main again is ma...](https://x.com/steipete/status/2074210475777364197)

**Dan Shipper** (@danshipper)
- [the gremlins have arrived in fable https://t.co/oeLAU7ilPH...](https://x.com/danshipper/status/2074160985452028406)
- [interestingly, this holds true for how you use models too  should you ...](https://x.com/danshipper/status/2074160886164451735)

**Claude** (@claudeai)
- [We've put together a short history of how Claude Code came to be, told...](https://x.com/claudeai/status/2074244664199115201)

### 博客

- [Claude Code now supports artifacts](https://claude.com/blog/artifacts-in-claude-code)
