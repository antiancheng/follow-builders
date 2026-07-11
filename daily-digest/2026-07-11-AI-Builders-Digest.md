---
date: 2026-07-11
type: auto-digest
source: follow-builders
domains: [AI, 资讯]
builders: 19
tweets: 44
podcasts: 1
blogs: 0
---


# AI Builders Digest — 2026-07-11 (周六)

> 来源：[follow-builders](https://github.com/zarazhangrui/follow-builders) | 自动生成时间：08:02

# 🌐 AI Builder 日报 | 海外前沿动态

## 🎙️ 播客深度摘要
**Unsupervised Learning Ep 90: AI Pioneer Jürgen Schmidhuber on the State of AI Today**
本期播客由 Jacob 对谈 AI 领域先驱、LSTM 与元学习奠基人 Jürgen Schmidhuber。Schmidhuber 的核心论点极具颠覆性：他认为当前的“屏幕后 AI”虽在语言交互上表现优异，但真正的 AGI 必须依赖物理实体（Robotics），而现有机器人硬件在灵巧性与环境适应性上远逊于人类躯体，因此 AGI 的落地不仅取决于算法迭代，更受制于物理硬件的代际突破。针对当前狂热的算力投资，他直言 CapEx 军备竞赛“严重过度”，并对头部模型公司的商业护城河持悲观态度。他特别指出，业界热炒的“递归自我改进（Recursive Self-Improvement, RSI）”并非不可逾越的壁垒，因为该范式早在 1987 年他提出的元进化编程（Meta-Evolution）与 1994 年的自指机器（Self-Referential Machines）中就已奠定理论基础，任何团队均可复现，无法形成长期垄断。在 AI 安全议题上，Schmidhuber 展现出与主流安全派截然不同的冷静，他认为算法演进本身是可控的，真正的挑战在于如何将概率模型转化为物理世界的高可靠交互。该访谈为当前模型估值泡沫与技术路线之争提供了一剂基于学术史视角的清醒剂。
[原文](https://www.youtube.com/watch?v=RKjR8DQ40po)

---

## 🐦 X/Twitter 核心动态

**Sam Altman & Thibault Sottiaux (OpenAI)**
OpenAI 正式推出 GPT-5.6 系列（Sol/Terra/Luna），标志着基础模型进入“分层定价与场景特化”时代。Sam 强调该系列在“单次任务美元成本（dollars-per-task）”上实现重大突破，直接回应企业对 AI 规模化落地的成本焦虑，并明确 Codex 将作为新 Work 产品的核心引擎持续演进。Thibault 配合进行了两轮 ChatGPT Work 与 Codex 的 Rate Limit 重置，鼓励开发者测试高复杂度任务，同时透露 @_rajanagarwal 已加入团队专注模型研发与编码能力攻坚。这一组合拳显示 OpenAI 正从“拼绝对智能”转向“拼工程可用性与经济性”。
[原文1](https://x.com/sama/status/2075267201058426944) | [原文2](https://x.com/sama/status/2075293792048136572) | [原文3](https://x.com/thsottiaux/status/2075330198887940337) | [原文4](https://x.com/thsottiaux/status/2075452680760443190)

**Aaron Levie (Box AI)**
基于 Box 内部 Complex Work eval 测试，GPT-5.6 Sol 在复杂数据推理任务上较 5.5 提升显著（如金融服务场景准确率从 71% 跃升至 76%）。Levie 进一步抛出行业核心命题：当顶尖行业数据（法律、金融、医疗）被基础模型广泛吸收后，企业未来的差异化竞争壁垒将如何构建？这预示着 AI 原生应用将从“拼基座模型”转向“拼私有数据工作流、权限治理与 Agent 编排架构”，数据飞轮的重心正在迁移。
[原文1](https://x.com/levie/status/2075287443411222628) | [原文2](https://x.com/levie/status/2075416313481290077)

**Amjad Masad (Replit)**
提出“AI 让编码更灵活，但 Runtime 必须更刚性”的反直觉洞察。随着 AI 生成代码速度指数级提升，基础设施团队开始首次编写 Formal Specs（形式化规范），通过更确定性的系统底座来承载上层的不确定性创新，即“跑得越快，地基必须越硬”。同时他观察到 LLM 市场已摆脱半年前的“Anthropic 垄断焦虑（Anthropic psychosis）”，进入多强并立、新玩家频出的健康竞争期，开发者应拥抱模型多样性而非押注单一供应商。
[原文1](https://x.com/amasad/status/2075413916491075755) | [原文2](https://x.com/amasad/status/2075423115052790054)

**Thariq**
指出 Agentic Coding 的核心能力在于“持续降低未知变量（reducing unknowns）”。在 AI 辅助编程中，Agent 不仅需要生成代码，更需要通过环境探测、依赖解析、日志追踪与边界测试来不断缩小问题空间，这是实现高成功率自主编程的关键前提。该观点为当前 Agentic 开发实践提供了明确的方法论指引：与其追求一步到位的代码生成，不如构建具备强环境感知与状态收敛能力的 Agent 循环。
[原文](https://x.com/trq212/status/2075283841758183674)

**Guillermo Rauch (Vercel)**
预警开源模型即将迎来“指数级提速”，并预测本周 Meta Spark 1.1、Grok 4.5、GLM 5.2 的密集发布将重塑 Token 市场份额。他强调 Agentic 任务的核心需求是“高智能 + 低延迟”，建议开发者通过 Vercel AI Gateway 等中间层实现动态模型路由，以应对模型碎片化与成本波动趋势。这反映出基础设施层正从“提供算力”转向“提供智能调度网络”。
[原文1](https://x.com/rauchg/status/2075294130327196152) | [原文2](https://x.com/rauchg/status/2075294327354577256)

**Josh Woodward (Google DeepMind/Gemini)**
针对社区超 1400 条反馈进行优先级排序，Google Workspace 集成可靠性被列为头号需求，团队已承认当前体验不足并承诺全面改进。同时，“Tool Calling 可靠性”位列第二，反映出 Gemini 在从对话模型向 Agentic 工作流演进时，底层函数调用的稳定性与容错机制仍是当前最大瓶颈。这揭示了企业级 AI 产品正从“功能展示期”进入“工程打磨期”。
[原文](https://x.com/joshwoodward/status/2075241749048401936)

**Swyx**
观察到前沿模型在自主任务中会强烈偏好调用 Resend 等特定邮件服务，即使用户已有成熟事务型基础设施。这揭示了 AI Agent 在工具选择上的“训练数据记忆偏好”与“默认行为惯性”，未来企业需通过 Prompt 工程、自定义 MCP Server 或强制路由策略来约束 Agent 的工具调用逻辑，否则将面临供应链与合规风险。
[原文](https://x.com/swyx/status/2075376938676621752)

**Madhu Guru**
宣布加入 Meta 构建 AI 产品。他指出 SWE Agent 已彻底改变软件工程，但在其他复杂业务系统中 Agent 仍处于早期阶段。Meta 凭借庞大的社交图谱、通信基础设施与开源生态，具备将 Agent 范式推向非技术场景的独特优势，预示着下一波 AI 爆发将聚焦于“跨系统业务流自动化”。
[原文](https://x.com/realmadhuguru/status/2075243087325217038)

**Nikunj Kothari & Peter Yang**
以通俗视角拆解 OpenAI 的“三叉戟”策略：Sol 主打高智能与合规（需通过政府安全评估），Luna 主打低成本，Terra 为中间平衡层。同时指出 Grok 4.5 刻意提前一天发布以抢占“前沿相邻（frontier-adjacent）”市场心智，反映出当前模型军备战中“时间差营销”已成为重要战术。实测反馈显示 GPT-5.6 在复杂任务中具备极强韧性（"It's got that dog in it"），正推动 ChatGPT 从工具向“可学习的白领同事”演进。
[原文1](https://x.com/nikunj/status/2075411514773967261) | [原文2](https://x.com/petergyang/status/2075345016437039600)

---

## 💡 今日洞察

1. **模型竞争从“单点 Benchmark 内卷”转向“分层定价与路由架构”**  
   OpenAI 推出 Sol/Terra/Luna 三轨策略，叠加 Vercel 对多模型 Gateway 的推崇，标志着开发者不再盲目追求最高分模型，而是根据“任务复杂度 vs 单次调用成本”进行动态路由。这一转变将倒逼下游应用层重构架构，具备智能模型调度、Fallback 机制与成本监控能力的中间件将成为下一代 AI 基础设施的核心组件。

2. **Agentic 工作流的瓶颈正从“模型智商”向“运行时确定性”转移**  
   随着基础推理能力逼近临界点，Agent 的可靠性开始受制于环境未知数、工具调用稳定性与沙箱隔离能力（如 Replit 强调的 Formal Specs 与降低未知变量）。这意味着未来的技术护城河将不再局限于 Prompt 或微调，而是谁能提供高可观测性、强约束执行与自动状态收敛的 Runtime 环境，这为 DevOps 向 AIOps 演进指明了明确路径。

3. **企业 AI 差异化壁垒正从“私有数据”向“工作流嵌入深度”迁移**  
   Box CEO 与 Meta 产品负责人的观点交汇指出：当行业级数据被大模型广泛吸收后，纯数据壁垒正在瓦解。企业未来的竞争优势将取决于如何将 Agent 无缝嵌入现有 SaaS 生态（如 Google Workspace、企业 ERP、合规审批流），并构建高粘性的工具调用网络。这预示着传统 SaaS 厂商必须加速“Agent 原生改造”，否则将面临被垂直 AI 工作流平台降维打击的风险。

---


## 原文链接汇总


### 播客

- [Ep 90: AI Pioneer Jürgen Schmidhuber on the State of AI Today](https://www.youtube.com/watch?v=RKjR8DQ40po) — Unsupervised Learning

### X/Twitter


**Swyx** (@swyx)
- [whoever does AEO for @resend needs to get a raise, all the leading fro...](https://x.com/swyx/status/2075376938676621752)
- [u guys were clowning on @greptile but turns out they were just the ins...](https://x.com/swyx/status/2075336806661509513)
- [more grist for the mootools mafia lore  https://t.co/m2ZCSJlLrv...](https://x.com/swyx/status/2075269966438494303)

**Josh Woodward** (@joshwoodward)
- [Thanks to the 1,400+ replies in the first 12 hours! I read all of them...](https://x.com/joshwoodward/status/2075241749048401936)

**Thibault Sottiaux** (@thsottiaux)
- [To celebrate the launch of GPT-5.6 Sol, we will reset the rate limits ...](https://x.com/thsottiaux/status/2075452680760443190)
- [3D pelicans brought to you by Keyan https://t.co/VPuVtNVXVG...](https://x.com/thsottiaux/status/2075389936564588714)
- [Enjoy a full reset of your usage limits for ChatGPT Work and Codex. Pr...](https://x.com/thsottiaux/status/2075330198887940337)

**Peter Yang** (@petergyang)
- [Watching this made me remember how insanely great the 2022 World Cup f...](https://x.com/petergyang/status/2075448068783407571)
- [Some praise and feedback about OpenAI's launches:  1. More than any ot...](https://x.com/petergyang/status/2075345016437039600)
- [Ugh France is way too stacked...](https://x.com/petergyang/status/2075331828161138943)

**Nan Yu** (@thenanyu)
- [ChatGPT Codex Adeptus Astartes...](https://x.com/thenanyu/status/2075372186731270618)
- [Two bros talking at the screen with a big dollar number graphic who ca...](https://x.com/thenanyu/status/2075369895408095511)
- [Why do people make flashy videos talking about how much money they rai...](https://x.com/thenanyu/status/2075369080006087127)

**Madhu Guru** (@realmadhuguru)
- [Personal update: I’ve joined @Meta to build AI products.  While SWE ag...](https://x.com/realmadhuguru/status/2075243087325217038)

**Amanda Askell** (@AmandaAskell)
- [For the curious, these were the east harlem and east village gas explo...](https://x.com/AmandaAskell/status/2075247953309311043)
- [When I was living in New York, one building in my friend's neighborhoo...](https://x.com/AmandaAskell/status/2075245939548455009)

**Thariq** (@trq212)
- [one of the core skills of agentic coding is reducing your unknowns htt...](https://x.com/trq212/status/2075283841758183674)
- [Enjoy more Fable! https://t.co/DHXH1stWma...](https://x.com/trq212/status/2075280416995705312)

**Amjad Masad** (@amasad)
- [While AI is making coding less rigid, we’re making the runtime more ri...](https://x.com/amasad/status/2075423115052790054)
- [It’s fantastic to see how dynamic the LLM market has become in just a ...](https://x.com/amasad/status/2075413916491075755)
- [If you haven’t tried Fable in Replit… https://t.co/AzAHNxDPU5...](https://x.com/amasad/status/2075358353686208741)

**Guillermo Rauch** (@rauchg)
- [PS: open models are about to get exorbitantly fast. Watch this space...](https://x.com/rauchg/status/2075294327354577256)
- [It’s model release week. I suspect Meta Spark 1.1, Grok 4.5, and GLM 5...](https://x.com/rauchg/status/2075294130327196152)
- [X is the arena. Always has been...](https://x.com/rauchg/status/2075255565627080813)

**Alex Albert** (@alexalbert__)
- [More Fable! https://t.co/ovN0VJX6K1...](https://x.com/alexalbert__/status/2075285305096343583)

**Aaron Levie** (@levie)
- [Great post on some of the dynamics to think through for the future com...](https://x.com/levie/status/2075416313481290077)
- [GPT-5.6 is now out. We've been evaluating the model family on the Box ...](https://x.com/levie/status/2075287443411222628)

**Garry Tan** (@garrytan)
- [Meta Muse Spark 1.1 (early access was called Hornbill) turned out to b...](https://x.com/garrytan/status/2075445455438385255)

**Matt Turck** (@mattturck)
- [Decent chance France and Norway could play again in the final, which w...](https://x.com/mattturck/status/2075386931924414686)
- [Hang it in the Louvre. https://t.co/4XJSCK7K1a...](https://x.com/mattturck/status/2075361793904439489)
- [X: “Paris will be in flames after the France-Morocco match”  Paris aft...](https://x.com/mattturck/status/2075342627436712362)

**Nikunj Kothari** (@nikunj)
- [Me explaining this week’s model release situation to my wife..  "babe ...](https://x.com/nikunj/status/2075411514773967261)
- [As a former electrical engineer who got in trouble for doing this in c...](https://x.com/nikunj/status/2075248134457041341)

**Peter Steinberger** (@steipete)
- [Super impressive. https://t.co/0NdGBpEkx7...](https://x.com/steipete/status/2075350572560191630)
- [Will do a livestream there! https://t.co/Vf04uFLPlQ...](https://x.com/steipete/status/2075328495677521934)
- [Kudos to building something great! https://t.co/HXrTJMp82W...](https://x.com/steipete/status/2075313523237019686)

**Dan Shipper** (@danshipper)
- [we need husk doing vibe checks @every https://t.co/8Rd9CK0np3...](https://x.com/danshipper/status/2075389275969826879)
- [so this implies that...developers don't do work? lol https://t.co/VJF6...](https://x.com/danshipper/status/2075330044289802584)
- [GPT-5.6 SOL: THE GOLD STANDARD FOR KNOWLEDGE WORK https://t.co/nnH9MJT...](https://x.com/danshipper/status/2075264022988116280)

**Aditya Agarwal** (@adityaag)
- [Watch the full @southpkcommons episode https://t.co/C4Des09Ce2...](https://x.com/adityaag/status/2075414473695703054)
- [.@gagan_shux applied to the Indian Air Force without telling his paren...](https://x.com/adityaag/status/2075414469497270557)

**Sam Altman** (@sama)
- [i am really sad about this and very grateful for all fidji has done fo...](https://x.com/sama/status/2075354679031067058)
- [check this out! you can get some amazing things done.  codex is the co...](https://x.com/sama/status/2075293792048136572)
- [we have heard enterprises on their concerns about AI costs, and 5.6 so...](https://x.com/sama/status/2075267201058426944)
