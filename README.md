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

> 本期归档文件：[daily/2026/10/2026-10-23.md](daily/2026/10/2026-10-23.md)

<!-- latest daily content starts -->

# 云厂商竞逐智能体基建，AI安全与PHP在野利用同日升温

> 谷歌云亮出Agent Compute Engine，云厂商与中间件加码AI基建；另一侧，PHP2Shell在野利用与漏洞披露接连出现，AI安全与漏洞挖掘同步进入视野。加上AI制药创业融资与机器人的进展，今天适合把「建」与「防」放在一起看：基建跑得越快，安全跟得越紧。

**灵砚日报 · ORAINK DIGEST**  
2026-10-23 · 日报 · Vol. 400

- 今日处理文章：276
- 主精选条目：16
- 预计阅读：6 分钟
- 今日主线：智能体基建 / AI安全 / 在野利用 / AI制药 / 机器人

## 速览

- [PHP 暴雷第二日：GPT 挖的洞，逼出多国预防性下线](#1-php-暴雷第二日gpt-挖的洞逼出多国预防性下线)
- [DeepSeek 千亿背后，产业资本开始站队头部模型](#2-deepseek-千亿背后产业资本开始站队头部模型)
- [Vercel 六成部署出自 Agent，差距却在人不在模型](#3-vercel-六成部署出自-agent差距却在人不在模型)
- [朱啸虎看不懂的品类，Anthropic 开测了 Duet](#4-朱啸虎看不懂的品类anthropic-开测了-duet)
- [PHP2Shell第二天：在野攻击跑赢补丁](#1-php2shell第二天在野攻击跑赢补丁)
- [Tor近一成出口被控两月：匿名终点就是明文起点](#2-tor近一成出口被控两月匿名终点就是明文起点)
- [Skill木马攻破多款Agent：审查拦不住二进制](#3-skill木马攻破多款agent审查拦不住二进制)
- [ATT&CK v20扩容AI攻击，防御基线跟着重画](#4-attck-v20扩容ai攻击防御基线跟着重画)
- [Kevin Weil 入局制药：AI 创业转向科学纵深](#1-kevin-weil-入局制药ai-创业转向科学纵深)
- [腾讯字节谷歌齐出手：AI 中间件进入平台接管期](#1-腾讯字节谷歌齐出手ai-中间件进入平台接管期)
- [DeepSeek 悄悄上新 Flash：轻量型号开始收思考税](#2-deepseek-悄悄上新-flash轻量型号开始收思考税)
- [「一个人干三个人的活」：Claude Code 改写裁员经济账](#3-一个人干三个人的活claude-code-改写裁员经济账)
- [谷歌上线智能体计算引擎：云架构开始换主角](#1-谷歌上线智能体计算引擎云架构开始换主角)
- [Claude 部署选项扩容，谷歌云把对手模型当卖点](#2-claude-部署选项扩容谷歌云把对手模型当卖点)
- [连 HSM 都开源：微软把基建开放当武器](#3-连-hsm-都开源微软把基建开放当武器)
- [分层控制方案背后，微软把主权做成配置项](#4-分层控制方案背后微软把主权做成配置项)

## 本期概览

- 候选文章：约 44 篇
- 公开覆盖原文：44 篇
- 候选订阅来源：Claude(@claudeai) / Microsoft Azure Blog / 安全客 / 创业邦 / AINLP / 极客公园 / 掘金本周最热 / Latent Space
- 公开阅读入口：https://oraink.com/public/daily/2026-10-23/

## 本期如何生成

本期公开日报汇聚公众号、推特、博客等渠道的优质博主和一线团队文章；灵砚先聚合近期信源内容，再结合 AI 摘要、主题标签、来源质量与编辑规则筛选重点，最后按主题分卷整理成公开版。公开版仅展示摘要、线索与观点，不转载原文全文。

## 今日目录

1. AI与智能化：AI与智能化 — 精要 4 条 / 思考 2 个
2. 网络安全：网络安全 — 精要 4 条 / 思考 2 个
3. 前沿科技：前沿科技 — 精要 1 条 / 思考 1 个
4. 软件与开发者：软件与开发者 — 精要 3 条 / 思考 2 个
5. 云计算与企业服务：云计算与企业服务 — 精要 4 条 / 思考 2 个

## 今日主线

- 智能体基建
- AI安全
- 在野利用
- AI制药
- 机器人

## 1. AI与智能化

### AI与智能化

**关键词：** AI 安全 / 漏洞挖掘 / PHP

### 今日精要

#### 1. PHP 暴雷第二日：GPT 挖的洞，逼出多国预防性下线

PHP2Shell 风暴进入第二天，焦点从补丁覆盖率转向挖洞者：OpenAI 的 Patch the Planet 项目作为两方之一，用 GPT-5.6 Sol 挖出 PHP 核心这对潜伏约二十年的高危漏洞，波及全球 70% 网站，协调修复历时两个月。因披露提前泄密，日本首相公开催打补丁，多国政府与服务索性预防性下线。挖洞成本被 AI 压低之后，应急响应第一次跑在了补丁前面。

标签：`AI 安全` `漏洞挖掘` `PHP` `应急响应`

相关材料：
- [全球 70% 网站一夜告急，日本首相催打补丁！详解PHP暴雷事件始末](https://oraink.com/public/articles/90031)
- [AINews\] OpenAI’s Patch the Planet program is 1 of 2 parties to discover PHP2Shell vulnerabilities in core PHP affecting 70% of the web, using GPT-5.6 Sol; coordinated response over 2 months](https://oraink.com/public/articles/90012)
- [AI 到处挖漏洞一整年，终于给人类爆了个大的](https://oraink.com/public/articles/90004)
- [AI挖出藏了十几年的底层PHP漏洞，网络安全也回不去那个旧时代了。](https://oraink.com/public/articles/90017)
- [GPT挖出PHP世纪大漏洞，人类屎山代码的大清算开始了](https://oraink.com/public/articles/90158)
- [GPT 挖出 PHP 大漏洞，全球互联网连夜打补丁](https://oraink.com/public/articles/89990)

订阅来源：InfoQ 中文 / Latent Space / 极客公园 / 数字生命卡兹克 / 傅盛

#### 2. DeepSeek 千亿背后，产业资本开始站队头部模型

DeepSeek 新一轮融资约 1000 亿元人民币（约 150 亿美元），跻身中国史上最大融资之列：宁德时代、腾讯入局，完美世界、中芯聚源等产业资本跟进，资金投向模型研发、算力与具身智能，公司同步筹备科创板上市。当外部资金还在观望，产业资本已经选择直接站队头部模型公司，这笔钱也把具身智能推成了大模型公司的下一站。

标签：`DeepSeek` `融资` `产业资本` `具身智能`

相关材料：
- [DeepSeek千亿融资逼近收官：结盟完美世界、中芯聚源等产业资本，募资翻倍押注具身智能](https://oraink.com/public/articles/90058)
- [刚刚，DeepSeek在最新一轮融资中筹集了约1000亿元人民币（约150亿美元），这是中国有史以来规模最大的融资之一](https://oraink.com/public/articles/90014)

订阅来源：AI前线 / 夕小瑶科技说

#### 3. Vercel 六成部署出自 Agent，差距却在人不在模型

Vercel CEO Guillermo Rauch 披露，平台上 60% 的部署已来自 AI 编程智能体，互联网正在为 AI 重做一遍。同一天，Jellyfish 基于 447 家公司、近 5 万名工程师的数据得出反向结论：AI 模型对编码产出的影响不足 1%，个体工程师才是最大变量。智能体接管部署的同时，模型选型的权重反而在缩水，工程组织与流程成了新的胜负手。

标签：`AI 编码` `Vercel` `智能体` `工程效能`

相关材料：
- [全世界只有 5000 人见过的 AI 群控，会把软件公司的差距拉到一百倍](https://oraink.com/public/articles/90032)
- [Vercel CEO 最新爆料：60% 的部署已经来自 agent，互联网正在为 AI 重做一遍](https://oraink.com/public/articles/90018)
- [Better AI Models Won't Fix Your Engineering Team — Nicholas Arcolano, Jellyfish](https://oraink.com/public/articles/90214)

订阅来源：InfoQ 中文 / 深思圈 / AI Engineer

#### 4. 朱啸虎看不懂的品类，Anthropic 开测了 Duet

Anthropic 开放 Claude Duet 研究预览：由 Opus 5.5 驱动的主动式智能体，面向美国 Pro 与 Max 订阅用户，7×24 小时自主推进工作，不等指令先动手。中文圈同期仍在争论品类成立与否——朱啸虎直言不明白 Personal Agent 能干嘛，也有人断言「从来就没有什么 Personal Agent」。海外把「主动」做成默认产品形态，分歧本身比结论更值得盯。

标签：`Claude Duet` `Anthropic` `主动式智能体` `Personal Agent`

相关材料：
- [对话朱啸虎：不明白Personal Agent能干嘛；5亿ARR 的中国应用将批量涌现](https://oraink.com/public/articles/90065)
- [绝杀OpenAI！首个Claude Duet上岗，Opus 5.5 24 小时替你打工](https://oraink.com/public/articles/89983)
- [We’re opening a research preview of Claude Duet, a new app where Claude works as a proactive agent. ...](https://oraink.com/public/articles/89950)
- [从来就没有什么Personal Agent](https://oraink.com/public/articles/90210)

订阅来源：硅星人Pro / 创业邦 / Claude(@claudeai)

**本卷快讯**

· Character.AI 因商业模式问题破产，字节猫箱百万月活闷声盈利（创业邦）
· 成都海艺 AI 陪伴两个月流水近百万美元，AI 业务占比 45%（白鲸出海）
· 人形机器人租赁降温：日租从三万跌到两千，商户难回本（创业邦）
· 双 11 多家大模型服务商上架 token 套餐，算力生意走向消费端（网易科技）
· Uber 向全球超 3 万名员工全面部署 ChatGPT Work（OpenAI / OpenAI Blog）
· Qwen 团队开源 FlashQLA 算子库，线性注意力前后向提速 2-3 倍（InfoQ 中文）
· MiniMax M3.1 Flash 发布：ALE 榜国产第一，成本约为 Opus 十分之一（十字路口Crossing）
· 阿里提出 CODA 协议：协同进化下高分智能体反而更脆弱（阿里技术）
· 柳叶刀子刊：AI 凭人脸照片预测癌症患者死亡风险，未入临床（硅星人Pro）
· Otter.ai 融 3.2 亿美元，AI 法律创企 Legora 估值达 88 亿美元（Z Potentials / Z Potentials）
· 外滩年会上经济学家为 AI 投资失败寻对策，警示金融动荡风险（腾讯科技）
· 岩芯矩阵开源 EdgeRock-4B，单卡长推理吞吐达原模型 6.4 倍（甲子光年）

### 今日思考

#### 当挖洞成本趋近于零，两个月的协调披露窗口还守得住吗？

**今日信号：** GPT-5.6 Sol 挖出 PHP 核心双漏洞，多国政府抢在补丁前预防性下线

**灵砚视角：**  
灵砚视角：真正的变量不是漏洞，而是发现者换成了 AI。攻防时间差被压缩后，「等补丁再行动」第一次输给了「先下线再说」。协调节奏是人定的，AI 挖洞的产能不认这个节奏——预案会比补丁更早成为刚需。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-23#thought-t1)

#### 模型不再是差距来源后，AI 编码的溢价会沉淀在人身上还是流程里？

**今日信号：** Vercel 披露六成部署来自 Agent，Jellyfish 数据显示模型选型只解释 1% 产出

**灵砚视角：**  
灵砚视角：两个数字放在一起，指向同一个方向：价值正从模型层滑向工程组织层。Agent 写掉六成部署，模型好坏却只解释 1% 的产出差异，放大器始终是人。企业的采购逻辑可能要改：追新模型的预算，未必跑得赢投给工程师与流程的钱。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-23#thought-t2)


## 2. 网络安全

### 网络安全

**关键词：** PHP2Shell / 在野利用 / 漏洞披露

### 今日精要

#### 1. PHP2Shell第二天：在野攻击跑赢补丁

补丁落地次日，奇安信威胁情报中心交出 PHP2Shell 在野攻击全记录：两个潜伏 14 年的内核漏洞在披露前夕遭信息泄露，规模化利用跑在补丁前面。慢雾测算超五成加密行业域名运行 PHP，奇安信称波及千万级站点，PoC 与利用细节均已公开。厂商通告刷屏，360 把图龙锋 AI 排查免费开放——当攻击不再等补丁，修复窗口本身成了攻击面。

标签：`PHP2Shell` `在野利用` `漏洞披露` `Web3`

相关材料：
- [补丁未至，攻击先行：PHP2Shell 在野攻击全记录](https://oraink.com/public/articles/90051)
- [PHP 爆出"互联网级"高危漏洞，Web3 的"链下软肋"该怎么补？](https://oraink.com/public/articles/90135)
- [【已复现可RCE】PHP 远程代码执行漏洞(CVE-2026-109618、CVE-2026-109619)安全风险通告](https://oraink.com/public/articles/90086)
- [【已复现 RCE】php2shell：PHP Core 远程代码执行漏洞（CVE-2026-109618/109619）](https://oraink.com/public/articles/90162)
- [【已复现验证】PHP远程代码执行漏洞（CVE-2026-109618/CVE-2026-109619）](https://oraink.com/public/articles/90164)
- [【安全圈】PHP官方补丁来了！速升这4个版本](https://oraink.com/public/articles/90150)
- [75%的网站都该警惕了！PHP「php2shell」高危漏洞深度解析与修复指南](https://oraink.com/public/articles/89980)
- [免费！360开放图龙锋安全体检，帮企业排查PHP漏洞风险](https://oraink.com/public/articles/90154)

订阅来源：奇安信威胁情报中心 / 慢雾科技 / 奇安信CERT / 长亭安全课堂 / 绿盟科技CERT

#### 2. Tor近一成出口被控两月：匿名终点就是明文起点

黑鸟披露 Tor 史上最大规模节点劫持：约 11% 出口中继被提前两个月控制，潜伏期满突然发难，收割流经出口的 SSH 密码与明文邮件，植入 Ebury 后门。发难三天后才被发现，受感染节点随后全部下线，残留风险仍未排除。匿名网络的软肋不在密码学，而在出口处明文流过的每一台机器与每一位运营者。

标签：`Tor` `节点劫持` `Ebury` `匿名网络`

相关材料：
- [潜伏两月突然发难：Tor 近10%出口中继被黑客控制](https://oraink.com/public/articles/90196)

订阅来源：黑鸟

#### 3. Skill木马攻破多款Agent：审查拦不住二进制

复旦白泽战队 JADE 发布 SkillTrojan：把恶意代码藏进 Skill 二进制文件，绕过多款主流智能体框架的执行前安全审查，相关漏洞已被 CNNVD 收录，研究案例同步开源。当 Agent 的能力靠技能生态拼装、审查却只扫描文本，攻击者只需要换一种文件格式。技能市场这堂审核课，应用商店十年前就上过一遍。

标签：`Agent安全` `SkillTrojan` `复旦白泽` `CNNVD`

相关材料：
- [Skill Trojan Horse：二进制文件实现隐蔽的恶意代码注入](https://oraink.com/public/articles/90169)

订阅来源：复旦白泽战队

#### 4. ATT&CK v20扩容AI攻击，防御基线跟着重画

MITRE 发布 ATT&CK v20，扩容 AI 攻击、MFA 绕过与工控威胁的技术面，新增 15 项检测策略。全球防御者共用的威胁语言开始系统性收录 AI 战术，AI 攻击从新闻个案变成可按图索骥的常规条目。检测规则跟着框架走的企业，这周多了一批要做的升级。

标签：`ATT&CK` `MITRE` `AI攻击` `威胁情报`

相关材料：
- [MITRE ATT&CK v20 重磅更新：AI 攻击、MFA 绕过及工控威胁全面扩展](https://oraink.com/public/articles/90056)

订阅来源：数世咨询

**本卷快讯**

· GitLab 修复满分未认证 RCE，波及 12 年来所有版本，自托管速升（代码卫士）
· LiteLLM 1.107.0 遭供应链投毒，植入窃密器与后门，官方已移除（代码卫士）
· Conduent 泄露 6220 万用户数据，5.3 亿元和解待法院批准（互联网安全内参）
· 华盛顿邮报称 CIA 将中国 AI、半导体企业列为重点情报目标（天御攻防实验室）
· 联合国 AI 科学小组首发简报：失控风险已显现，现有防护不够用（信息安全国家工程研究中心）
· 网信办清朗行动整治短视频虚假人设，推动内容回归真实（中国信息安全）
· 176 号令后区域安服商承压，「平台+本地」陪跑成转型选项（安全419）
· 港科大 RedHerring 用诱饵漏洞消耗 AI 攻击资源，掩护真漏洞（安全研究GoSSIP）
· 安全牛披露 Claude Agent 四类越界案例，权限管控别靠自觉（安全牛）
· 反诈中心点名 27 款涉诈 App，艾米聊、飞舟在列，快卸载（中国信息安全）
· Meta 因数据误导行为面临 250 亿美元天价司法罚单（安全牛）
· 威胁猎人开源黑灰产黑话词典 3.0，750 条黑话免费共享（永安在线情报平台）

### 今日思考

#### 当在野利用总跑赢补丁，协调披露的时间差还是安全余量吗？

**今日信号：** 奇安信威胁情报中心今天交出 PHP2Shell 在野攻击全记录：补丁发布前已有规模化利用，披露前夕还发生信息泄露。

**灵砚视角：**  
灵砚视角：这起事件最该记住的不是 CVSS 9.2，而是时间线：攻击先于补丁抵达战场。披露前泄密、PoC 全公开、通告刷屏，说明漏洞情报的分发速度已超过修复速度。对 PHP 这类存量资产，防御方或许该把零日假设当成默认姿态。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-23#thought-t1)

#### Agent 技能生态在重演应用商店的审核战争，最后一道门该设在入口审查还是运行时隔离？

**今日信号：** 复旦白泽 SkillTrojan 把恶意代码藏进 Skill 二进制，多款主流 Agent 框架的执行前审查被整体绕过。

**灵砚视角：**  
灵砚视角：技能市场拼能力、框架只审文本，等于把移动时代的旧坑原样搬进 Agent。执行隔离正在成为生意，但入口审核与运行时沙箱缺一不可，只补一半，木马永远走另一半。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-23#thought-t2)


## 3. 前沿科技

### 前沿科技

**关键词：** AI制药 / 创业融资 / 机器人

### 今日精要

#### 1. Kevin Weil 入局制药：AI 创业转向科学纵深

Kevin Weil 等人联合创立 Warp Sciences，把 AI 和机器人用于新药研发，A 轮即融 2.15 亿美元。一家新公司首轮融资就拿到这个量级，说明资本对「AI+机器人+科学」的组合已有明确押注。通用模型的军备竞赛之外，AI 正沿着垂直纵深寻找下一个回报周期，制药是眼下注码最重的那个场景。

标签：`AI制药` `创业融资` `机器人` `AI for Science`

相关材料：
- [💥 Introducing Warp Sciences, a new company applying AI and robotics to help the world develop new m...](https://oraink.com/public/articles/90204)

订阅来源：Kevin Weil 🇺🇸(@kevinweil)

**本卷快讯**

· You.com 发布 Inference Router：企业级多模型推理，零数据留存（Richard Socher）
· Sandra Matz 在 TED 演讲：算法正收窄个人品味与探索空间（TED）
· Erum Mariam 的 TED 演讲：「游戏实验室」用玩耍疗愈难民儿童（TED）
· UBC 心理学教授谈精神病态：特质人群占比可观，且极难改变（The Diary Of A CEO Clips）

### 今日思考

#### 通用模型竞赛之外，「AI for Science」会不会成为资本和人才的下一个聚集地？

**今日信号：** Kevin Weil 宣布创立 Warp Sciences，用 AI 和机器人做新药研发，A 轮即融 2.15 亿美元。

**灵砚视角：**  
灵砚视角：A 轮 2.15 亿美元买的不是一个产品，是一个判断：AI 的下一个回报周期可能藏在实验室里。机器人补物理实验的手，模型补假设生成的脑，制药恰好两头都要。接下来值得盯的，是同类重注会不会接连出现。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-23#thought-t1)


## 4. 软件与开发者

### 软件与开发者

**关键词：** AI基建 / 云厂商 / 中间件

### 今日精要

#### 1. 腾讯字节谷歌齐出手：AI 中间件进入平台接管期

腾讯把升级后的元宝搜索以 API 形式开放，直接喊话开发者「别再自建搜索」；同一天，火山引擎发布面向 Agent 的云数据库 Lakebase，打通库与湖；谷歌 API 网关上线流式预览，不改规范即可承载 AI 负载。搜索、数据、接口三块自建件，一天之内都有了即开即用版。本周阿里云刚披露八成新增实例由 Agent 创建，需求侧已投票，供给侧跟上，开发者的自建清单一天划掉三项。

标签：`AI基建` `云厂商` `中间件`

相关材料：
- [开发者别再自建搜索了：腾讯把「AI搜索」开放了！](https://oraink.com/public/articles/90025)
- [火山引擎云数据库 Lakebase 正式发布：让 Agent 高效访问库、湖数据](https://oraink.com/public/articles/90102)
- [Streaming comes to API Gateway: real-time and AI-ready APIs, without changing your spec](https://oraink.com/public/articles/90139)

订阅来源：CSDN / 字节跳动技术团队 / Google Developers Blog

#### 2. DeepSeek 悄悄上新 Flash：轻量型号开始收思考税

DeepSeek 无预告上线 V4.1-Flash-1017，两篇独立实测结论一致：一句话能生成可玩的小游戏，能力确实上来了；但思考环节会吃掉约九成 token 预算，长输出动辄截断。另一份多场景测评给出同样纠结的画像：较旧版有提升、性价比不错，复杂任务仍落后 GPT、Claude 一档。便宜和好用之间，隔着一笔没印在价目表上的思考开销。无预告上新成常态，评测只能追着版本号跑。

标签：`DeepSeek` `模型评测` `token成本`

相关材料：
- [DeepSeek 又偷偷升级了：我实测了 V4.1-Flash-1017，一句话生成可玩游戏，但有个坑会吃掉你 90% 的预算](https://oraink.com/public/articles/90048)
- [DeepSeek 新版还是难评！](https://oraink.com/public/articles/90006)

订阅来源：掘金本周最热

#### 3. 「一个人干三个人的活」：Claude Code 改写裁员经济账

西班牙系统管理员 Nash 发帖：公司裁掉两名年薪 50 万+ 的工程师，花两小时教他用 Claude Code，年薪约 17 万的他就此接下三人的活，这笔公开的账在社区引爆讨论。同日的另一篇分享里，复旦彭鑫谈软件工程课改：AI 抽走了成长的梯子，教学须转向工程核心能力。出口在裁员，入口在改课，工程师的成长路径两头被重写——个案未必可复制，但定价逻辑已经松动。

标签：`Claude-Code` `AI就业` `软件工程教育`

相关材料：
- [AI抽走了成长的梯子，软件工程课该怎么教？](https://oraink.com/public/articles/90123)
- [公司裁掉两个年薪50+万元工程师，花2小时教他用Claude Code「接盘」：“我年薪17万，一个人干三个人的活！”](https://oraink.com/public/articles/90023)

订阅来源：CodeWisdom / CSDN

**本卷快讯**

· 词元星火发 Spark-X2.6-4B 编程模型，Anthropic 推 Claude Duet 主动 Agent（机器之心SOTA模型）
· JetBrains 发布 Air Governance：组织级管理 AI Agent 权限与开销（The JetBrains Blog）
· 谷歌 Project Chrysalis 智能体平台实测：自演进 Agent 1.8 秒修复生产中断（Google Developers Blog）
· 开发者抓包 72 小时辟谣：手机没偷听，精准推荐另有技术（掘金本周最热）
· 开源 Laya 对标闭源 Jev：单问 33 毫秒，快 6-7 倍靠微调（腾讯云开发者）
· freeCodeCamp 推免费 MCP 安全课：覆盖 OWASP Top 10，可获证书（freeCodeCamp.org）
· 阿里云实践：大模型安全检测从单点识别走向全流程体系（网络安全回收站）
· Spring Batch 发 6.1.0-RC1 与 6.0.6：API 重构加性能优化（Spring Blog）
· Vercel Pro 免费域名再添 8 个顶级域，合格后缀增至 16 个（Vercel News）
· JS 周刊关注：TypeScript 的 Rust 移植版最高提速 8 倍（印记中文）
· MiniMax H3 可本地部署：5090 加 ComfyUI 完整教程出炉（掘金本周最热）
· 1024 程序员日深圳专场 22-24 日举办，聚焦大模型到端侧 AI 实战（CSDN）

### 今日思考

#### 当经验可以靠两小时培训和一款工具补位，企业还会为资深付溢价吗？

**今日信号：** 公司裁掉两名年薪 50 万+ 工程师，花 2 小时教年薪 17 万的管理员用 Claude Code 接盘三人工作量

**灵砚视角：**  
灵砚视角：这是当事人的单方陈述，细节无从复核，传播价值大于实证价值。但它能火，说明读者默认这套账算得通。真正的信号不是裁了几个人，而是裁员决策里第一次出现了「AI 可补位」这个默认项。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-23#thought-t1)

#### 地基被平台预制后，开发者的护城河应该建在哪一层？

**今日信号：** 腾讯开元宝搜索 API、字节发 Lakebase、谷歌网关上流式，三朵云一天内补齐 AI 中间件

**灵砚视角：**  
灵砚视角：本周早些时候，阿里云披露八成新增数据库实例由 Agent 创建，那是需求侧投票；今天三家同天把搜索、库、网关做成即开即用，是供给侧跟进。自建正从能力证明变成成本负担，但平台化的另一面是新绑定。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-23#thought-t2)


## 5. 云计算与企业服务

### 云计算与企业服务

**关键词：** 谷歌云 / Agent Compute Engine / 智能体基建

### 今日精要

#### 1. 谷歌上线智能体计算引擎：云架构开始换主角

谷歌发布 Agent Compute Engine，为智能体时代重造计算底座：专用算力、安全架构、治理内建，官方直言传统计算架构已不敷使用。同一波更新里，治理能力跨环境扩展，Knowledge Catalog 的自学习上下文进入预览，智能体的知识不再靠人工维护。微软同日发文，谈云原生基础如何随智能体演进。两大云不约而同把智能体立为架构的第一约束，工作负载的主角正在换人。

标签：`谷歌云` `Agent Compute Engine` `智能体基建`

相关材料：
- [Introducing Agent Compute Engine and expanded agent governance](https://oraink.com/public/articles/90134)
- [Inside Agent Compute Engine: Building the compute foundation for the agentic era](https://oraink.com/public/articles/90133)
- [Introducing new self-learning context enrichment in Knowledge Catalog](https://oraink.com/public/articles/90160)
- [Evolving the cloud-native foundation for the next generation of AI](https://oraink.com/public/articles/89966)

订阅来源：Google Cloud Blog / Microsoft Azure Blog

#### 2. Claude 部署选项扩容，谷歌云把对手模型当卖点

继 OpenAI 三模型上架之后，谷歌云今天把 Anthropic 管理的 Claude 部署选项做成正式可用，新增两种部署方式供企业选择。对手模型接连进入自家货架，谷歌云的卖点正从自家模型转向底座本身：当模型在哪都能跑，竞争回到算力、数据与治理层。

标签：`谷歌云` `Claude` `Anthropic` `模型托管`

相关材料：
- [Expanding Claude availability and deployment choice on Google Cloud](https://oraink.com/public/articles/90220)

订阅来源：Google Cloud Blog

#### 3. 连 HSM 都开源：微软把基建开放当武器

OCP 全球峰会上，微软联合多家机构推出开源集成 HSM 项目 Project Tessera，直面 AI 与量子时代的密钥安全；同一波还开放新一代芯片、网络、电力与冷却规范，并详解第三代推理加速器 Maia 300。三天前谷歌刚开源 NPU，开放正从模型层卷进机房，成为超大规模厂商的竞争姿势。

标签：`微软` `OCP` `开源硬件` `Project Tessera`

相关材料：
- [Infrastructure for the frontier era: Scaling intelligence through open industry collaboration](https://oraink.com/public/articles/89969)
- [Advancing hardware security with open-source Integrated HSM technology](https://oraink.com/public/articles/89968)
- [Deep dive into Azure Maia 300 architecture](https://oraink.com/public/articles/89970)

订阅来源：Microsoft Azure Blog

#### 4. 分层控制方案背后，微软把主权做成配置项

微软给主权云做阶段性更新：分层控制方案让企业按工作负载选择技术控制权，另与英特尔共建从边缘到云的主权 AI 共享底座。两天前谷歌刚集齐主权 AI 产品目录，主权正从政治承诺细化成可采购的工程配置，两大云开始在同一赛道比交付。

标签：`微软` `主权云` `英特尔` `主权 AI`

相关材料：
- [Advancing digital sovereignty with greater control and choice](https://oraink.com/public/articles/90011)
- [Designing for sovereign AI: A shared foundation from edge to cloud](https://oraink.com/public/articles/89964)

订阅来源：Microsoft Azure Blog

**本卷快讯**

· 微软联手英伟达发布开放权重模型风险白皮书，给企业部署开源模型定分级管控框架（Microsoft Azure Blog）
· AWS 用 AgentCore 做医疗编码：规则优先，AI 兜底（AWS Architecture Blog）
· 阿里公开工单分诊智能体实践，AgentScope Java 跑通开发到协作（阿里巴巴中间件）
· 微软获评 2026 Gartner 服务器虚拟化领导者，多环境一致性成核心需求（Microsoft Azure Blog）

### 今日思考

#### 智能体会不会像当年的容器一样，成为新的基础部署单元？

**今日信号：** 谷歌为智能体单开计算层，微软同日发文谈云原生为智能体演进

**灵砚视角：**  
灵砚视角：智能体正在争取部署单元的地位，类似容器之于虚拟机。差别在于它自主发起调用、长时驻留、跨系统穿行，为人类请求设计的配额、隔离与计费未必扛得住。谷歌抢先立框架，微软同日表态，赌注是未来云上的大头算力由智能体消耗。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-23#thought-t1)

#### 硬件都开放之后，云厂商的锁定会转移到哪一层？

**今日信号：** 微软在 OCP 开源 HSM、公开基建规范，谷歌三天前刚开源 NPU

**灵砚视角：**  
灵砚视角：开放规范压低迁移成本，锁定正从硬件层上移到软件栈与运营层。微软说开放是为了让 AI 更普及可负担，但选在谷歌开源 NPU 之后跟进，节奏本身就是竞争信号。下一个看点，是谁的开放规范先长成事实标准。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-10-23#thought-t2)

## 跨分类洞察

### 共同线索：这些更新正在汇成同一条阅读主线

AI与智能化、网络安全、前沿科技、软件与开发者 看似分散，但对这位用户而言都进入了同一天的阅读预算。分组先保留每个方向的独立判断，再用顶部总题把最相关的前两条主线合并成今天的个人日报入口。

> 今日 44 篇更新 → 16 条信号 + 44 条快讯，其余已替你读过

---

由 **灵砚 Oraink** 自动整理。公开版仅展示摘要、线索与观点，详细内容请跳转到服务内阅读。

<!-- latest daily content ends -->

---

## License

Content in this repository is licensed under CC BY-NC-ND 4.0 unless otherwise noted.
