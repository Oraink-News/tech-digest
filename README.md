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

> 本期归档文件：[daily/2026/10/2026-10-16.md](daily/2026/10/2026-10-16.md)

<!-- latest daily content starts -->

# 从云与后端到国行手机，智能体多点落地，开源本地与 AI 攻防同日升温

> 谷歌云和 Vercel 都在把智能体做成基建，Meta 的开源模型把部署拉回本地，消费电子端苹果国行 AI 与阿里巴巴同框；当 AI 从模型层渗进平台与设备，安全板块的进攻性 AI 与漏洞议题，正好是这场落地的另一面。

**灵砚日报 · ORAINK DIGEST**  
2026-10-16 · 日报 · Vol. 388

- 今日处理文章：620
- 主精选条目：19
- 预计阅读：6 分钟
- 今日主线：智能体基建 / 开源本地 / 国行AI / AI攻防

## 速览

- [XBOW六天造出Chrome利用链，攻击开始明码标价](#1-xbow六天造出chrome利用链攻击开始明码标价)
- [OpenAI抓内鬼背后：AI公司谍战烧到自家会议室](#2-openai抓内鬼背后ai公司谍战烧到自家会议室)
- [定向广告不再只是广告，间谍软件借道零点击入户](#3-定向广告不再只是广告间谍软件借道零点击入户)
- [LiteLLM曝双高危漏洞：AI网关成了新靶心](#4-litellm曝双高危漏洞ai网关成了新靶心)
- [Meta 高调回归开源背后，前沿门槛落到两台 Mac](#1-meta-高调回归开源背后前沿门槛落到两台-mac)
- [ChatGPT 操控 Chrome：AI 入口战烧进浏览器](#2-chatgpt-操控-chromeai-入口战烧进浏览器)
- [Figma 把代码搬上画布，设计与代码边界开始消失](#3-figma-把代码搬上画布设计与代码边界开始消失)
- [1/12 算力追平 DeepSeek：微软自研基座上牌桌](#4-112-算力追平-deepseek微软自研基座上牌桌)
- [Vercel 押注智能体运行时：补齐常驻进程与持久存储](#1-vercel-押注智能体运行时补齐常驻进程与持久存储)
- [开源权重吃下 71.5% token，钱还在闭源手里](#2-开源权重吃下-715-token钱还在闭源手里)
- [百万美元悬赏钓出内核零日，智能体沙箱现出裂缝](#3-百万美元悬赏钓出内核零日智能体沙箱现出裂缝)
- [Netflix 编码提速两三成背后，AI 工程进入交账期](#4-netflix-编码提速两三成背后ai-工程进入交账期)
- [谷歌云四连更背后：云产品开始把 agent 当默认客户](#1-谷歌云四连更背后云产品开始把-agent-当默认客户)
- [四厂商案例同日换剧本：企业AI从能不能讲到快不快](#2-四厂商案例同日换剧本企业ai从能不能讲到快不快)
- [替你管特权的 BeyondTrust，成了间谍组织的门](#3-替你管特权的-beyondtrust成了间谍组织的门)
- [苹果国行 AI 定档月底：Siri 缺席，阿里补位](#1-苹果国行-ai-定档月底siri-缺席阿里补位)
- [折价四成仍破发：传音的 AI 故事先输一阵](#2-折价四成仍破发传音的-ai-故事先输一阵)
- [小米开源业界首个空间听觉大模型，抢跑人车家生态](#3-小米开源业界首个空间听觉大模型抢跑人车家生态)
- [禾赛 AI 空间相机背后：激光雷达厂转做具身数据生意](#4-禾赛-ai-空间相机背后激光雷达厂转做具身数据生意)

## 本期概览

- 候选文章：约 58 篇
- 公开覆盖原文：58 篇
- 候选订阅来源：Guillermo Rauch(@rauchg) / Figma(@figma) / 爱范儿 / 腾讯云开发者 / dbaplus社群 / The JetBrains Blog / 深网腾讯新闻 / 机器之心SOTA模型
- 公开阅读入口：https://oraink.com/public/daily/2026-10-16/

## 本期如何生成

本期公开日报汇聚公众号、推特、博客等渠道的优质博主和一线团队文章；灵砚先聚合近期信源内容，再结合 AI 摘要、主题标签、来源质量与编辑规则筛选重点，最后按主题分卷整理成公开版。公开版仅展示摘要、线索与观点，不转载原文全文。

## 今日目录

1. 网络安全：网络安全 — 精要 4 条 / 思考 2 个
2. 前沿科技：前沿科技 — 精要 4 条 / 思考 2 个
3. 软件与开发者：软件与开发者 — 精要 4 条 / 思考 2 个
4. 云计算与企业服务：云计算与企业服务 — 精要 3 条 / 思考 2 个
5. 消费电子：消费电子 — 精要 4 条 / 思考 2 个

## 今日主线

- 智能体基建
- 开源本地
- 国行AI
- AI攻防

## 1. 网络安全

### 网络安全

**关键词：** ai-security / offensive-ai / vulnerability

### 今日精要

#### 1. XBOW六天造出Chrome利用链，攻击开始明码标价

XBOW 用六天拼出 Chrome 完整 0day 利用链，从谷歌领走 25 万美元赏金；博思艾伦同日实测，前沿 AI 最快 16 分钟即可从边界自主攻入工控控制区。青藤报告补上商业注脚：OpenAI 已将网络进攻能力商品化，攻击可以买，防守只能自建。数世咨询当场泼冷水：智能体没那么厉害，只是安全措施缺失。六天、25 万美元、16 分钟，三个数字就是今天的攻防账本。

标签：`ai-security` `offensive-ai` `vulnerability`

相关材料：
- [工控安全也被变革？实测：前沿AI均能自主劫持工控系统](https://oraink.com/public/articles/87474)
- [六天，研究员利用AI模型构建 Chrome 完整利用链，获赏$25万](https://oraink.com/public/articles/87375)
- [AI攻防备战报告：攻击可以买，防守只能自建](https://oraink.com/public/articles/87470)
- [智能体没那么厉害 安全措施缺失而已](https://oraink.com/public/articles/87439)

订阅来源：互联网安全内参 / 代码卫士 / 青藤技术服务 / 数世咨询

#### 2. OpenAI抓内鬼背后：AI公司谍战烧到自家会议室

继昨日 DeepSeek 办公室藏录音器之后，OpenAI 高管会议室也被查出窃听器，一名 35 岁工程师涉案，经 OpenAI 自家模型协助调查后被 FBI 逮捕。两天两案，从办公室蔓延到会议室，物理谍战正在成为 AI 行业的日常风险——安全边界从防火墙退回到四面墙。

标签：`ai-security` `espionage` `insider-threat`

相关材料：
- [OpenAI高管会议室惊现窃听器，35岁工程师涉案被AI举报送进FBI](https://oraink.com/public/articles/87475)

订阅来源：互联网安全内参

#### 3. 定向广告不再只是广告，间谍软件借道零点击入户

安全研究披露，以色列雇佣兵间谍软件已把在线定向广告改造成投毒渠道，目标刷到特定广告即遭零点击设备入侵，研究者称这是全球首次公开证实该路径。买广告位与买攻击入口，从此可以是同一笔预算。广告投放系统本身成了攻击面，定向投放所依赖的用户画像，恰好替攻击者完成了目标筛选。

标签：`spyware` `zero-click` `mobile-security`

相关材料：
- [你刷到的一条广告，可能正在给手机装间谍软件](https://oraink.com/public/articles/87649)

订阅来源：黑鸟

#### 4. LiteLLM曝双高危漏洞：AI网关成了新靶心

奇安信深度解析开源 LLM 网关 LiteLLM 的两个高危漏洞：一把普通账号钥匙，就能打开网关大门。LiteLLM 这类网关组件常被企业用作模型调用的统一入口，集中保管各家 API 密钥与全部调用流量，一旦被打穿，丢的不是一台服务器，而是整条 AI 调用链的钥匙。修复方案已公布，低版本部署需尽快升级。

标签：`ai-security` `llm-gateway` `vulnerability`

相关材料：
- [一把普通账号钥匙，打开AI网关的大门：LiteLLM两大高危漏洞深度解析](https://oraink.com/public/articles/87379)

订阅来源：奇安信威胁情报中心

**本卷快讯**

· 黑客把法国数百家超市冷柜调到50℃，食材一夜报废（安全客）
· Palo Alto PAN-OS RCE漏洞已遭在野利用，官方已发修复（代码卫士）
· GitLab远程代码执行漏洞CVE-2026-97229，建议尽快升级（深信服千里目安全实验室）
· 微软披露3个Active Directory漏洞，可绕过防护拿下域控（看雪学院）
· 360披露Kimsuky多路径攻击，钓鱼邮件加开源仓库投毒（360威胁情报中心）
· 超六成定向攻击样本可绕过沙箱，干净报告不再等于安全（安全牛）
· 工信部通报17款违规收集个人信息的APP及SDK，限期整改（中国信息安全）
· 美政府把AI改称超级智能SI，命名权成了治理工具（网安寻路人）
· 英国AI安全研究所：前沿AI风险已前移至开发阶段（中国信息安全）
· 韩华海洋招聘启事暴露韩国核动力潜艇工程已实质推进（情报分析师）
· 研究提出AI Agent「工具发现攻击」概念，梳理四类威胁（安全分析与研究）
· 21万星逆向工具REA实测：「逆向一切」宣传有水分（吾爱破解论坛）

### 今日思考

#### 当攻击可以按需采购，防御成本还能靠人肉补丁撑多久？

**今日信号：** XBOW六天构建Chrome完整0day利用链获25万美元赏金，博思艾伦实测前沿AI最快16分钟攻入工控控制区

**灵砚视角：**  
灵砚视角：六天、25 万美元、16 分钟，三个数字把攻防剪刀差摆上台面。数世咨询的反驳其实并不矛盾——AI 赢在基础管控缺席，而非智能超群。真正的拐点是攻击边际成本趋零，而防御仍是逐台设备的手工活。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t1)

#### 当模型机密同时引来窃听器与破案AI，安全预算该向物理层还是算法层倾斜？

**今日信号：** OpenAI会议室窃听器案由自家AI模型协助侦破，35岁工程师被FBI逮捕

**灵砚视角：**  
灵砚视角：DeepSeek 藏录音器在前，OpenAI 窃听器在后，两天两案坐实物理谍战重回 AI 行业一线。耐人寻味的是闭环：偷的是模型，抓人的也是模型。会议室的四面墙，正在变成新的攻击面。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t2)


## 2. 前沿科技

### 前沿科技

**关键词：** Meta / 开源模型 / 本地部署

### 今日精要

#### 1. Meta 高调回归开源背后，前沿门槛落到两台 Mac

Meta 放出 Muse Spark Open：816B 总参、42B 激活、1M 上下文，自称美国迄今最强开源权重，训练用了 NVIDIA GB300 NVL72 集群。真正的信号在门槛——两台 M5 Ultra 就能跑，Delangue 已在两台 Mac Studio 跑通量化版；同日 NVIDIA、阶跃也放出开源权重，前沿能力被拉回本地。

标签：`Meta` `开源模型` `本地部署`

相关材料：
- [Congrats to StepFun on Step 5 Preview 🙌 Their largest open weights release. The 600B MoE model is ...](https://oraink.com/public/articles/87468)
- [And @AIatMeta went live with Muse Spark Open! The 816B model was trained on NVIDIA GB300 NVL72. Its...](https://oraink.com/public/articles/87654)
- [Today we’re releasing Muse Spark Open, the most capable US open-weight model to date. Built for cod...](https://oraink.com/public/articles/87546)
- [Muse Spark Open is available today through API platforms at Baseten, Fireworks AI, Groq, Modal, Nebi...](https://oraink.com/public/articles/87545)
- [Meta is back! https://t.co/F6draDnjfF](https://oraink.com/public/articles/87629)
- [To help make advanced models more accessible, Muse Spark Open is optimized to run on two Apple M5 Ul...](https://oraink.com/public/articles/87544)
- [Meet NVIDIA Nemotron 3.5 Super VL Our new open model combines reasoning and tool use with text, ima...](https://oraink.com/public/articles/87467)
- [Muse Spark Open is now on Ollama. @Meta's open-weight model for coding and tool use, with a 1M-toke...](https://oraink.com/public/articles/87714)
- [llama serve -hf ggml-org/Muse-Spark-Open-816B-A42B-GGUF:Q2_K (on two mac studios). Well done @fink...](https://oraink.com/public/articles/87628)

订阅来源：NVIDIA AI(@NVIDIAAI) / AI at Meta(@AIatMeta) / clem 🤗(@ClementDelangue) / ollama(@ollama)

#### 2. ChatGPT 操控 Chrome：AI 入口战烧进浏览器

OpenAI 给 Chrome 用户送上一双「手」：新扩展可读取标签页并直接操控浏览器，所有 ChatGPT 套餐用户可用，官方示例是跨页面比对三张沙发的尺寸。computer use 此前多停留在演示与开发者预览，如今成了普通用户的日常功能。而浏览器，一直是谷歌的主场。

标签：`OpenAI` `浏览器` `智能体`

相关材料：
- [A few big upgrades for Chrome users today! We’re bringing the power of computer use to anyone who us...](https://oraink.com/public/articles/87712)
- [Try using ChatGPT in Chrome for tasks like… “Compare the three couches I have open by dimensions, m...](https://oraink.com/public/articles/87713)
- [Download the Chrome extension to get started today: https://t.co/o4522imCOF Available for all Chat...](https://oraink.com/public/articles/87711)

订阅来源：ChatGPT(@ChatGPTapp)

#### 3. Figma 把代码搬上画布，设计与代码边界开始消失

Config India 大会上，Figma 把 Code Layers 开放公测：画布元素直接携带代码，Chrome 扩展可把整站代码抓回画布，Specs 给 Markdown 加上上下文，Payload 把真实数据接进 Figma Make，另有 20 家 MCP 合作方接入。设计稿正在变成可执行的构建物。当 Lovable、Cursor 从代码侧逼近，Figma 选择拆掉边界而非守城。

标签：`Figma` `设计工具` `代码`

相关材料：
- [Today at Config India, we announced new ways of building in Figma → Collab with code on the canvas ...](https://oraink.com/public/articles/87238)
- [Wake up babe the Figma Chrome extension can now capture your website code and bring into Figma as a ...](https://oraink.com/public/articles/87246)
- [We’re bringing the power of Payload into Figma → Create, build, ship with real data and content no...](https://oraink.com/public/articles/87242)
- [Announcing 20 new MCP partners at Config India (!!) Amp, ClickUp, Dia, Junie by JetBrains, Linear, ...](https://oraink.com/public/articles/87240)
- [Together at last: design and code on the canvas Code Layers are here, now in open beta Live from C...](https://oraink.com/public/articles/87247)
- [We shared a sneak peek of a new dedicated place to bring all the pieces of your design system togeth...](https://oraink.com/public/articles/87245)
- [Introducing Specs: a new medium for markdown that brings context into, out of, and across Figma AND ...](https://oraink.com/public/articles/87244)

订阅来源：Figma(@figma)

#### 4. 1/12 算力追平 DeepSeek：微软自研基座上牌桌

苏莱曼宣布 MAI 完全自研训出 3T 参数量级的最强预训练基座，并称结合缩放定律与复合效率，在留出代码集上以少 12 倍算力追平 DeepSeek-V4-Pro 级预训练表现，后训练结果稍后公布。微软不再只当 OpenAI 的分发渠道；若效率叙事成立，算力军备的账要重新算。

标签：`微软` `MAI` `训练效率`

相关材料：
- [Scaling laws, scaling... with compounding efficiency! On held-out code, we matched DeepSeek-V4-Pro-...](https://oraink.com/public/articles/87552)
- [We now have state-of-the-art pre-trained base models in the 3T-parameter weight class, built entirel...](https://oraink.com/public/articles/87553)

订阅来源：Mustafa Suleyman(@mustafasuleyman)

**本卷快讯**

· 苹果收盘市值破 5 万亿美元成全球第二家，曝国行苹果智能 12 月上线（量子位）
· DeepSeek 服务宕机超 3 小时，事后按 7 天消耗补偿用户（Geek）
· DeepSeek V4.1 Flash 在 OpenCode 免费开放使用（Geek）
· ElevenLabs 发布 Eleven v4 与 Turbo，自称八语盲测表现力最佳（ElevenLabs）
· Drama 3 Preview 登顶开放权重 TTS 榜，价格约为 Eleven v4 五分之一（Fish Audio）
· NVIDIA 发布 Nemotron 3.5 Bolt，24GB 显存即可本地部署（NVIDIA AI）
· Notion 上线 150+ MCP 连接，重构设置页统一管理工具（Notion / Akshay Kothari）
· Cognition 推出 Devin Oncall，自动排查告警与生产 bug（Cognition）
· 前华为小艺大模型负责人唐都钰创业，押注主动式物理 AI（量子位）
· 瑞典真人秀整季素材被 AI 代理误删，agent 可靠性再受质疑（Gary Marcus）
· Browser Use 发布 Photon 2.0 与 iMessage 智能体，升级 macOS 控制端（Browser Use）
· 西蒙斯基金会启动 1500 万美元项目，助数学家应对 AI 时代（Suhail）

### 今日思考

#### 前沿模型降到桌面价位后，云端 API 的溢价靠什么维持？

**今日信号：** Meta 的 816B 开源权重被量化成 GGUF 后，在两台 Mac Studio 上跑通了

**灵砚视角：**  
灵砚视角：42B 激活参数让 816B 有了消费级入口，但 Q2_K 量化的实际体验仍是未知数。真正被撬动的不是推理成本，而是分发权，谁握住本地运行时，谁拿走下一层生态。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t1)

#### 能力扩张与成本管控，谁先触到企业的天花板？

**今日信号：** OpenAI 向全员开放浏览器操控的同一天，埃森哲在收紧 AI 补贴

**灵砚视角：**  
灵砚视角：厂商把 agent 商品化的速度，快于企业验证其产出的速度。补贴退潮后留下的用量才是真实需求，管控不是终点，而是定价的开始。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t2)


## 3. 软件与开发者

### 软件与开发者

**关键词：** Vercel / 智能体平台 / 后端

### 今日精要

#### 1. Vercel 押注智能体运行时：补齐常驻进程与持久存储

Vercel 在 Ship 活动上把后端一次补齐：Python 正式 GA、容器开放、Daemons 公测让无 HTTP 服务器也能跑长驻进程，Drives 为智能体提供可挂载、可分叉的持久存储，企业侧再补上 AI 治理平台与 AWS 自带云。创始人 Rauch 把现代智能体架构概括为大脑、双手与文件三层，这家前端托管商正把自己改写成智能体运行时。当进程、状态与治理齐备，平台的收税点正从部署移向智能体生命周期。

标签：`Vercel` `智能体平台` `后端` `PaaS`

相关材料：
- [Vercel for Enterprise](https://oraink.com/public/articles/87614)
- [Python on Vercel is now generally available](https://oraink.com/public/articles/87617)
- [Backends on Vercel: Python, containers, and Daemons](https://oraink.com/public/articles/87616)
- [Introducing Vercel Drives: persistent storage for agents](https://oraink.com/public/articles/87615)
- [Vercel Daemons is now in public beta](https://oraink.com/public/articles/87619)
- [Introducing Token Pass](https://oraink.com/public/articles/87618)
- [Vercel is the Vercel for Backends](https://oraink.com/public/articles/87600)
- [Bring Your Own Cloud on AWS is now generally available](https://oraink.com/public/articles/87621)
- [I recently described the modern scalable agent architecture as: 🧠 brain, 🙌 hands, 🗃️ files. The f...](https://oraink.com/public/articles/87598)

订阅来源：Vercel News / Guillermo Rauch(@rauchg)

#### 2. 开源权重吃下 71.5% token，钱还在闭源手里

Vercel 发布 10 月 AI Gateway 生产指数：开放权重模型吃下 71.5% 的 token，却只占 23% 的支出，闭源阵营仍握着约四分之三的钱袋。另一条数字同样扎眼：近七成中国模型支出经由美国供应商结算。同日，阶跃开放 Step 5 Preview 权重、蚂蚁开源 Ling-3.1-flash、Meta 的 Muse Spark Open 上架网关，开源供给还在加码。用量侧大局已定，收入主导权的换手尚未开始。

标签：`开源模型` `Vercel AI Gateway` `生产指数` `模型经济`

相关材料：
- [Open weight takes 71.5% of tokens and 23% of spend](https://oraink.com/public/articles/87613)
- [阶跃星辰开放Step 5 Preview模型权重，蚂蚁百灵开源Ling-3.1-flash长上下文Agent模型](https://oraink.com/public/articles/87368)
- [Muse Spark Open now available on AI Gateway](https://oraink.com/public/articles/87720)

订阅来源：Vercel News / 机器之心SOTA模型

#### 3. 百万美元悬赏钓出内核零日，智能体沙箱现出裂缝

Vercel 百万美元沙箱安全挑战收官：有人提交了可突破云沙箱虚拟化边界的 Linux 内核零日漏洞，官方确认已修复，无客户数据泄露。智能体应用正把沙箱当作默认安全边界，而这层边界恰恰压在 Linux 内核这块最古老复杂的基石上。愿意为内核零日出价的，如今多了 AI 基础设施公司，悬赏买到的不是恐慌，是提前排雷的时间窗口。

标签：`云沙箱` `内核零日` `安全悬赏` `智能体安全`

相关材料：
- [This is one of the most exhilarating times in technology, and this challenge was yet another jaw-dro...](https://oraink.com/public/articles/87154)

订阅来源：Guillermo Rauch(@rauchg)

#### 4. Netflix 编码提速两三成背后，AI 工程进入交账期

Netflix 联合 JetBrains 把无头代码智能引擎接入编码智能体，实测效率提升 20%-30%、最高 65%；同一天，Meta 复盘用 AI 原生工程造出 Forum 应用，得物交出团队级 Agent 工作系统 EP-Harness，腾讯广告讲多 Agent 根因定位。四家公司不约而同开始交账：给出数字、架构与方法论，而不只是工具清单。AI 编码的叙事正从个人增效翻向组织级工程。

标签：`AI 编码` `工程效能` `Netflix` `方法论`

相关材料：
- [How Meta Built Forum With AI-Native Engineering](https://oraink.com/public/articles/87672)
- [如何从个人AI Coding到构建团队级Agent工作流？](https://oraink.com/public/articles/87314)
- [How Netflix Made AI Coding Agents More Efficient with JetBrains IDE Intelligence](https://oraink.com/public/articles/87337)
- [给270万行代码开“上帝视角”：Agent 自主定位根因实践](https://oraink.com/public/articles/87276)

订阅来源：Engineering at Meta / dbaplus社群 / The JetBrains Blog / 腾讯云开发者

**本卷快讯**

· Modal ARR 破 10 亿美元，D 轮融资 7.5 亿、投后估值 157.5 亿美元。（meng shao）
· JetBrains Java 扩展进驻 Cursor，1.0 需 Ultimate 订阅。（The IntelliJ IDEA Blog）
· Google 与 LangChain 同日发 Agent 评估指南，玄学检查退场。（Google Developers Blog / meng shao）
· 设计创造力榜发布：GPT-6 Astra 居首，仍远低于人类设计师。（meng shao）
· 开源逆向工具 REA 三天破 11 万星，软件分析门槛被拉到零。（掘金本周最热）
· Databricks 把 Qwen 微调提速 6 倍，7 小时 44 分压到 1 小时 17 分。（meng shao）
· Google OAuth 新增 DPoP：刷新令牌绑定发送方，支持多智能体委托。（Google Developers Blog）
· 群晖推送 DSM 7.4.1 安全更新，修复未公开细节的漏洞。（小众软件）
· 快手大数据加速器 Auron 毕业 Apache 孵化器，晋升顶级项目。（快手技术）
· 斯坦福新开 AI Agent 工程课 CS 329Z，聚焦智能体全栈工程。（meng shao）
· Google AI Agents 课程第五份白皮书：规格驱动开发落地。（meng shao）
· 腾讯 WorkBuddy 正式入驻企业微信，实测打通权限与上下文。（CSDN）

### 今日思考

#### 用量与收入长期背离之下，开源供给端会先撑不住，还是先找到新的税点？

**今日信号：** Vercel 生产指数：开源权重占 71.5% token、23% 支出，近七成中国模型支出经美国供应商。

**灵砚视角：**  
灵砚视角：开源已是用量侧的默认底座，但钱仍流向闭源 API 与托管网关层。值得盯的不是比例本身，而是谁在为免费的开源付账——发模型的、做托管的，还是付电费的。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t1)

#### 智能体运行时会成为新的云操作系统，还是又一门被卷平的 PaaS 生意？

**今日信号：** Vercel 一日补齐 Python、容器、Daemons 与 Drives，押注智能体运行时。

**灵砚视角：**  
灵砚视角：Vercel 赌的是智能体离不开长驻进程、持久状态与企业治理，这恰是传统 PaaS 没做好的三件事。赌对了，收税点从部署转向智能体生命周期；赌错了，就只是又一轮功能堆料。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t2)


## 4. 云计算与企业服务

### 云计算与企业服务

**关键词：** 谷歌云 / 智能体基建 / 云产品更新

### 今日精要

#### 1. 谷歌云四连更背后：云产品开始把 agent 当默认客户

谷歌云一轮更新，四件事全在为智能体让位：无边界 Lakehouse 打通 agent 跨源取数，Temporal Serverless Workers 按需预扩、闲时归零，VPC Service Controls 默认为自主智能体划安全边界，外加写给创业团队的 Gemini 智能体指南。数据、编排、安全三层都开始按「消费者是 agent」的假设重做，云厂商的竞争从模型层挪到了基建完整度——层层数齐，自建的理由就薄一层。

标签：`谷歌云` `智能体基建` `云产品更新`

相关材料：
- [Temporal Serverless Workers on Cloud Run: Scale workers ahead of demand](https://oraink.com/public/articles/87518)
- [What the Gemini agent means for startups](https://oraink.com/public/articles/87519)
- [Modernizing perimeter security: Scalable perimeters with VPC Service Controls](https://oraink.com/public/articles/87520)
- [Bringing the borderless Lakehouse into the agentic era with innovations for Gemini](https://oraink.com/public/articles/87517)

订阅来源：Google Cloud Blog

#### 2. 四厂商案例同日换剧本：企业AI从能不能讲到快不快

谷歌云、阿里、AWS、Databricks 同日晒客户案例，剧本出奇一致：滔搏用 AgentCore 把多智能体铺进数千门店，Dynata 借 AI-DLC 把 3-4 个冲刺压到 1 个，FactSet 训练部署从数天缩到数小时，Visko 30 天把实时世界模型跑上 TPU。叙事主角从「能不能」换成「多快、多广」，采购方要的证明已从能力演示变成运营指标。只是这些是厂商挑出的幸存者故事，数字要打折听。

标签：`企业AI落地` `客户案例` `规模化运营`

相关材料：
- [从单点探索到规模化运营：滔搏体育的企业级多智能体实践](https://oraink.com/public/articles/87413)
- [How Visko streams real-time world models on Google Cloud TPUs](https://oraink.com/public/articles/87516)
- [How Dynata scaled AI across the development lifecycle with AI-DLC and Kiro IDE](https://oraink.com/public/articles/87493)
- [How FactSet cut model training and deployment from days to hours with Databricks AI Runtime](https://oraink.com/public/articles/87453)

订阅来源：阿里巴巴中间件 / Google Cloud Blog / AWS Architecture Blog / Databricks

#### 3. 替你管特权的 BeyondTrust，成了间谍组织的门

谷歌云威胁情报复盘了间谍组织 ARMORY CASTLE 的完整链路：借 BeyondTrust Remote Support 的零日漏洞 CVE-2026-102764 入侵目标，且已在野外广泛利用。远程支持软件权限高、暴露面大，正坐在企业信任边界中央；昨天刚是办公室里的录音器，今天门换成了远程支持。细节已公开、波及范围未明，还在跑 BeyondTrust 的企业修复窗口正在收窄。

标签：`零日漏洞` `APT` `远程支持安全`

相关材料：
- [ARMORY CASTLE Exploits BeyondTrust](https://oraink.com/public/articles/87732)

订阅来源：Google Cloud Blog

**本卷快讯**

· Lakehouse//RT 新增空间 SQL 与空间连接，地理查询最高提速 38 倍（Databricks）
· Bolt 上线数月 ARR 达数千万美元，两位创始人周二直播答疑（bolt.new）

### 今日思考

#### 当每一层云产品都为 agent 重做，企业剩下必须自建的是什么？

**今日信号：** 谷歌云同轮更新数据、编排、安全三层，全部默认服务智能体。

**灵砚视角：**  
灵砚视角：托管选项配齐后，自建的理由会从「缺工具」退到「要差异化」，多数团队最终只守住数据与编排两层。买得越全，迁移成本越往后堆。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t1)

#### 围着 agent 重造的安全模型，会先补上还是继续漏掉为人设计的旧通道？

**今日信号：** 同一天：谷歌云给自主智能体发安全边界，间谍组织正借人的远程支持进门。

**灵砚视角：**  
灵砚视角：新的防御模型都按智能体设计，远程支持、PAM 这些为人留下的旧通道仍在原地，攻击者挑的正是改造的时间差。预算涌向 agent 边界时，最老的门反而最少人看。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t2)


## 5. 消费电子

### 消费电子

**关键词：** 苹果 / 国行 AI / 阿里巴巴

### 今日精要

#### 1. 苹果国行 AI 定档月底：Siri 缺席，阿里补位

库克确认国行 Apple Intelligence 首批核心功能 10 月底上线测试版，Siri 的 AI 升级不在首批名单，与阿里巴巴的合作方案一并披露。国行 AI 第一次同时有了日期和本土底座，外资 AI 入华从传闻阶段进入交付阶段。首批功能成色如何、阿里模型承担几分，月底测试版见真章。

标签：`苹果` `国行 AI` `阿里巴巴`

相关材料：
- [独家｜库克确认苹果国行 AI，10 月底上线测试版！](https://oraink.com/public/articles/87268)

订阅来源：爱范儿

#### 2. 折价四成仍破发：传音的 AI 故事先输一阵

有非洲之王之称的传音控股赴港上市，发行价较 A 股折价近四成，首日仍告破发；本次募资近四成投向 AI 研发，储能业务快速增长，高分红之后的折价募资引发市场对转型的讨论。折价四成换不来首日稳住，资本给硬件厂商的 AI 故事先打了折。近四成募资押向 AI，兑现节奏从此被放在放大镜下。

标签：`传音控股` `港股 IPO` `AI 转型`

相关材料：
- [上市即破发：非洲之王”不甘只做低端局 | 深网](https://oraink.com/public/articles/87340)

订阅来源：深网腾讯新闻

#### 3. 小米开源业界首个空间听觉大模型，抢跑人车家生态

小米开源 MiDashengLM-Spatial，称其为业界首个端到端空间音频理解大模型：不只听清声音，还能判断声源方位与空间关系，瞄准人车家全生态的空间智能交互。多模态竞赛的边界，正从看图识字扩到空间听觉。开源是卡位生态的打法，成色则要看车机与家居端的落地速度。

标签：`小米` `开源大模型` `空间音频`

相关材料：
- [给大模型装上“一双耳朵”：小米开源空间音频理解大模型 MiDashengLM-Spatial](https://oraink.com/public/articles/87395)

订阅来源：小米技术

#### 4. 禾赛 AI 空间相机背后：激光雷达厂转做具身数据生意

禾赛发布 Kosmo 三维世界数据引擎：手持 AI 空间相机 Kosmo One 配云平台 Kosmo World，可对现实空间做高精度可编辑重建，现阶段优先服务专业用户。具身智能缺真实世界数据，卖传感器的公司顺势开卖数据引擎。激光雷达厂商的第二曲线，正从车顶延伸到机器人。

标签：`禾赛` `具身智能` `激光雷达`

相关材料：
- [给现实世界按下复制键，禾赛做了一台「AI 空间相机」](https://oraink.com/public/articles/87432)

订阅来源：爱范儿

**本卷快讯**

· 豆包手机助手公示期结束，将逐步放开第三方应用屏幕操作权限（少数派）
· iPhone Duo 完成大模型备案，有望 12 月上线；OPPO 官宣与 Manus 合作（爱范儿）
· 少数派实测 WorkBuddy 打通企业微信：授权群聊可读，信息整理省时（少数派）
· 宝马新世代 i3 不充电跑完 1213 公里，百公里能耗 8.8 度（爱范儿）
· 微软 Surface Laptop Ultra 首发 RTX Spark，主打 AI 全能本（爱范儿）
· 华为披露十年累计 1.3 万亿研发投入，Mate 新品坚持自研路线（爱范儿）
· 谷歌在美上线 Universal Cart 智能购物车，接入搜索与 Gemini（The Keyword）
· 谷歌 Circle to Search 可识别诈骗短信，画圈即测真伪（The Keyword）
· 谷歌 SynthID 入选《时代》2026 最佳发明，AI 水印获认可（The Keyword）
· 微信上线「绿泡泡短剧」小程序，剧集免费、插播广告变现（少数派）
· 零一数科尝试用 10 人加 AI 重做原千人规模的获客业务（笔记侠）
· 笔记侠结合《造神之后》刊文，追问辛顿警示之后的 AI 治理（笔记侠）

### 今日思考

#### 搭上苹果的中国大模型，拿到的是入口还是代工单？

**今日信号：** 库克确认国行 Apple Intelligence 十月底开测，并披露与阿里的 AI 合作方案

**灵砚视角：**  
灵砚视角：阿里拿下苹果，短期是流量与背书，长期看条款——能力若只藏在系统底层，用户记住的还是 Siri 而非通义。本土底座生意的红利期，取决于苹果何时攒出自己的中国答案。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t1)

#### 物理世界的数据入口，会先被硬件厂商圈住吗？

**今日信号：** 禾赛发布 Kosmo 空间相机转向数据引擎，小米同日开源空间听觉大模型

**灵砚视角：**  
灵砚视角：具身智能卡在数据上。禾赛卖相机、小米练听觉，都在把感知能力折算成数据资产。传感器厂商离数据最近，模型公司离场景最近，中间的定价权之争才刚开场。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-16#thought-t2)

## 跨分类洞察

### 共同线索：这些更新正在汇成同一条阅读主线

网络安全、前沿科技、软件与开发者、云计算与企业服务 看似分散，但对这位用户而言都进入了同一天的阅读预算。分组先保留每个方向的独立判断，再用顶部总题把最相关的前两条主线合并成今天的个人日报入口。

> 今日 58 篇更新 → 19 条信号 + 50 条快讯，其余已替你读过

---

由 **灵砚 Oraink** 自动整理。公开版仅展示摘要、线索与观点，详细内容请跳转到服务内阅读。

<!-- latest daily content ends -->

---

## License

Content in this repository is licensed under CC BY-NC-ND 4.0 unless otherwise noted.
