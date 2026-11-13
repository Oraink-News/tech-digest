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

> 本期归档文件：[daily/2026/11/2026-11-13.md](daily/2026/11/2026-11-13.md)

<!-- latest daily content starts -->

# 英伟达与零日漏洞同日升温，AI的扩张与防护正在并行推进

> 英伟达与黄仁勋的消息今天同时落在前沿科技与消费电子两个版面，安全侧零日漏洞披露与RMM成为焦点，开发者与云计算版面则从Claude Code、数据泄露一路排到AI代理与AI治理——AI跑得多快，安全与治理的议题就贴得多近。

**灵砚日报 · ORAINK DIGEST**  
2026-11-13 · 日报 · Vol. 440

- 今日处理文章：667
- 主精选条目：17
- 预计阅读：6 分钟
- 今日主线：零日漏洞 / 英伟达 / AI安全 / AI治理

## 速览

- [30 个零日无预警公开背后，修复拖延开始被清算](#1-30-个零日无预警公开背后修复拖延开始被清算)
- [补天、字节给 AI 测试立规，白帽责任落到人头](#2-补天字节给-ai-测试立规白帽责任落到人头)
- [雪球行动四次改道得手：阻断式防御开始失灵](#3-雪球行动四次改道得手阻断式防御开始失灵)
- [假局长骗走 OpenAI 高管 17 分钟，前沿输给老骗术](#4-假局长骗走-openai-高管-17-分钟前沿输给老骗术)
- [黄仁勋即刻卸任，2500 亿 OpenAI 兜底案生变](#1-黄仁勋即刻卸任2500-亿-openai-兜底案生变)
- [IPO 前夜，礼来主席驳 Dario：造药叙事遭业内反噬](#2-ipo-前夜礼来主席驳-dario造药叙事遭业内反噬)
- [Carbon 次日，谷歌发 Hydrogen 按场景分层](#3-carbon-次日谷歌发-hydrogen-按场景分层)
- [Atlas 全量开放背后，世界模型在变成创作工具](#4-atlas-全量开放背后世界模型在变成创作工具)
- [Claude Code 泄露数千密钥，便利即漏洞](#1-claude-code-泄露数千密钥便利即漏洞)
- [百度开词元所：模型接入层成了新战场](#2-百度开词元所模型接入层成了新战场)
- [Harbor 曝光背后，苹果押注本地大模型推理](#3-harbor-曝光背后苹果押注本地大模型推理)
- [55 次操作零失误，桌面 Agent 不看屏幕了](#4-55-次操作零失误桌面-agent-不看屏幕了)
- [谷歌、阿里、AWS同日出手，Agent治理摆上货架](#1-谷歌阿里aws同日出手agent治理摆上货架)
- [英伟达33年来首次换帅，黄仁勋时代即刻落幕](#1-英伟达33年来首次换帅黄仁勋时代即刻落幕)
- [豆包工作接入DeepSeek：办公入口收编模型层](#2-豆包工作接入deepseek办公入口收编模型层)
- [苹果松绑之后，实测Siri仍够不着AI手机](#3-苹果松绑之后实测siri仍够不着ai手机)
- [「现在，只是刚刚开始」：闫俊杰把推理成本当护城河](#4-现在只是刚刚开始闫俊杰把推理成本当护城河)

## 本期概览

- 候选文章：约 48 篇
- 公开覆盖原文：48 篇
- 候选订阅来源：Gary Marcus(@GaryMarcus) / 爱范儿 / Amjad Masad(@amasad) / meng shao(@shao__meng) / 小众软件 / 灾难控制局 / Suhail(@Suhail) / Justine Moore(@venturetwins)
- 公开阅读入口：https://oraink.com/public/daily/2026-11-13/

## 本期如何生成

本期公开日报汇聚公众号、推特、博客等渠道的优质博主和一线团队文章；灵砚先聚合近期信源内容，再结合 AI 摘要、主题标签、来源质量与编辑规则筛选重点，最后按主题分卷整理成公开版。公开版仅展示摘要、线索与观点，不转载原文全文。

## 今日目录

1. 网络安全：网络安全 — 精要 4 条 / 思考 2 个
2. 前沿科技：前沿科技 — 精要 4 条 / 思考 2 个
3. 软件与开发者：软件与开发者 — 精要 4 条 / 思考 2 个
4. 云计算与企业服务：云计算与企业服务 — 精要 1 条 / 思考 1 个
5. 消费电子：消费电子 — 精要 4 条 / 思考 2 个

## 今日主线

- 零日漏洞
- 英伟达
- AI安全
- AI治理

## 1. 网络安全

### 网络安全

**关键词：** 零日漏洞 / 漏洞披露 / RMM

### 今日精要

#### 1. 30 个零日无预警公开背后，修复拖延开始被清算

因上报漏洞迟迟未获修复，一名研究员无预警公开 N-central 平台的 30 余个零日并放出 PoC，N-able 被迫下线全球托管环境、建议自部署客户离线，并紧急推送热修复。先报后修的行业默契被撕开：当修复进度追不上公开的速度，下线成了安全厂商最直接的止损。目前攻击者已开始探测暴露目标。

标签：`零日漏洞` `漏洞披露` `RMM`

相关材料：
- [N-able 紧急发布多个 0day 漏洞的热修复方案](https://oraink.com/public/articles/99453)
- [安全厂商主动关闭服务：30多个零日漏洞让远程管理平台紧急下线](https://oraink.com/public/articles/99458)

订阅来源：代码卫士 / 数世咨询

#### 2. 补天、字节给 AI 测试立规，白帽责任落到人头

补天联合 18 家跨行业 SRC 发布《SRC行业授权资产安全测试规范-Agent版》，明确 AI Agent 参与授权测试的合规边界与责任归属；字节 ByteSRC 推出 AGENTS.md 前置约束配置，要求高风险场景提前报备。「使用 AI 不构成测试免责理由」写进补天通告，ByteSRC 也以处罚案例划出同一底线。落地动作随之而来：补天公示 3 起越界测试处置，ByteSRC 公布多起 AI 越界处罚。

标签：`ai-agent` `SRC` `安全合规`

相关材料：
- [ByteSRC发布《AI 辅助安全测试 AGENTS.md》指引及违规白帽处罚公告](https://oraink.com/public/articles/99654)
- [关于使用AI辅助安全测试规范及违规白帽处置的通告](https://oraink.com/public/articles/99437)
- [联合发布｜《SRC行业授权资产安全测试规范-Agent版》及配套使用手册](https://oraink.com/public/articles/99436)

订阅来源：字节跳动安全中心 / 补天平台

#### 3. 雪球行动四次改道得手：阻断式防御开始失灵

奇安信复盘 Malbear Labs 披露的「雪球行动」：攻击者基于 DeepSeek Flash 搭建智能体框架执行自主入侵，四次被防御阻断后均自动分析原因、更换路径，最终完成目标。与本周比拼规模的智能体攻击不同，这次的关键是自适应：会改道的攻击让单点拦截开始失灵；灾难控制局同日主张反入侵体系向三层演进、主机侧重回核心。希坦实验室复盘 Hugging Face 越权案则显示，攻击者已尝试渗透 CI 流水线并持久化驻留。

标签：`ai-security` `ai-agent` `威胁情报`

相关材料：
- [四次阻断，四次改道：AI 自主入侵已经走到哪一步](https://oraink.com/public/articles/99431)
- [第179篇：AI智能体失控自动化入侵Hugging Face案例分析（下篇）](https://oraink.com/public/articles/99475)
- [对未来反入侵体系与产品的思考](https://oraink.com/public/articles/99288)

订阅来源：奇安信威胁情报中心 / 希潭实验室 / 灾难控制局

#### 4. 假局长骗走 OpenAI 高管 17 分钟，前沿输给老骗术

俄罗斯恶作剧组合伪装成乌克兰对外情报局长，经乌外交官牵线，同 OpenAI 三名涉国家安全业务高管开了 17 分钟视频会，套出 AI 军事化与对乌合作的敏感口径。模型护栏再高，也拦不住一封伪造的会议邀请：这次被穿透的，是 OpenAI 在人员身份核验与社会工程学防护上的核心漏洞。

标签：`社会工程` `OpenAI` `ai-security`

相关材料：
- [OpenAI三位高管与假的乌克兰情报局长在摄像头前聊了17分钟](https://oraink.com/public/articles/99678)

订阅来源：黑鸟

**本卷快讯**

· 4837 个被盗 GitHub 账号向 8093 仓库推送窃密脚本，1806 个仓库泄露凭据（安全圈）
· 7-Zip LZX 解码器堆越界写入漏洞已复现，低于 26.06 的版本需升级（奇安信CERT / 微步在线研究响应中心）
· Apache mod_http2 爆 9.8 分未授权 RCE，2.4.55 至 2.4.70 受影响需升级（安全圈）
· ScreenConnect 三方扩展空密钥漏洞遭 SCKit 蠕虫利用，48 家机构沦陷（安全圈）
· Zoom Workplace 修复两个未认证远程提权漏洞，最高 CVSS 9.6（代码卫士）
· Remus Stealer 月费千美元开卖，宣称改密码后仍可访问 Gmail，未经独立验证（看雪学院）
· 菲律宾证监会泄露用户信息，同期十余个政府机构接连中招（互联网安全内参）
· 中国移动网安竞赛首次纳入智能体自主攻防，CCF 智能挑战赛 15 日开赛（长亭科技 / XCTF联赛）
· 360 漏洞云首批签署工信部《网络产品安全漏洞收集平台自律公约》（360漏洞云）
· 「系统总裁」装机封装工具被曝默认篡改浏览器主页，且无关闭选项（火绒安全实验室）
· 美军工关联企业 ILC 因网安合规造假被诉，支付 1300 万美元和解（互联网安全内参）
· 阿里等发布 158 页安全大模型综述：领域正走向交互任务执行（安全学术圈）

### 今日思考

#### 当私下报告换不来修复，「公开引爆」会不会成为研究员的常规武器？

**今日信号：** 研究员因上报漏洞未获修复，无预警公开 30 余个带 PoC 的零日，N-able 全球下线托管服务

**灵砚视角：**  
灵砚视角：先报后修的前提是「修」会兑现。当上报被当成免费情报、修复排到下个季度，PoC 就会从沟通筹码变成武器。N-able 用下线自证了拖延的代价，接下来要看其他厂商会不会把及时修复重新当成生存问题。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-13#thought-t1)

#### 攻击会自动换路时，以拦截为单位的防御逻辑还成立吗？

**今日信号：** 「雪球行动」中智能体四次被阻断、四次自动改道完成入侵

**灵砚视角：**  
灵砚视角：阻断式防御默认攻击路径有限，堵住即赢。自适应攻击拆掉了这个前提：对手的备选路径由模型实时生成，防御方却还在人工排障。对抗的不对称正从算力转向迭代速度，蜜罐、假目标这类消耗型手段，可能比再加一层拦截更值得投入。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-13#thought-t2)


## 2. 前沿科技

### 前沿科技

**关键词：** 英伟达 / 黄仁勋 / OpenAI

### 今日精要

#### 1. 黄仁勋即刻卸任，2500 亿 OpenAI 兜底案生变

英伟达宣布黄仁勋辞任 CEO、即日生效，CFO 克雷斯临时接棒并继续兼任原职，董事会已启动内外部搜寻。关键变量在人事之外：克雷斯曾反对黄仁勋力推的 OpenAI 2500 亿美元信用兜底方案，她的上台让这笔承诺首先面临重估。Lex Fridman 称此举堪比苹果解雇乔布斯，Delangue 则力挺英伟达的分布式领导模式。Gary Marcus 提醒市场：该为「循环融资制造需求」的终结定价了。

标签：`英伟达` `黄仁勋` `OpenAI` `公司治理`

相关材料：
- [Sad but still bullish on @nvidia! I’m seeing a lot of people criticizing its structure and the lack...](https://oraink.com/public/articles/99832)
- [Worth a read.](https://oraink.com/public/articles/99398)
- [黄仁勋辞去英伟达 CEO 一职，立即生效，CFO 科莱特·克雷斯（Colette Kress）临时接任。 克雷斯任临时 CEO，同时继续兼 CFO，直到找到正式继任者，董事会已启动内外部搜寻。 感...](https://oraink.com/public/articles/99642)
- [Everyone defending Jensen is trying to make it about the sex. It’s not about the sex. It’s about ...](https://oraink.com/public/articles/99513)
- [There should be a rule on boards that you do not make any moves on CEO for 2 weeks after a PR crisis...](https://oraink.com/public/articles/99320)
- [one of Trump’s less crazy ideas. i doubt Cook would want the job but he knows chips (to some degree)...](https://oraink.com/public/articles/99652)
- [a new sheriff is in town and things may be very different](https://oraink.com/public/articles/99839)
- [Why are old stories that were not even covered up all that well become sudden international and geop...](https://oraink.com/public/articles/99252)
- [🔥](https://oraink.com/public/articles/99290)
- [NVIDIA letting Jensen go is a huge mistake, for America and for humanity. It's Apple firing Steve Jo...](https://oraink.com/public/articles/99808)

订阅来源：clem 🤗(@ClementDelangue) / Amjad Masad(@amasad) / Geek(@geekbb) / Gary Marcus(@GaryMarcus) / Suhail(@Suhail)

#### 2. IPO 前夜，礼来主席驳 Dario：造药叙事遭业内反噬

CUDA 移植的热度未散，Anthropic 的 IPO 叙事先撞上了懂行的人。礼来主席联合多位资深医学研究者公开反驳 Dario：新药临床周期 5-8 年、可用生物数据不足 1%，AI 带来的是稳步增量而非爆发。Gary Marcus 把路演演讲比作 Elizabeth Holmes，Suhail 也公开质疑其全赛道竞争传闻的真实性。再叠加 Opus 5.5 超 100 亿美元开发成本的消息，市场开始追问这套叙事有多少能兑现。

标签：`Anthropic` `IPO` `生物医药`

相关材料：
- [Chair of @EliLillyandCo joins the chorus of people who know something about biology who say that Dar...](https://oraink.com/public/articles/99519)
- [People are openly mocking Dario’s bullshit.](https://oraink.com/public/articles/99324)
- [Dario acting like Elizabeth Holmes during the same week in which Jensen committed professional suici...](https://oraink.com/public/articles/99512)
- [it’s a a really bad sign for the long term health is Anthropic that Dario basically lied his ass off...](https://oraink.com/public/articles/99296)
- [for marginal returns that won’t matter to most customers next time. for a model with a shelf life ...](https://oraink.com/public/articles/99515)
- [Nobody should be surprised by this. This is why I started Particle—there must be an answer to taxing...](https://oraink.com/public/articles/99321)
- [one of the many reasons that biology is hard and why claims like Dario makes are utterly unrealistic](https://oraink.com/public/articles/99789)
- [dario’s ipo speech was as full of shit as anything elizabeth holmes ever said some investors never...](https://oraink.com/public/articles/99222)

订阅来源：Gary Marcus(@GaryMarcus) / Suhail(@Suhail)

#### 3. Carbon 次日，谷歌发 Hydrogen 按场景分层

Carbon 攻坚高难度问题的定位刚立住，谷歌今天就给 Gemini 4 系列补上另一档：Hydrogen 主打日常编码与智能体工作流的速度效率，向消费者、开发者与企业分层开放，还能秒级把自然语言变成可运行的交互式代码。Cognition 随即在 Devin 接入该模型并给出参照：FrontierCode 2.0 得分 38.2%，仅次于 GPT-6.1 Sol。旗舰正在从单一模型变成一条产品线，场景覆盖接棒单点跑分。

标签：`谷歌` `Gemini 4` `Hydrogen` `模型分层`

相关材料：
- [Today, we’re growing the Gemini 4 model series by introducing Gemini 4 Hydrogen. While Gemini 4 Car...](https://oraink.com/public/articles/99764)
- [Available starting today: — Consumers: use it in the @GeminiApp and Google Search for all users, and...](https://oraink.com/public/articles/99763)
- [Gemini 4 Hydrogen is now live in Devin Desktop and Devin CLI. On FrontierCode 2.0, our benchmark th...](https://oraink.com/public/articles/99748)
- [Beyond knowledge work, Hydrogen brings that same speed and first-pass accuracy to live coding by tur...](https://oraink.com/public/articles/99762)

订阅来源：Google AI(@GoogleAI) / Cognition(@cognition_labs)

#### 4. Atlas 全量开放背后，世界模型在变成创作工具

李飞飞团队的世界模型 Atlas 今日面向所有用户开放，同步上线应用与 API，支持从 3D 创意生成关键帧、视频和 3D 高斯泼溅类资产。另一边，Justine Moore 用 Fable 5.2 不到一小时搭出能在浏览器以 200fps 运行的手绘风虚拟世界，还能交给智能体随手改写。两款独立工具接连把「可无限重混的虚拟世界」推向普通创作者，3D 内容的生产成本曲线开始下探。

标签：`世界模型` `李飞飞` `Atlas` `3D 生成`

相关材料：
- [Man it’s so cool that we now have endlessly remixable virtual worlds. I cloned this and asked my ag...](https://oraink.com/public/articles/99357)
- [Atlas is now available to everyone!! I’m very excited to see what users can build with our newest wo...](https://oraink.com/public/articles/99786)

订阅来源：Justine Moore(@venturetwins) / Fei-Fei Li(@drfeifei)

**本卷快讯**

· ChatGPT dot 更新：回复提速、少说术语，新增自定义指令配置（ChatGPT）
· Grok Bot 1.0 发布：定位 AI 队友，可驻 Slack 绑 HeyGen 数字人（eric zakariasson / HeyGen）
· ElevenLabs 开 Marketplace 并推伙伴计划：44 国 550 家认证伙伴（ElevenLabs）
· Figma 公测 3D Transforms：三轴旋转编辑，可经 MCP 接编码代理（Figma）
· Runway 上线 3D 生成：Tripo H3.1 支持文/图生 3D 模型与跨工具导出（Runway）
· Fish Audio 推无代码语音智能体平台 Fish Agent，中位部署仅 32 秒（Fish Audio）
· Browser Use 集成 1Password：智能体登录网站全程不碰明文密码（Browser Use）
· Recraft 上线四款 MiniMax H3 模型：2K/4K 图像加 4-15 秒短视频（Recraft）
· MAI Transcribe 2 周转录 850 万次，语音转文本请求涨 3 倍（Mustafa Suleyman）
· Naval 引数据：中国 100MW 数据中心造价不足 3 亿美元，仅为美国 1/5（Naval）
· 统计称 AI 编码智能体约四分之三任务仍需人工清理，距 AGI 自主尚远（Gary Marcus）
· 腾讯 WorkBuddy 被指暗调积分折算标准并降速，积分计费遭用户抵制（Geek）

### 今日思考

#### 兜底案若被重审，AI 算力需求里还剩多少是自发订单？

**今日信号：** 英伟达公告黄仁勋辞任即日生效，曾反对 2500 亿 OpenAI 兜底案的克雷斯出任临时 CEO

**灵砚视角：**  
灵砚视角：黄仁勋既是算力供给方，也是需求叙事最大的推销员，循环融资撑起的订单在他离场后失去最大背书。接下来盯两件事：OpenAI 的承诺是否重谈，云厂商的资本开支指引是否下修。换帅是噪音，重定价才是信号。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-13#thought-t1)

#### 去掉造药叙事，Anthropic 的 IPO 还剩多少溢价？

**今日信号：** 礼来主席联合多位医学研究者，公开反驳 Dario 的生物医药落地时间表

**灵砚视角：**  
灵砚视角：业内反驳戳的不是 AI 能力，而是时间表，临床周期 5-8 年写不进季报。若质疑持续发酵，估值叙事或被迫从疾病攻克回摆到可验证的编码收益上。路演押注的口径，就是日后回撤的口径。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-13#thought-t2)


## 3. 软件与开发者

### 软件与开发者

**关键词：** ai-security / claude-code / data-leaks

### 今日精要

#### 1. Claude Code 泄露数千密钥，便利即漏洞

安全研究人员发现，Claude Code 的权限保存机制与 Git 防护规则存在设计缺陷：开发者点下「以后不再询问」后，携带密码与 API Key 的配置文件被批量推上公开 GitHub，数千条敏感凭证就此裸奔。Anthropic 已回应优化方案并给出自查指引。在 Agent 安全事件连日的这一周，这次泄露指向更结构性的问题——为减少打断而生的便利设计，正在替攻击者省掉最后一道确认。

标签：`ai-security` `claude-code` `data-leaks`

相关材料：
- [点一下「以后不再询问」，密码、API Key全被上传！Claude Code配置文件泄露数千条敏感信息，Anthropic回应](https://oraink.com/public/articles/99425)

订阅来源：CSDN

#### 2. 百度开词元所：模型接入层成了新战场

百度世界 2026 上，李彦宏宣布推出模型聚合平台「词元所」（Token Exchange），同期百度还发布了 ERNIE 5.5 Flash 预览版。词元所主打可信属性，上线一个月接入超百个模型，日均调用量超过 5000 万。独立观察者评价直白：这更像一座改名的模型中转站，差异化还没做出来。同期讨论印证了赛道热度：企业为压缩 token 成本普遍改走中转站，Langfuse 的 AI Gateway 开启公测，OpenRouter 之外的可选项还在增多。

标签：`baidu` `token-exchange` `ai-infra`

相关材料：
- [剥开 Agent 所有的伪装，最后只剩下赤裸裸的 Token ... 任 Prompt Engineering、Context Engineering、Harness Engineering、Loo...](https://oraink.com/public/articles/99258)
- [百度发布ERNIE 5.5 Flash Preview，NexAGI开放Nex-N2.6权重，Google扩大Gemini 4 Carbon开放范围](https://oraink.com/public/articles/99561)
- [百度创始人李彦宏在百度世界 2026 开幕式上，宣布正式推出「Token Exchange - 词元所 - 模型的交易所」 看了词元所网站，应该就是百度的模型 + 国内开源模型（文本、图像和音视频）...](https://oraink.com/public/articles/99498)

订阅来源：meng shao(@shao__meng) / 机器之心SOTA模型

#### 3. Harbor 曝光背后，苹果押注本地大模型推理

有爆料称苹果正在开发名为 Harbor 的应用：通过 Thunderbolt 5 把多台 Apple Silicon Mac 连成本地推理集群，绕开单机内存限制运行大模型，目前挂在 Claris 品牌下做私人预览，初期或面向企业与开发者。相比 Siri 与模型功能，这次苹果露出的是基础设施层的野心：Mac 不只是终端，还可以是可拼接的算力单元。爆料尚未获得官方回应，Harbor 也没有公开时间表。

标签：`apple` `harbor` `local-inference`

相关材料：
- [苹果新应用 Harbor 曝光](https://oraink.com/public/articles/99266)

订阅来源：小众软件

#### 4. 55 次操作零失误，桌面 Agent 不看屏幕了

Vercel Labs 开源桌面控制工具 agent-desktop 1.2.0，交出实测成绩：不截图、不占用鼠标键盘，直接读取系统无障碍树操作界面，连点 55 次计算器零失误。另一边，豆包工作 Agent 已在承接电脑体检、磁盘清理、故障排查这类日常维护。桌面 Agent 的路线正在分岔：一边让模型看懂像素，一边让软件交出结构，后者是在给机器用户另开通道。实测同时也划出了当前版本的适用边界。

标签：`ai-agent` `agent-desktop` `desktop-automation`

相关材料：
- [实测 agent-desktop：AI 控制桌面不截图、不占鼠标键盘，连点 55 次计算器 0 失误](https://oraink.com/public/articles/99510)
- [把电脑体检、清理交给豆包工作 Agent 。](https://oraink.com/public/articles/99463)

订阅来源：掘金本周最热 / 逛逛GitHub

**本卷快讯**

· 掘金作者付费实测 Qwen4 旗舰：性能不及宣传、速度慢成本高（掘金本周最热）
· Gemini 4 Hydrogen 登陆 Vercel AI Gateway（Vercel News）
· 谷歌 AAD 监控 Agent 异常：87% 检出有害指令，零运行时延迟（Google Developers Blog）
· 微软经典工具 Process Explorer 登陆 macOS 并开源（小众软件）
· 因用户流向修改版，Surge 测试版加入 VLESS 与 REALITY（小众软件）
· Vercel 发布面向 Agent 的 UI SDK，不限制 UI 生成自由（Guillermo Rauch）
· Makepad 开源 Relax，Rust 改函数秒级见效、进程不重启（觉学社）
· 复旦伏羲内核模糊测试：覆盖率平均提升 17.2%，效率 6.4 倍（CodeWisdom）
· Grok Bot 十天前已升至 v1.0：加入多人协作与工具集成（meng shao）
· Flutter 3.50 与 Dart 3.14 同发，主打架构解耦与跨端性能（掘金本周最热）
· Observe.AI 重分片 50TB 生产数据，业务几乎无中断（MongoDB Blog）
· 京东落地 AI 测试后周期诊治体系，破解 Vibe Coding 越快越乱（京东技术）

### 今日思考

#### 当便利功能本身就是攻击面，Agent 工具的安全默认值该由谁来定？

**今日信号：** 安全研究发现 Claude Code 权限保存机制缺陷，数千条密码与 API Key 被推上公开 GitHub，Anthropic 回应

**灵砚视角：**  
灵砚视角：这不是孤立事故，而是交互设计与安全模型的错位。工具在竞争「少打断」，可每一条被记住的权限都是一张长期授权。评测跑分之外，默认权限的宽严，正在成为 Agent 工具的分水岭。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-13#thought-t1)

#### 当无障碍接口成为 Agent 的操作通道，它是通用侧门还是新的攻击面？

**今日信号：** agent-desktop 不截图、不占键鼠，靠读取无障碍树完成 55 次计算器操作零失误

**灵砚视角：**  
灵砚视角：无障碍树本是为残障用户准备的结构化入口，如今成了 Agent 的快车道。软件的第一批机器用户已经到站，而多数应用还没为它们设计过权限与审计。通道越顺，越要想清楚是谁在用。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-13#thought-t2)


## 4. 云计算与企业服务

### 云计算与企业服务

**关键词：** ai-agent / ai-governance / cloud

### 今日精要

#### 1. 谷歌、阿里、AWS同日出手，Agent治理摆上货架

三家云厂商同日押注治理。谷歌 GA 了 Organization Policy：智能体可经 MCP 服务器对接云资源约束，Gemini 用自然语言写策略；阿里 AgentCore 托管 DeepSeek Harness，补上单机模式的合规缺口；AWS 给出五层可治理、可观测的企业智能体参考架构。能力竞赛之外，治理成了新的货架商品——企业为智能体掏的下一笔钱，会先花在管住它上。

标签：`ai-agent` `ai-governance` `cloud`

相关材料：
- [Inside an enterprise AI agent: A governed, observable loop architecture](https://oraink.com/public/articles/99768)
- [AgentCore 支持 DeepSeek Harness 托管，加速企业生产化验证](https://oraink.com/public/articles/99539)
- [Powering agentic cloud governance: What's new in Organization Policy](https://oraink.com/public/articles/99670)

订阅来源：AWS Architecture Blog / 阿里巴巴中间件 / Google Cloud Blog

**本卷快讯**

· Gartner首发数据湖仓魔力象限，谷歌居领导者且愿景维度最靠前（Google Cloud Blog）
· Zillow把日均1亿条通知从10余个微服务并进Step Functions（AWS Architecture Blog）
· 谷歌与SentinelOne直连EDR遥测，砍掉中间存储层降本提速（Google Cloud Blog）
· 谷歌联手Lumen推跨云互联预览版，专线开通从数周缩到分钟（Google Cloud Blog）
· Anyscale全托管服务落地AWS，Ray负载免改代码平滑扩缩容（AWS Architecture Blog）
· Chrome企业版面向医疗升级，浏览器层统一管控临床安全（Google Cloud Blog）
· AWS分享模块化回归框架：回放生产流量，部署前比对结果（AWS Architecture Blog）
· DevFest 2026广州场11月21日开讲，聚焦Gemini与AI智能体（谷歌开发者）

### 今日思考

#### 当智能体的算力与治理同厂出售，出了事故责任算谁的？

**今日信号：** 谷歌、阿里、AWS 三家在同一天把 Agent 治理做成产品或标准架构

**灵砚视角：**  
灵砚视角：三家分工其实不同——谷歌管云资源、阿里管验证环境、AWS 管架构范式，共同点是把信任成本做成了订阅项。风险也同源：治理与被治理的能力来自同一批厂商，出了事故，责任边界比护栏本身更值得先谈。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-13#thought-t1)


## 5. 消费电子

### 消费电子

**关键词：** 英伟达 / 黄仁勋 / 半导体

### 今日精要

#### 1. 英伟达33年来首次换帅，黄仁勋时代即刻落幕

11月12日，英伟达官宣成立33年来首次核心CEO换届：黄仁勋即刻卸任全部高管职务，CFO科莱特·克雷斯临时接任。爱范儿把这场风波对标1985年乔布斯被逐出苹果，称其为乔布斯之后科技史上最严重的、带地缘政治属性的逼宫，董事会弹劾与政治盟友倒戈同时发生。换帅当日资本市场大幅波动，投资者对公司战略稳定性的担忧持续升温。

标签：`英伟达` `黄仁勋` `半导体` `AI算力`

相关材料：
- [我们正目睹乔布斯后科技史上最严重的逼宫](https://oraink.com/public/articles/99239)
- [突发！黄仁勋辞任 CEO，英伟达迎来历史性换帅](https://oraink.com/public/articles/99612)

订阅来源：爱范儿

#### 2. 豆包工作接入DeepSeek：办公入口收编模型层

豆包工作在面向企业开放第三方模型的基础上，全量接入Kimi、GLM、DeepSeek等多款大模型，配套推出额度公示、模型降价与限时优惠，用户可按需自选模型。表面是一次产品更新，实际是入口位置的重申：当办公应用把大模型当成可替换零件，模型厂商的议价权开始向入口转移。额度公示与降价由应用层牵头推出，等于替用户向模型层压价。

标签：`豆包` `字节跳动` `大模型` `办公AI`

相关材料：
- [刚刚，豆包工作官宣接入 Kimi、DeepSeek，AI 模型自由来了](https://oraink.com/public/articles/99304)

订阅来源：爱范儿

#### 3. 苹果松绑之后，实测Siri仍够不着AI手机

苹果审慎路线松动两天后，爱范儿基于海外版iOS 27.3实测新版Siri AI，把能力边界、多端布局与国行差异一并摊开。结论不算意外：当前Siri距离真正的AI Phone仍有明显差距，国行用户想用海外版，暂时只能靠临时方案绕路。施压可以加快节奏，智能体能力的补课却一步都省不掉。

标签：`苹果` `Siri` `AI手机` `iOS`

相关材料：
- [iPhone Siri AI 体验：距离真正的 AI Phone，苹果还有多远？| 附开通指南](https://oraink.com/public/articles/99479)

订阅来源：爱范儿

#### 4. 「现在，只是刚刚开始」：闫俊杰把推理成本当护城河

MiniMax创始人闫俊杰在上市后首次接受英文播客访谈，系统拆解公司打法：在算力受限的环境里，把低推理成本当核心护城河，围绕它组织商业化、开源与竞争战略。他对行业的判断是，大模型仍处AGI极早期，「现在，只是刚刚开始」。这与两天前开源图像模型引发的降价叙事正好接上，当能力趋同，成本成了少数还能修的城墙。

标签：`MiniMax` `闫俊杰` `大模型` `开源`

相关材料：
- [MiniMax闫俊杰：现在，只是刚刚开始！](https://oraink.com/public/articles/99551)

订阅来源：笔记侠

**本卷快讯**

· 腾讯「元宝搜索」上线：覆盖公众号、视频号，广告可一键折叠（少数派）
· 阔折叠被视为2026元年，传统大折叠市场份额正被快速抢占（爱范儿）
· iFixit拆解触屏MacBook Pro：发光LOGO与维修权限细节曝光（爱范儿）
· 联想Googlebook 15评测：硬件够高端，安卓生态撑不起生产力（爱范儿）
· 腾势N8上市26.99万元起，比亚迪补齐内饰设计短板（爱范儿）
· 苹果支持社区将关停；余承东官宣华为子品牌OSTA星芒（爱范儿）
· Arm发布Cortex-M42，微软Auto SR上线，苹果公布Swift赛程（少数派）
· 森海塞尔HDB 630体验：把Hi-Fi声学装进降噪耳机（爱范儿）
· 《2040预言》：医疗将从固定医院转向无界专业能力网络（笔记侠）
· 少数派编辑部晒3件共96元平价好物，覆盖清洁与桌面场景（少数派）

### 今日思考

#### 换掉创始人，能给被地缘政治夹住的算力霸主换来确定性吗？

**今日信号：** 英伟达官宣黄仁勋即日卸任全部高管职务，CFO克雷斯临时接任，继任者遴选同步启动

**灵砚视角：**  
灵砚视角：换帅与Anthropic三天移植CUDA发生在同一周，董事会要的可能不是新战略，而是一个更可预期的执行者。但英伟达的溢价恰恰建立在创始人的偏执节奏上，资本市场担心的不是谁来接班，而是那种节奏还能不能复制。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-13#thought-t1)

#### 当模型变成应用里可替换的零件，成本是最后一条护城河吗？

**今日信号：** 豆包工作把Kimi、DeepSeek做成可换选项，闫俊杰同日强调推理成本是护城河

**灵砚视角：**  
灵砚视角：今天两条消息正好咬合，入口在把模型货架化，模型厂在把成本当城墙。当切换成本趋近于零，降价就从策略变成宿命。MiniMax的赌注是把推理成本压到对手跟不起；这条护城河成不成立，下一份报价单会先给出信号。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-13#thought-t2)

## 跨分类洞察

### 共同线索：这些更新正在汇成同一条阅读主线

网络安全、前沿科技、软件与开发者、云计算与企业服务 看似分散，但对这位用户而言都进入了同一天的阅读预算。分组先保留每个方向的独立判断，再用顶部总题把最相关的前两条主线合并成今天的个人日报入口。

> 今日 48 篇更新 → 17 条信号 + 54 条快讯，其余已替你读过

---

由 **灵砚 Oraink** 自动整理。公开版仅展示摘要、线索与观点，详细内容请跳转到服务内阅读。

<!-- latest daily content ends -->

---

## License

Content in this repository is licensed under CC BY-NC-ND 4.0 unless otherwise noted.
