# Oraink Tech Digest

灵砚 Oraink 公开科技互联网日报 / 周报归档。  
汇聚公众号、推特、博客、Newsletter 等渠道的优质博主和一线团队文章，由灵砚整理为每日线索、主题分卷和周度趋势。

## 目录

- [今日日报](#今日日报)
- [往期日报](daily/)
- [周报归档](weekly/)
- [License](#license)

---

## 今日日报

> 本期归档文件：[daily/2026/11/2026-11-20.md](daily/2026/11/2026-11-20.md)

<!-- latest daily content starts -->

# 从Anthropic的IPO到AI挖洞，AI今天同时在被估值与被部署

> Anthropic的IPO动向把AI资本化与估值推到台前；nginx2root的远程代码执行、虚拟化零日漏洞与AI挖洞让安全侧同样密集；Gemini 4 Neon与Copilot则把话题带到模型分发。资本、安全与工具链，今天各有具体进展。

**灵砚日报 · ORAINK DIGEST**  
2026-11-20 · 日报 · Vol. 454

- 今日处理文章：692
- 主精选条目：20
- 预计阅读：7 分钟
- 今日主线：AI估值 / AI挖洞 / 零日漏洞 / 模型分发

## 速览

- [Anthropic顶着联名信上市，首日开盘涨34%](#1-anthropic顶着联名信上市首日开盘涨34)
- [Neon以3美元拿下实测第二，评测者退订Claude](#2-neon以3美元拿下实测第二评测者退订claude)
- [机器人模型拿79分，OpenAI把机器人并进通用模型](#3-机器人模型拿79分openai把机器人并进通用模型)
- [Codex与Claude同日交卷：AI挖洞进入实战](#4-codex与claude同日交卷ai挖洞进入实战)
- [AI揪出nginx十年RCE，千万服务器补丁竞速开场](#1-ai揪出nginx十年rce千万服务器补丁竞速开场)
- [官方包也失守：微软AI框架PyPI遭账号劫持投毒](#2-官方包也失守微软ai框架pypi遭账号劫持投毒)
- [1.8亿下载的模型账号，被一个过期域名轻松接管](#3-18亿下载的模型账号被一个过期域名轻松接管)
- [Vite曝未授权RCE：开发环境正式算进攻击面](#4-vite曝未授权rce开发环境正式算进攻击面)
- [Anthropic 上市后回落 17%，泡沫争论有了价格](#1-anthropic-上市后回落-17泡沫争论有了价格)
- [AMD 被指违禁售华：半小时跌 13%，管制动真格](#2-amd-被指违禁售华半小时跌-13管制动真格)
- [GR00T 2 开源背后，具身智能打响数据粮草战](#3-gr00t-2-开源背后具身智能打响数据粮草战)
- [「谷歌以前很糟」：Gemini 4 半价追平 Opus](#4-谷歌以前很糟gemini-4-半价追平-opus)
- [Copilot 再添谷歌 Neon，货架开始卖对手模型](#1-copilot-再添谷歌-neon货架开始卖对手模型)
- [15 个 PR 之后，Shopify 把审查拆到单条深链](#2-15-个-pr-之后shopify-把审查拆到单条深链)
- [元宝被砍，WorkBuddy 登顶：腾讯押注工作场景](#3-元宝被砍workbuddy-登顶腾讯押注工作场景)
- [Board 开放背后，Vercel 押注智能体协作基建](#4-board-开放背后vercel-押注智能体协作基建)
- [ARMORY CASTLE 打穿 vSphere：APT 火力正沉向虚拟化底座](#1-armory-castle-打穿-vsphereapt-火力正沉向虚拟化底座)
- [微软谷歌同日上架上下文层背后：战火烧向企业数据](#2-微软谷歌同日上架上下文层背后战火烧向企业数据)
- [Gemini 4 Neon 把思考做成档位：前沿竞争转向性价比](#3-gemini-4-neon-把思考做成档位前沿竞争转向性价比)
- [微软用 Cobalt 200 设计下一代芯片，自研飞轮开始自转](#4-微软用-cobalt-200-设计下一代芯片自研飞轮开始自转)

## 本期概览

- 候选文章：约 72 篇
- 公开覆盖原文：72 篇
- 候选订阅来源：Philipp Schmid(@_philschmid) / Google AI(@GoogleAI) / Gary Marcus(@GaryMarcus) / Vercel News / GitHub(@github) / lmarena.ai(@lmarena_ai) / Anthropic(@AnthropicAI) / Cursor(@cursor_ai)
- 公开阅读入口：https://oraink.com/public/daily/2026-11-20/

## 本期如何生成

本期公开日报汇聚公众号、推特、博客等渠道的优质博主和一线团队文章；灵砚先聚合近期信源内容，再结合 AI 摘要、主题标签、来源质量与编辑规则筛选重点，最后按主题分卷整理成公开版。公开版仅展示摘要、线索与观点，不转载原文全文。

## 今日目录

1. AI与智能化：AI与智能化 — 精要 4 条 / 思考 2 个
2. 网络安全：网络安全 — 精要 4 条 / 思考 2 个
3. 前沿科技：前沿科技 — 精要 4 条 / 思考 2 个
4. 软件与开发者：软件与开发者 — 精要 4 条 / 思考 2 个
5. 云计算与企业服务：云计算与企业服务 — 精要 4 条 / 思考 2 个

## 今日主线

- AI估值
- AI挖洞
- 零日漏洞
- 模型分发

## 1. AI与智能化

### AI与智能化

**关键词：** anthropic / ipo / ai资本化

### 今日精要

#### 1. Anthropic顶着联名信上市，首日开盘涨34%

昨日还陷在联名信风波里的 Anthropic 如期挂牌：83 美元定价、813 亿美元募资，超越 SpaceX 成全球史上最大 IPO，也是首家上市的前沿 AI 实验室。$ANT 首日开盘 111.5 美元，较发行价高出 34%，估值一度逼近 2 万亿美元。Dario Amodei 的 IPO 声明仍把「安全优先」写成核心原则，资本用开盘价给这场安全争论标出了第一个价格——往后，这套叙事要按季度向财报交作业。

标签：`anthropic` `ipo` `ai资本化`

相关材料：
- [当智能开始量产，从Anthropic上市看大模型的六个趋势](https://oraink.com/public/articles/103185)
- [速递｜Anthropic完成813亿美元IPO，创全球史上最大规模，估值达1.5万亿美元](https://oraink.com/public/articles/103150)
- [83美元/股！史上最大IPO定了，今晚见](https://oraink.com/public/articles/103293)
- [Remarks from Anthropic CEO @DarioAmodei on our initial public offering: My co-founders and I starte...](https://oraink.com/public/articles/103461)
- [We’ve priced our IPO at $83 per share, with trading expected to begin on Nasdaq tomorrow. https://t...](https://oraink.com/public/articles/102911)
- [PUBLIC: Anthropic stock is now live on the Nasdaq. $ANT opened at $111.50, which is $28.50 more tha...](https://oraink.com/public/articles/103466)
- [Anthropic IPO定价83美元/股，投资者疯抢](https://oraink.com/public/articles/103234)

订阅来源：腾讯研究院 / Z Potentials / 智东西 / Anthropic(@AnthropicAI) / The Rundown AI(@TheRundownAI)

#### 2. Neon以3美元拿下实测第二，评测者退订Claude

Google 发布 Gemini 4 Neon：由旗舰 Carbon 蒸馏而来，定价 3/15 美元每百万 token。它在 lmarena 的 Agent Arena Index 以 1336 分位列总榜第二，Cursor 称其刷新性价比前沿。实测博主在 18 款模型的编码评测中把它排到第二，随即宣布退订 Claude；Simon Willison 则吐槽 Gemini 4 家族新增 Neon 后定价乱成一团。蒸馏小模型正用极低价格蚕食旗舰的订阅基本盘，而 DeepMind 的版本发布间隔还在逐次减半。

标签：`gemini-4-neon` `llm` `推理价格战`

相关材料：
- [llm-gemini 0.38](https://oraink.com/public/articles/103108)
- [Thanks Google! I am cancelling my Claude subscription...](https://oraink.com/public/articles/103132)
- [Google DeepMind is shipping exponentially faster. The first Gemini 4 model was announced on Septemb...](https://oraink.com/public/articles/102960)
- [Big news: Gemini 4 Neon (High) is the best @GoogleDeepmind model on the Agent Arena Index, ranking #...](https://oraink.com/public/articles/102910)
- [Today we are releasing Gemini 4 Neon. 🚀 Faster than Carbon and more capable as Hydrogen. #3 on AA, ...](https://oraink.com/public/articles/102878)
- [Gemini 4 Neon is now available in Cursor! At its default effort, it sets a new cost-performance fro...](https://oraink.com/public/articles/102947)

订阅来源：Simon Willison's Weblog / AICodeKing / lmarena.ai(@lmarena_ai) / Philipp Schmid(@_philschmid) / Cursor(@cursor_ai)

#### 3. 机器人模型拿79分，OpenAI把机器人并进通用模型

OpenAI 发布 GPT-6.2 Astra 机器人版本，在机械臂真机评测中拿到 79 分；同期，运行不足半年的独立机器人团队被撤销，研究并入通用大模型体系。最好的机器人成绩与机器人团队的解散同期而至，路线判断已经写明：机器人不再是独立赛道，而是通用模型的下游任务。前 OpenAI 首席研究官 Bob McGrew 创办 Arda 后仍强调超级智能离不开物理世界，通用派与具身派的分歧才刚开始。

标签：`openai` `具身智能` `组织调整`

相关材料：
- [一个能拿 79 分的机器人模型，和一个被撤掉的团队](https://oraink.com/public/articles/103158)
- [Superintelligence Needs the Physical World with CEO and Co-Founder of Arda Bob McGrew](https://oraink.com/public/articles/103260)

订阅来源：有新Newin / No Priors

#### 4. Codex与Claude同日交卷：AI挖洞进入实战

两条 AI 挖洞战果同日披露：Greg Brockman 团队用 Codex 做 Ruby 安全研究，独立挖出 Rails 框架的预认证远程代码执行漏洞；Mozilla 透露曾在 Fable 撤回阶段用 Claude 对 Firefox 千万行代码做安全挖掘，一次性修复超 400 个漏洞，其中不乏潜伏十余年的老洞。漏洞发现开始像流水线作业。上周 GTIG 刚观测到无人在环的攻击，这周防守方的产能也被撑大，攻防双方的成本曲线在同时陡降。

标签：`ai安全` `漏洞挖掘` `codex`

相关材料：
- [https://t.co/7YnqMnFefK](https://oraink.com/public/articles/103284)
- [Codex for securing Ruby, with assistance from our team:](https://oraink.com/public/articles/103323)

订阅来源：Claude(@claudeai) / Greg Brockman(@gdb)

**本卷快讯**

· 谷歌Genie 4上架API：一句话生成720p可交互世界（Philipp Schmid / Sundar Pichai）
· LangChain完成3亿美元C轮估值30亿，同步公测Agent工具网关（Harrison Chase / LangChain）
· 联想手握800亿美元AI服务器订单，千亿美元年营收目标提前（腾讯科技）
· PostgreSQL 19发布：为处理AI上报的安全漏洞推迟两个月（Simon Willison）
· Claude Code新推Code Mode：不换模型，Token最高省77%（AI前线）
· 腾讯混元Hy4 flash上线首日登顶OpenRouter，单任务0.26元（AI前线）
· OpenAI推Responses API后台模式：可等待任务token最高省40%（OpenAI Developers）
· 英伟达全员大会：加薪提前到12月，拒绝召回黄仁勋并启动CEO遴选（腾讯科技 / 创业邦）
· Replit三天做出开源本地助手Amuse：数据不上云，免费可用（Replit）
· 快手Q3除AI业务外全线下滑，可灵成唯一增长支柱（白鲸出海）
· 小米MiMo负责人罗福莉被曝考虑独立创业，或因分拆融资分歧（创业邦）
· 首个3D游戏Agent竞技场：代码分接近的Agent，人类盲测胜率差2.6倍（我爱计算机视觉）

### 今日思考

#### 当安全叙事变成招股书卖点，安全承诺的约束力还剩多少？

**今日信号：** Anthropic 顶着联名信完成史上最大 IPO，首日开盘较发行价上涨 34%

**灵砚视角：**  
灵砚视角：联名信质疑的是安全招牌名不副实，市场却用近 2 万亿美元的估值给这块招牌背书。上市之后，安全投入将第一次以成本项的形态出现在季报里——如果削减安全预算能提振利润，真正的压力测试才算开始。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t1)

#### 攻防双方都用上模型后，存量系统的安全欠账会被清算还是被引爆？

**今日信号：** Codex 挖出 Rails 预认证 RCE，Claude 为 Mozilla 修复超 400 个漏洞

**灵砚视角：**  
灵砚视角：上周 GTIG 刚观测到无人在环攻击，这周防守方拿到同款产能。真正的变化不是谁更强，而是时间常数——潜伏十余年的漏洞被一次性清出，说明欠账清算速度已绑定模型迭代节奏，安全从事件驱动转向节奏驱动。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t2)


## 2. 网络安全

### 网络安全

**关键词：** nginx2root / 远程代码执行 / AI挖洞

### 今日精要

#### 1. AI揪出nginx十年RCE，千万服务器补丁竞速开场

F5 一口气修复 5 个未授权远程代码执行漏洞，合称 nginx2root：HTTP/2 模块的 CVE-2026-123007 潜伏十年、CVSS 9.2，可容器逃逸直取宿主机 root。多家安全团队借助 AI Agent 完成挖掘，十年无人察觉的老洞被集中翻出。PoC 与 EXP 已公开、暂未发现在野利用，数千万台 Nginx 主机进入补丁竞速，修复版本为 1.31.9 与 1.30.7。

标签：`nginx2root` `远程代码执行` `AI挖洞` `漏洞预警`

相关材料：
- [【漏洞通告】nginx多模块内存安全漏洞链式远程代码执行漏洞(nginx2root)](https://oraink.com/public/articles/103453)
- [【已复现】nginx 多个远程代码执行漏洞（nginx2root）](https://oraink.com/public/articles/103394)
- [AI挖出Nginx潜伏十余年的RCE漏洞：无需认证，数千万服务器面临风险](https://oraink.com/public/articles/103211)
- [【安全圈】NGINX潜伏十年漏洞曝光：无需认证直接远程执行代码](https://oraink.com/public/articles/103249)
- [【已复现】nginx2root nginx 多个远程代码执行漏洞安全风险通告](https://oraink.com/public/articles/103232)
- [NGINX HTTP/2：已存在10年，可导致未认证攻击者在服务器上执行代码](https://oraink.com/public/articles/103203)
- [nginx2root nginx多个远程代码执行漏洞安全风险通告](https://oraink.com/public/articles/103200)
- [【漏洞通告】Nginx多个远程代码执行漏洞（CVE-2026-123007/CVE-2026-123634/CVE-2026-123633/CVE-2026-121810/CVE-2026-113425）](https://oraink.com/public/articles/103405)
- [【风险提示-已复现】天融信关于nginx多个远程代码执行漏洞(nginx2root)的风险提示](https://oraink.com/public/articles/103366)
- [已复现！nginx2root nginx http2 远程代码执行漏洞](https://oraink.com/public/articles/103341)

订阅来源：深信服千里目安全实验室 / 长亭安全课堂 / 看雪学院 / 安全圈 / 奇安信CERT

#### 2. 官方包也失守：微软AI框架PyPI遭账号劫持投毒

微软官方 AI Agent 框架的 PyPI 发布账号被劫持，攻击者发布内置窃密逻辑的恶意版本，无需显式导入即可静默窃取云服务、CI/CD 与大模型 API 凭据。被瞄准的是开发者对官方渠道的默认信任：Agent 框架天然经手全套凭据，投毒一次即可收割一整层基础设施。恶意包现已下架，但发布权限如何失守仍无解释，涉案版本为 1.26.1 与 1.26.2。

标签：`供应链安全` `PyPI投毒` `AI Agent` `凭据窃取`

相关材料：
- [Microsoft AI Agent开发框架遭遇供应链攻击，被植入恶意代码](https://oraink.com/public/articles/103122)
- [【安全圈】微软官方AI框架遭投毒：悄悄盗取云端令牌与CI凭据](https://oraink.com/public/articles/103250)

订阅来源：白泽安全实验室 / 安全圈

#### 3. 1.8亿下载的模型账号，被一个过期域名轻松接管

奇安信复盘 Kokoro 事件：安全研究员仅重新注册一个过期域名，就接管了 Hugging Face 上的高热度模型发布者账号，并在本地验证了权重篡改的可行性。模型生态的信任链，断点落在一个域名注册记录上。1.8 亿次的累计下载量，没有为这个账号换来任何更强的身份保障；事件全程受控，未造成实际恶意扩散。

标签：`AI供应链` `Hugging Face` `账号接管` `模型安全`

相关材料：
- [一次受控接管，撕开 AI 模型供应链的信任缺口：Kokoro 事件复盘](https://oraink.com/public/articles/103196)

订阅来源：奇安信威胁情报中心

#### 4. Vite曝未授权RCE：开发环境正式算进攻击面

长亭、深信服、腾讯云鼎三家同日预警：前端构建工具 Vite 的开发服务器一旦暴露到网络，未授权攻击者即可读取任意文件、执行任意代码。开发环境不再是可以豁免防护的灰色地带。当本地工具链默认联网、默认持有令牌，dev 与 prod 的边界失守成本正在逼近生产事故，深信服已将其编号为 SF_2026_47139 纳入跟踪。

标签：`Vite` `开发环境安全` `远程代码执行` `前端安全`

相关材料：
- [【已复现】Vite 开发服务器暴露至网络可致远程代码执行](https://oraink.com/public/articles/103395)
- [预警！Vite 开发服务器暴露于网络，可致任意代码执行](https://oraink.com/public/articles/103263)
- [【漏洞通告】Vite 开发服务器虚拟模块注入远程代码执行漏洞(SF_2026_47139)](https://oraink.com/public/articles/103454)

订阅来源：长亭安全课堂 / 云鼎实验室 / 深信服千里目安全实验室

**本卷快讯**

· Linux内核CVE-2026-98432全版本曝RCE，AI可快速生成利用码（安全客）
· F5曝6枚BIG-IP数据平面高危漏洞，无配置规避只能上工程热补丁（安全圈）
· PHP全受支持版本发安全更新，此前PHP2Shell已遭活跃利用（代码卫士）
· 谷歌GTIG预警：半年内全自主AI攻击将成为常态（安全客）
· 两名举报人泄露1500万份德银文件，70亿欧元合规整改叙事被推翻（黑鸟）
· 印度AI催收平台CreditNirvana硬编码密钥，数百万债务数据暴露（互联网安全内参）
· 兴业银行因数据安全与科技外包管理不到位被罚695万元（信息安全国家工程研究中心）
· MiSRC联合20家SRC发布AI Agent授权安全测试规范（小米安全中心）
· Corma融1.25亿美元估值破10亿，专攻安全防御AI基础模型（数世咨询）
· 停维护的Apache Axis 1.x曝未授权反序列化RCE，只能迁移或拦截（深信服千里目安全实验室）
· Yak推出AI Agent研发的反编译器Reify，瞄准替代IDA（Yak Project）
· 复旦白泽在PoC 2026披露TrustedInstaller全球首个完整分析（复旦白泽战队）

### 今日思考

#### 挖洞与打洞同时被 AI 提速之后，补丁窗口该按什么节奏管理？

**今日信号：** AI Agent 挖出 nginx 潜伏十年的 RCE，同一天 GTIG 预警半年内自主攻击将成常态

**灵砚视角：**  
灵砚视角：AI 把漏洞的发现与利用一起提速，攻防时间差正被双向压缩。十年老洞被集中翻出，说明『没人发现』不再是安全余量；GTIG 的半年倒计时又把防守规划逼到按天计算。变化的核心不在漏洞数量，而在节奏换了档。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t1)

#### 官方渠道的默认信任被击穿后，开发者的信任锚该落在哪里？

**今日信号：** 微软官方 AI Agent 框架的 PyPI 发布账号被劫持，两个版本静默窃取凭据

**灵砚视角：**  
灵砚视角：攻击者瞄准的不是某个包，而是开发者对官方发布渠道的无条件信任。Agent 框架天然经手云凭据、CI/CD 与模型 API Key，投毒一次即可收割一整层基础设施。锁版本、验哈希、盯发布账号异动，正在从可选项变成必选项。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t2)


## 3. 前沿科技

### 前沿科技

**关键词：** Anthropic / IPO / AI估值

### 今日精要

#### 1. Anthropic 上市后回落 17%，泡沫争论有了价格

Anthropic 的上市交易没能守住热度：开盘冲高后持续回落约 17%，多数主流 AI 股已跌去双位数，被比作压缩到一个下午的郁金香狂热。WSJ 同日披露，曾推高英伟达股价约 10 美元的 5000 亿美元华尔街承诺从未实际出资，媒体未经核查照单传播；鲍尔森、李彦宏先后警告资金错配，股权转债务的结构被指与 2008 年同构。FT 测算：1 万亿美元算力承诺换 20% 回报需 6020 亿美元年营收，超过谷歌、苹果全年营收。

标签：`Anthropic` `IPO` `AI估值` `市场`

相关材料：
- [“I've never seen so much money chasing one opportunity with not a lot of earnings and ROI backing it...](https://oraink.com/public/articles/103225)
- [1. this probably won’t happen 2. what happens to the company if it doesn’t?](https://oraink.com/public/articles/103226)
- [my opinion of Jensen keeps dropping as more facts comes to light](https://oraink.com/public/articles/103066)
- [🚨 Anthropic had a big opening pop, but has steadily fallen ever since the open, around 17%. And th...](https://oraink.com/public/articles/103470)
- [Nearly every major AI stock has dropped double digits since this dubious (but confidently delivered)...](https://oraink.com/public/articles/102903)
- [Looking tentatively like tulipmania compressed to an afternoon, with banks and institutional investo...](https://oraink.com/public/articles/103471)
- [You know who else should be investigated? The media, for mostly being chumps and repeating a bunch...](https://oraink.com/public/articles/103343)

订阅来源：Gary Marcus(@GaryMarcus)

#### 2. AMD 被指违禁售华：半小时跌 13%，管制动真格

AMD 被指控非法向中国出售芯片，30 分钟内股价下跌 13%，而发布指控的机构同步持有 AMD 空头仓位，动机本身存疑。管制尺度正在变成芯片股的新定价因子：彭博此前披露英伟达高管曾干预走私案调查，中文科技圈普遍判断黄仁勋误判了美方尺度、灰色放水时代行将结束。CNN 同日给出另一面——至少 6 家被列黑名单的中国高校近年仍买到受限英伟达芯片，其中 2 家涉军高校近数月仍未停手。

标签：`AMD` `出口管制` `英伟达` `半导体`

相关材料：
- [我有个感觉，我说的是感觉。 一直以来，老黄都以为老美和他闹着玩呢，自己悄悄卖一点点给我们问题不大，或者说睁一只眼闭一只眼。 没想到老美这次是来真的，说白了就是玩砸了，事到如今再回去，他必定坚决执行...](https://oraink.com/public/articles/103048)
- [The thing about export controls? Nobody thought the rules applied to *them*. Effectively it was al...](https://oraink.com/public/articles/103472)
- [keeps getting worse](https://oraink.com/public/articles/103342)

订阅来源：Geek(@geekbb) / Gary Marcus(@GaryMarcus)

#### 3. GR00T 2 开源背后，具身智能打响数据粮草战

机器人训练数据的成本，正被三路同日压低。英伟达 Jim Fan 开源 GR00T 2：无剪辑、1 倍速端到端控制真实灵巧手，可跑 20+ 步骤、5 分钟以上长时任务，10 万小时训练数据与全栈资源一并开放。上海 AI Lab 的 EgoExplorer 用 5 个追踪器加数据手套替掉动捕棚，全身运动重建误差较基线降低 71.9%。Runway 把 27B 视频模型 Praxis-1 送进机器人：不足 30 分钟遥操作演示，通过 Noble Machines 全部 15 项模拟测试。具身智能的数据粮草，正从稀缺品变成公共品。

标签：`具身智能` `GR00T2` `开源` `机器人`

相关材料：
- [5个追踪器替掉动捕棚：上海AI Lab把具身数据采集做成了可穿戴管线](https://oraink.com/public/articles/103014)
- [Autonomous, uncut, 1x speed. This is GR00T 2 controlling real dexterous hands, end to end.](https://oraink.com/public/articles/103448)
- [It also learns new tasks from very little data. With under 30 minutes of teleoperated demos, Praxis-...](https://oraink.com/public/articles/103568)
- [Praxis-1 is a 27B-parameter mixture-of-experts diffusion transformer that predicts video and actions...](https://oraink.com/public/articles/103567)

订阅来源：量子位 / Jim Fan(@DrJimFan) / Runway(@runwayml)

#### 4. 「谷歌以前很糟」：Gemini 4 半价追平 Opus

Google 发布 Gemini 4 Neon，主打前沿智能与端到端任务效率，Antigravity 同日开始向付费 Pro 用户推送。更关键的是第三方评测方 Browser Use 的实测：浏览器操作准确率 74%，追平 Opus 5.5，成本仅其一半，「谷歌以前在这里很糟」的旧印象正在失效。不过在智能体场景的新计分板下，同价位 GPT-6.2 Sol 准确率仍更高，继续守住 SOTA。

标签：`Gemini` `大模型` `智能体` `谷歌`

相关材料：
- [Meet Gemini 4 Neon — our newest model that brings frontier-level intelligence with fast end-to-end t...](https://oraink.com/public/articles/102899)
- [Gemini 4 Neon is actually very good at browser use 👀 google used to be terrible here, but every re...](https://oraink.com/public/articles/103046)
- [Rolling out today in @GeminiApp for Google AI Pro and Ultra subscribers, @Antigravity for paid Pro a...](https://oraink.com/public/articles/102900)

订阅来源：Google AI(@GoogleAI) / Browser Use(@browser_use)

**本卷快讯**

· 范式智能首发 Phai-A1 与 Phai-M1：全链路昇腾训练，将开放权重（量子位）
· 可灵发布 Kling Image 4.0：原生 8K 生图，支持长图与多参考图融合（量子位）
· Qwen4-Max 登陆 Nous Portal：1M 上下文，5 天免费体验（Qwen）
· ElevenLabs 医保试点：对话智能体独立完成近六成拒赔申诉全流程（ElevenLabs）
· Java4Shell 等漏洞一周密集出现，Cognition 上线 Devin 漏洞索引服务（Cognition）
· Ollama CEO：开源模型已进企业生产负载，关切转向数据流向（ollama）
· 罗马尼亚律师因未核查 AI 生成的诉讼材料被禁业 2 年（Gary Marcus）
· grok-bot.directory 上线首日：1200+ 机器人提交、7000+ 次添加（eric zakariasson）
· Quora 换帅：John Peacock 出任 CEO，创始人转任执行主席（Adam D'Angelo）
· OpenCode 实测：GLM-5.3 请求量仅为 DeepSeek V4.1 Flash 的约 1/6（Geek）
· ExaAI 全栈使用 Devin Bots，每周自主合并数千 PR 无需值守（Cognition）
· Starlight Arena 开 5 万美元智能体诱导赛：不入侵系统，只靠说服（AI Breakfast）

### 今日思考

#### 当官宣金额与实际到账的差距足以驱动股价，谁来为 AI 资本市场的信息质量负责？

**今日信号：** WSJ 披露华尔街承诺英伟达的 5000 亿美元从未实际出资，同日 Anthropic 上市后回落约 17%

**灵砚视角：**  
灵砚视角：单日涨跌不足为凭，但承诺与到账之间的缝隙正在变成可定价的风险。当股权融资让位于高成本债务，约束 AI 公司的将不再是被故事说服的投资人，而是要求还本付息的债权人——后者从来不听故事。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t1)

#### 当数据采集成本塌方，具身智能的护城河会转移到哪里——硬件、真机验证，还是数据所有权？

**今日信号：** 英伟达开源 10 万小时机器人数据，上海 AI Lab 用 5 个追踪器替掉动捕棚，Runway 让视频模型 30 分钟学会新任务

**灵砚视角：**  
灵砚视角：数据稀缺的叙事正在失效。三家同日从不同路径压低采集成本，说明行业共识已从攒数据转向流动数据。下一个稀缺品可能是真机验证与安全兜底——视频模型会生成动作，但不会为事故负责。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t2)


## 4. 软件与开发者

### 软件与开发者

**关键词：** Gemini 4 Neon / Copilot / 模型分发

### 今日精要

#### 1. Copilot 再添谷歌 Neon，货架开始卖对手模型

昨天 GPT-6.2 刚进 Copilot，今天谷歌 Gemini 4 Neon 就全量上架，Vercel AI Gateway 同步接入。Neon 面向智能体编码：性能贴近 Gemini 4 Carbon，任务成本更低、非请求改动更少，另有多模态与百万 token 上下文。配合面向 Pro 用户开放的 Hydrogen，谷歌按化学元素命名的四档型号正分层铺进各家渠道。对手的货架，正在变成谷歌模型的分发渠道。掘金实测 Hydrogen 基准亮眼但工程稳定性不足，分层策略仍在填坑。

标签：`Gemini 4 Neon` `Copilot` `模型分发`

相关材料：
- [Google发布Gemini 4 Neon多模态模型，商汤推出SenseNova-Loop-9B正式版](https://oraink.com/public/articles/103237)
- [谷歌太抽象了，快速测一下Hydrogen！](https://oraink.com/public/articles/103176)
- [Gemini 4 Neon now available on AI Gateway](https://oraink.com/public/articles/102906)
- [🆕 @GoogleAI's Gemini 4 Neon is now generally available in GitHub Copilot. It is designed for agent...](https://oraink.com/public/articles/102907)

订阅来源：机器之心SOTA模型 / 掘金本周最热 / Vercel News / GitHub(@github)

#### 2. 15 个 PR 之后，Shopify 把审查拆到单条深链

AI 出码速度正在把审查甩在身后：昨天资深工程师用辞职表达失配，今天机构给出了流程性答案。Shopify 披露移动应用代码吞吐达去年同期 11 倍，做法是把安全审查拆到单条深链粒度，靠分类攻击面地图和可迭代 Skill 承接；CMU 17-214 课程主张把静态与动态检查设为 CI 流水线门禁，专治 Agent 一下午改 2000 行的出码速度，还配套防绕过设计。审查正从人的注意力，变成系统的结构，腾讯云开发者则把验证闭环称作大 Agent 时代的第一瓶颈。

标签：`AI 编码` `安全审查` `CI 门禁`

相关材料：
- [Shopify：移动应用出码提速 11 倍后，用攻击面地图把安全审查拆到单条深链 来自 @ShopifyEng 工程团队博客，在 Agent 时代，他们移动应用的代码吞吐已经是去年同期的 11 倍。...](https://oraink.com/public/articles/103026)
- [当AI生成快到溢出，大Agent时代该讨论些什么？](https://oraink.com/public/articles/103040)
- [CMU 17-214 第 21 讲：Agent 一下午改 2000 行，就把检查做成流水线门禁 CMU 17-214「Agentic Software Development」课程认为，有了 Cod...](https://oraink.com/public/articles/103103)

订阅来源：meng shao(@shao__meng) / 腾讯云开发者

#### 3. 元宝被砍，WorkBuddy 登顶：腾讯押注工作场景

腾讯财报电话会出现罕见对照：总裁刘炽平坦言元宝未达预期、已大幅缩减开支；同一份财报里，WorkBuddy 按用户每日 token 消耗总量衡量已是国内第一。C 端助手烧钱换增长的叙事开始退潮，token 消耗的主战场转向工作场景，管理层还讲了 Flash 模型获客变现的策略。而元宝缩减开支的同时，公众号广告照投不误。

标签：`腾讯` `元宝` `WorkBuddy`

相关材料：
- [刚看完腾讯财报后电话会议中，马化腾和刘炽平关于 WorkBuddy 的一些观点和数据分享，有几个发现，一起看看 1. 按用户每日大语言模型 Token 消耗总量衡量，WorkBuddy 已发展成为国...](https://oraink.com/public/articles/103121)
- [腾讯总裁刘炽平表示，元宝此前没有达到预期的成功，所以目前已大幅缩减开支！ 所以元宝是边「大福缩减开支」，边继续在公众号投广告，而且广告一往既往的莫名其妙 😅](https://oraink.com/public/articles/103027)

订阅来源：meng shao(@shao__meng)

#### 4. Board 开放背后，Vercel 押注智能体协作基建

Vercel 把内部验证过的智能体协作消息板 Board 开放给所有套餐：无预设 UI、框架无关，CEO Rauch 类比它是智能体集群的 Redux、去中心化协作的 headless Slack，已在内部安全智能体集群与 v0 软件工厂跑通，解决多智能体的任务跟踪与状态同步。同日 Netlify 十年最大改版，把 Agent 搭建与开发者工作流合流，单日新增 10 万用户、ARR 破 1 亿美元。部署平台正把自己重写成智能体基建，Rauch 强调 Board 是 infra 而非 product。

标签：`Vercel Board` `智能体基建` `Netlify`

相关材料：
- [Introducing Vercel Board](https://oraink.com/public/articles/103032)
- [𝚟𝚎𝚛𝚌𝚎𝚕 𝚋𝚘𝚊𝚛𝚍 has no heavyweight or opinionated UI. It's infra not product. I love the "he...](https://oraink.com/public/articles/103452)
- [Netlify 十年最大改版：让 Agent 搭建和开发者改代码走同一套工作流 @Netlify 创始人兼 CEO @biilmann 宣布，公司推出新品牌、新网站，以及从头重新做的应用体验。他称之...](https://oraink.com/public/articles/103024)
- [Vercel Board is now available](https://oraink.com/public/articles/103033)
- [One of the most impressive things I've seen, and I think this is an important advancement to the sta...](https://oraink.com/public/articles/103011)

订阅来源：Vercel News / Guillermo Rauch(@rauchg) / meng shao(@shao__meng)

**本卷快讯**

· Nginx 两项 HTTP/2 高危漏洞可无登录远程执行代码，官方已修复（小众软件）
· 微软宣布 2027 年关闭 To Do，企业任务并入 Planner（小众软件）
· GitHub 推官方验证 MCP 连接器公测，Copilot 一次配置多端可用（GitHub）
· 谷歌开源 ABFS 构建服务，AOSP 检出从 36 分钟压到 8 秒（meng shao）
· 谷歌 MaxText 引入 Streaming DiLoCo，跨区训练通信量降 60 倍（Google Developers Blog）
· GPT-6.2 Astra 口碑翻车，多位知名开发者公开表示不推荐（掘金）
· Flutter 3.50 稳定原生互操作，Platform Channel 将逐步退场（掘金）
· DeepSeek 发布 Agent 运行环境 DSH，六层架构可插拔（掘金）
· MongoDB 政府版获 FedRAMP 最高等级认证，成唯一跨云数据库（MongoDB Blog）
· 开发者用 REA 逆向自家 Electron 应用，扫出 178 个 IPC 通道（掘金）
· Android 峰会放出 Jetpack Compose 多端适配更新，覆盖折叠屏到车机（Android 开发者）
· GitHub 称开源贡献一年翻倍，同步发布 Replica 设计工具（The GitHub Blog）

### 今日思考

#### 出码速度是审查的 11 倍时，团队核心会从写代码的人换成建门禁的人吗？

**今日信号：** Shopify 把安全审查拆到单条深链，CMU 17-214 把代码检查设为流水线门禁

**灵砚视角：**  
灵砚视角：审查正从个人手艺变成系统结构，信任对象从开发者转向攻击面地图。粒度细到单条深链后，安全工程师会向地图维护者迁移，普通工程师的价值锚点也从写出代码移向定义门禁。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t1)

#### 推理云会重演 CDN 的收敛史，还是被模型厂商自建推理吞掉？

**今日信号：** rauchg 称平均每两天收到一家新推理云推介，其网关 token 需求月增 40%

**灵砚视角：**  
灵砚视角：供给从稀有变成两天一家，定价又贴着成本，洗牌的燃料只剩需求增速本身。40% 月增若能持续，扩张还能吸收新玩家；一旦放缓，整合会以季度为单位清算大部分名字。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t2)


## 5. 云计算与企业服务

### 云计算与企业服务

**关键词：** 安全 / 零日漏洞 / 虚拟化

### 今日精要

#### 1. ARMORY CASTLE 打穿 vSphere：APT 火力正沉向虚拟化底座

Mandiant 与谷歌威胁情报团队披露，APT 组织 ARMORY CASTLE（原 UNC5221）正利用未公开零日 CVE-2026-123890 攻击 VMware vCenter，完整攻击链、定制恶意工具集与漏洞细节一并曝光，受影响组织被敦促尽快安装补丁。虚拟化管理面一旦失守，其上的全部业务系统都在同一射程内。继 Java4Shell 之后，这是本周第二起沉向基础底座的攻击——应用层加固的边际收益递减，攻防主战场正在下移。

标签：`安全` `零日漏洞` `虚拟化`

相关材料：
- [ARMORY CASTLE Exploits vSphere](https://oraink.com/public/articles/103296)

订阅来源：Google Cloud Blog

#### 2. 微软谷歌同日上架上下文层背后：战火烧向企业数据

微软在 Ignite 推出企业上下文平台 Microsoft IQ，把组织独有的流程、知识与数据打包成智能体可调用的资产；谷歌几乎同时开放 Cloud Storage 的 Object Enrichments 预览，用 AI 就地为非结构化对象生成上下文元数据；Oracle 数据库也经 AI Database@Azure 接入微软智能体生态。前沿模型趋于同质，差异化正从模型能力转向企业私有数据。三件产品同日落地，上下文层就此有了货架。

标签：`智能体` `企业上下文` `云竞争`

相关材料：
- [Introducing the new Microsoft IQ: Putting your organization’s intelligence to work in every agent](https://oraink.com/public/articles/103079)
- [Introducing object enrichments: Transform unstructured data into agent-ready context](https://oraink.com/public/articles/103439)
- [Microsoft and Oracle bring agentic AI into flow of enterprise work](https://oraink.com/public/articles/103074)
- [Microsoft Ignite 2026: What’s new in Azure, the platform purpose-built for AI](https://oraink.com/public/articles/103076)

订阅来源：Microsoft Azure Blog / Google Cloud Blog

#### 3. Gemini 4 Neon 把思考做成档位：前沿竞争转向性价比

谷歌全量开放 Gemini 4 Neon：面向复杂专业工作流，主打高智能、低幻觉与高性价比，开发者、企业与个人用户同日可用。除了能力指标，档位化思考把推理深度做成了可调项。当推理成本成为规模化落地的瓶颈，谷歌把「想多久」的选择权直接交到了每个用户手里。

标签：`大模型` `Gemini` `推理成本`

相关材料：
- [Gemini 4 Neon 发布](https://oraink.com/public/articles/103204)

订阅来源：谷歌开发者

#### 4. 微软用 Cobalt 200 设计下一代芯片，自研飞轮开始自转

微软宣布自研 3nm ARM 芯片 Cobalt 200 虚拟机正式通用可用，通用负载较上代 Cobalt 100 最高提速 50%。更耐人寻味的细节是：微软把自家芯片设计的 EDA 工作流搬上了 Cobalt 200，实测提速 1.30 至 4.15 倍，用自家芯片设计下一代芯片。自研硅从降本工具变成能自我迭代的飞轮，Cobalt 200 已上线 14 个区域，年底将扩至 23 个。

标签：`自研芯片` `Cobalt` `EDA`

相关材料：
- [Designing Azure silicon on Azure silicon: EDA workloads on Cobalt 200](https://oraink.com/public/articles/103082)
- [Azure Cobalt 200 VMs now available, proven on real workloads and built for the agentic era](https://oraink.com/public/articles/103077)

订阅来源：Microsoft Azure Blog

**本卷快讯**

· 微软 Foundry 公测 Kling、LTX、MiniMax 视频模型，符合美国数据驻留（Microsoft Azure Blog）
· 微软推出 Azure Catalyst，用智能体改造存量应用并跨云边端部署（Microsoft Azure Blog）
· 微软 Foundry 引入代理持续改进，构建、运行、治理收进一个平台（Microsoft Azure Blog）
· 谷歌晒 4 个公共部门案例：洛杉矶市政、夏威夷大学用 Gemini 摆脱重复行政（Google Cloud Blog）
· 微软披露 Azure 硬件故障预测系统，硬件相关 VM 中断降低 36%（Microsoft Azure Blog）
· GKE 开放 Dataplane V2 原地迁移预览，eBPF 数据平面升级可回滚（Google Cloud Blog）
· 微软撰文称智能体不该当一次性项目，应按持续纪律配套投资框架（Microsoft Azure Blog）
· Google Cloud 在 Partner Marketing Studio 上线 Gemini 营销功能（Google Cloud Blog）

### 今日思考

#### 上下文层被平台收编后，企业知识会不会变成新的锁定？

**今日信号：** 微软 IQ 与谷歌 Object Enrichments 同日把企业知识包装成智能体供给

**灵砚视角：**  
灵砚视角：模型同质化之后，差异化确实沉到了数据侧，但把私有知识注入厂商托管的上下文层，等于把护城河交给平台代管。未来的迁移成本可能不在模型费，而在知识搬迁，上下文锁定的雏形已经出现。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t1)

#### 攻击者集体沉底，基础软件的补丁经济学还撑得住吗？

**今日信号：** Java4Shell 之后 vSphere 零日再中弹，基础底座一周两次被点名

**灵砚视角：**  
灵砚视角：虚拟化管理面一次沦陷等于整片业务沦陷，但 vCenter 这类底座的停机窗口天然稀缺，补丁永远排在变更流程末尾。攻击节奏按天走、修补节奏按季度走，这笔账越来越算不过来。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-20#thought-t2)

## 跨分类洞察

### 共同线索：这些更新正在汇成同一条阅读主线

AI与智能化、网络安全、前沿科技、软件与开发者 看似分散，但对这位用户而言都进入了同一天的阅读预算。分组先保留每个方向的独立判断，再用顶部总题把最相关的前两条主线合并成今天的个人日报入口。

> 今日 72 篇更新 → 20 条信号 + 56 条快讯，其余已替你读过

---

由 **灵砚 Oraink** 自动整理。公开版仅展示摘要、线索与观点，详细内容请跳转到服务内阅读。

<!-- latest daily content ends -->

---

## License

Content in this repository is licensed under CC BY-NC-ND 4.0 unless otherwise noted.
