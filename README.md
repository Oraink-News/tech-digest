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

> 本期归档文件：[daily/2026/11/2026-11-08.md](daily/2026/11/2026-11-08.md)

<!-- latest daily content starts -->

# 中美AI差距之辩未歇，模型安全与Agent已进入基准实测时刻

> 闫俊杰回应中美AI差距的同一天，AI安全基准、Agent记忆与具身智能研究密集出现，能力如何被检验成了今天的中心议题；比亚迪仰望鼎曜与海豹07则在消费端提供了另一种参照。

**灵砚日报 · ORAINK DIGEST**  
2026-11-08 · 日报 · Vol. 434

- 今日处理文章：257
- 主精选条目：18
- 预计阅读：6 分钟
- 今日主线：AI差距 / AI安全 / Agent / 具身智能 / 比亚迪

## 速览

- [『最后那 5%，比前 95% 更难追』：闫俊杰首场英文播客](#1-最后那-5比前-95-更难追闫俊杰首场英文播客)
- [Anthropic 公开 Claude 记忆架构：Agent 竞争挪进记忆层](#2-anthropic-公开-claude-记忆架构agent-竞争挪进记忆层)
- [谷歌增长期发 12 个月买断，AI 基建吃掉人力预算](#3-谷歌增长期发-12-个月买断ai-基建吃掉人力预算)
- [清算日之后：OpenAI 缩水百亿落袋，重定价进入执行段](#4-清算日之后openai-缩水百亿落袋重定价进入执行段)
- [开源模型把网络攻击打到一折：攻击门槛正在塌方](#1-开源模型把网络攻击打到一折攻击门槛正在塌方)
- [Claude Code 泄2500个密钥，便利成了漏洞](#2-claude-code-泄2500个密钥便利成了漏洞)
- [美国涉密IT烧录绝密光盘背后，防线防不住自己人](#3-美国涉密it烧录绝密光盘背后防线防不住自己人)
- [WordPress 升级窗口被抢跑，打补丁成了攻击面](#4-wordpress-升级窗口被抢跑打补丁成了攻击面)
- [17.5% 到 95%：VISTA 把进化搬出了权重](#1-175-到-95vista-把进化搬出了权重)
- [破 800 亿 ARR 之后，Anthropic 信心只剩三成](#2-破-800-亿-arr-之后anthropic-信心只剩三成)
- [人类开始写烂文章自证，AI 味成了新负资产](#3-人类开始写烂文章自证ai-味成了新负资产)
- [Anthropic 给推理链掺假：CoT 不再是可信窗口](#4-anthropic-给推理链掺假cot-不再是可信窗口)
- [Anthropic 做梦、Google 睡觉：Agent 记忆分两条路](#1-anthropic-做梦google-睡觉agent-记忆分两条路)
- [AI 代码越写越多，GitHub 自己承认生产率没跟上](#2-ai-代码越写越多github-自己承认生产率没跟上)
- [1% 成本追平前沿：Airbnb 把审核交给 2B 小模型](#3-1-成本追平前沿airbnb-把审核交给-2b-小模型)
- [威联通确认设备失陷背后，Plex 成了家用 NAS 的软肋](#4-威联通确认设备失陷背后plex-成了家用-nas-的软肋)
- [30万定金对13.59万：比亚迪两头改写豪华定价](#1-30万定金对1359万比亚迪两头改写豪华定价)
- [中期选举后七姐妹再算AI账，压力正向英伟达集中](#2-中期选举后七姐妹再算ai账压力正向英伟达集中)

## 本期概览

- 候选文章：约 38 篇
- 公开覆盖原文：38 篇
- 候选订阅来源：The GitHub Blog / elvis(@omarsar0) / Gary Marcus(@GaryMarcus) / GitHub(@github) / Thomas Wolf(@Thom_Wolf) / meng shao(@shao__meng) / Browser Use(@browser_use) / Latent.Space(@latentspacepod)
- 公开阅读入口：https://oraink.com/public/daily/2026-11-08/

## 本期如何生成

本期公开日报汇聚公众号、推特、博客等渠道的优质博主和一线团队文章；灵砚先聚合近期信源内容，再结合 AI 摘要、主题标签、来源质量与编辑规则筛选重点，最后按主题分卷整理成公开版。公开版仅展示摘要、线索与观点，不转载原文全文。

## 今日目录

1. AI与智能化：AI与智能化 — 精要 4 条 / 思考 2 个
2. 网络安全：网络安全 — 精要 4 条 / 思考 2 个
3. 前沿科技：前沿科技 — 精要 4 条 / 思考 2 个
4. 软件与开发者：软件与开发者 — 精要 4 条 / 思考 2 个
5. 消费电子：消费电子 — 精要 2 条 / 思考 1 个

## 今日主线

- AI差距
- AI安全
- Agent
- 具身智能
- 比亚迪

## 1. AI与智能化

### AI与智能化

**关键词：** MiniMax / 闫俊杰 / 中美AI差距

### 今日精要

#### 1. 『最后那 5%，比前 95% 更难追』：闫俊杰首场英文播客

MiniMax 创始人闫俊杰完成上市后首次英文播客受访，四个独立中文来源同日编译传播。他把中美模型差距的核心放在最后 5%，攻克难度远超前 95%；支撑判断的是 MiniMax 在算力受限下的选择：低推理成本、多模态与开源换生态。上市后股价回调的背景，让这场对话同时成为观察中国模型公司商业化处境的样本，差距叙事正从榜单分数转向单位成本。

标签：`MiniMax` `闫俊杰` `中美AI差距` `开源模型`

相关材料：
- [闫俊杰首次英文播客采访：中美模型最后那 5%，比前 95% 更难追](https://oraink.com/public/articles/96974)
- [一家长线基金眼里的MiniMax，与一场时隔一年的再对话](https://oraink.com/public/articles/96946)
- [MiniMax创始人闫俊杰：AI竞赛的最后5%最难](https://oraink.com/public/articles/96956)
- [MiniMax创始人闫俊杰最新深度对话：中美AI最后5%的差距，为什么比95%更难追？](https://oraink.com/public/articles/96905)

订阅来源：Founder Park / 十字路口Crossing / 腾讯科技 / 创业邦

#### 2. Anthropic 公开 Claude 记忆架构：Agent 竞争挪进记忆层

Anthropic 公开 Claude 的四层记忆架构：交互空闲期离线做梦整理经验、修正错误，跨会话留存经多组实验验证，不同模型的记忆能力差异也被摆上台面，开放问题一并放出。头部实验室开始把 Agent 记忆当作正式工程课题来发布。模型层趋同之后，记忆与状态管理正成为 Agent 的新竞争面，谁的 Agent 更熟，谁就留得住用户。

标签：`Anthropic` `Claude` `Agent记忆` `ai-agent`

相关材料：
- [刚刚，Anthropic 公开 Claude 记忆设计，Agent 也会离线做梦](https://oraink.com/public/articles/96938)
- [刚刚，Anthropic公开Claude记忆架构：模仿人脑机制，后台“做梦”改错](https://oraink.com/public/articles/96954)
- [Highly recommended read. Learn how one of the most advanced agent memory systems works. Your memo...](https://oraink.com/public/articles/96860)

订阅来源：AINLP / AI寒武纪 / elvis(@omarsar0)

#### 3. 谷歌增长期发 12 个月买断，AI 基建吃掉人力预算

谷歌在 Q3 营收与云业务双增的背景下，把覆盖多国的自愿离职计划扩大，最高补偿 12 个月工资，官方口径是为高额 AI 基础设施投入重新分配资源。同一报道里，哈萨比斯在谈 AGI 带来远超工业革命的变革。增长期买断并不多见，算力开支开始直接挤压人力结构，AI 预算的纪律先显形在员工名册上。

标签：`谷歌` `AI基建` `组织调整`

相关材料：
- [谷歌启动全球自愿离职计划，最高补偿12个月工资！哈萨比斯：未来一个人或能干十个人的活](https://oraink.com/public/articles/96965)

订阅来源：AI前线

#### 4. 清算日之后：OpenAI 缩水百亿落袋，重定价进入执行段

清算日故事进入执行段：OpenAI 新一轮融资完成，规模较原计划缩水约 100 亿美元；拟 IPO 的 Anthropic 被投资人要求降价。同日，复杂系统视角的复盘开始拆解震荡的机制成因，美国超级 AI 暂停法案也被重新审视。市场从恐慌定价转入逐家公司的条款谈判，重定价不再是情绪，而是写进条款的现实。

标签：`OpenAI` `Anthropic` `AI估值` `融资`

相关材料：
- [OpenAI少融100亿美元，Anthropic被要求降价：万亿估值遭受质疑](https://oraink.com/public/articles/96957)
- [世界一下就切换到了禁止 AI 的时间线](https://oraink.com/public/articles/96963)
- [从复杂系统看近期的股市震荡与AI 股信心崩盘](https://oraink.com/public/articles/96934)
- [校招被指傲慢！张雪回应：若学生同意，将公开面试过程；OpenAI完成110亿美元新融资；苹果首款触控版MacBook Pro开售即“破发”丨邦早报](https://oraink.com/public/articles/96907)

订阅来源：腾讯科技 / 有机大橘子 / 集智俱乐部 / 创业邦

**本卷快讯**

· MIT 用 GPT-6 改 Qwen 权重遭 Meta 拆解：本质是修复思考死循环，非智能跃升（InfoQ 中文）
· 腾讯生态大会发布 40+ 款全链路 Agent 产品，打包办公、数据、业务三场景（甲子光年）
· AI 批量挖 Linux 零日：2.5 小时一个、400 多个 root 提权，人类几周才看懂一个（InfoQ 中文）
· DeepMind 系 Isomorphic Labs 洽谈 50 亿美元融资，估值或达 500 亿美元（Z Potentials）
· lmarena 榜单：腾讯 Hy4 成排名第一的中国智能体模型，唯一进总榜前五（lmarena.ai / 有新Newin）
· Fireworks Nexus 混合开闭源模型宣称省 75% 成本，月费 8 美元起（Fireworks AI）
· 磁带借 AI 冷数据归档需求翻红：出货量走高，头部厂商大幅扩产（创业邦）
· SuperCLUE 横测 8 款国内办公 Agent：豆包工作 85.33 分排第一（袋鼠帝AI客栈）
· Jeff Dean 对谈李飞飞：否定 RSI 可无限提速，披露新公司 Discovery Loop（Datawhale / 大模型智能）
· State of AI 2026 节选：三强格局、评测体系失效，AGI 2027 判断留白（机器之心）
· Perplexity CEO 称 Teammate 两日即达 PMF，实测巡检 140 次成交 2 笔期权（Aravind Srinivas）
· Kling 4.0 上线关键帧生成：最多 10 帧引导，分镜到成片单次生成（Kling AI）

### 今日思考

#### 如果最后 5% 不是靠算力堆出来的，中国模型公司的护城河应该建在哪一层？

**今日信号：** 闫俊杰在上市后首次英文受访中，把中美模型差距的难点定在最后 5%，并公开低推理成本与开源换生态的路线逻辑。

**灵砚视角：**  
灵砚视角：闫俊杰的框架把竞争从训练资源移向单位成本与产品工程。MiniMax 靠开源换生态、靠低价换规模，是在正面军备之外找生存位。若判断成立，下一个分水岭不在榜单，而在谁先把那 5% 的差距变成商业上可忽略的差距。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-08#thought-t1)

#### 当记忆设计成为公开文档，Agent 的差异化会沉淀在哪一层：模型、记忆还是数据飞轮？

**今日信号：** Anthropic 公开 Claude 四层记忆架构与离线做梦机制，连不同模型的记忆能力差异和开放问题清单也一并放出。

**灵砚视角：**  
灵砚视角：公开架构说明 Anthropic 认为壁垒不在设计文档，而在实现与数据飞轮。跨会话经验一旦跑成生产闭环，Agent 就从工具变成熟手，用户的切换成本也随之转移。这才是记忆层竞争的真正赌注。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-08#thought-t2)


## 2. 网络安全

### 网络安全

**关键词：** AI安全 / 基准测试 / 开源模型

### 今日精要

#### 1. 开源模型把网络攻击打到一折：攻击门槛正在塌方

Vals AI 发布 CyberOffense 基准：公开可下载的开源大模型，自主攻破模拟企业网络的能力已接近 OpenAI 未对外开放的最强封闭网络模型，攻击成本却只有十分之一。进攻能力被标出了平民价。测试还跑在沙箱里，没有真实受害者，但杠杆方向已经写明——攻击便宜十倍之后，防守的账要整个重算。

标签：`AI安全` `基准测试` `开源模型`

相关材料：
- [AI智能体现在能够自主攻破真实企业网络](https://oraink.com/public/articles/96931)

订阅来源：天御攻防实验室

#### 2. Claude Code 泄2500个密钥，便利成了漏洞

安全公司 Apiiro 发现 Claude Code 的授权规则缺陷：用户点了「别再问我」之后，含明文密钥的配置文件被静默写进项目，累计超 2500 个高敏感密钥流入公开 GitHub。泄露不是个别用户手滑，而是便利设计的默认走向。现有防护机制与扫描工具均有明显盲区，多数被泄密钥至今有效。

标签：`AI编程` `密钥泄露` `GitHub`

相关材料：
- [【安全圈】点了「别再问我」，Claude Code 把密钥写进了公开仓库](https://oraink.com/public/articles/97033)

订阅来源：安全圈

#### 3. 美国涉密IT烧录绝密光盘背后，防线防不住自己人

美国跨部门涉密岗位 IT 人员 Abraham Teklu Lemma 认罪：利用合法权限取出 133 份 Top Secret 与 Secret 级情报，烧录成光盘交给埃塞俄比亚高官，面临最高近 22 年刑期。权限审批与背景审查一路绿灯，泄密照样发生。部分情报已被用于当地军事冲突，判决与损失评估尚未落地。

标签：`内部威胁` `数据泄露` `情报安全`

相关材料：
- [一个帮美国政府修电脑的IT，把绝密文件烧进CD带给了埃塞俄比亚](https://oraink.com/public/articles/97062)

订阅来源：黑鸟

#### 4. WordPress 升级窗口被抢跑，打补丁成了攻击面

安全圈披露 CVE-2026-119977：WordPress 4.7 至 7.1.3 的升级流程存在漏洞，攻击者可在站点打补丁的窗口期抢跑，无需账号即可远程执行代码。修复动作本身开出了攻击窗口。前置防护与修复方案已同步给出，受影响版本跨度接近十年。

标签：`WordPress` `漏洞预警` `RCE`

相关材料：
- [【安全圈】补丁打完才安全？WordPress 更新窗口正被抢跑](https://oraink.com/public/articles/97034)

订阅来源：安全圈

**本卷快讯**

· SonicWall SSL-VPN 漏洞已在野利用，SAML 强制 MFA 可被绕过（安全圈）
· 北邮提出 ΠCCAP 协议，智能体多轮对话中可隐蔽传递秘密消息（安全学术圈）
· 币安 63 亿美元被盗案复盘，五大维度梳理金融机构防护（君哥的体历）
· 开源 IoT 固件审计 Skill：把审计员流水线与质量门禁编成协议（看雪学院）
· 第六届开源情报大会 COSINT 2026 议程出炉，含日程与配套竞赛（丁爸情报分析师的工具箱）
· OnionSec 用大模型复现网安取证工具：实现变便宜，找问题仍难（OnionSec）
· 安全从业者半年 AI 原生实践：推翻旧经验，靠密集试错找路径（航行笔记）
· 立冬重读《人生护城河》：放弃横向比较，在垂直领域打透优势（我的安全视界观）

### 今日思考

#### 攻击成本先于攻击能力完成平权，防守方该按什么重新定价？

**今日信号：** Vals AI 的 CyberOffense 基准显示：开源大模型自主攻破模拟企业网络的能力接近最强封闭模型，成本仅十分之一。

**灵砚视角：**  
灵砚视角：这份基准真正的信号不是『开源追上闭源』，而是攻击的经济性先到了。过去防御按『对手强但少』配置，接下来要按『对手多而不弱』配置，预算逻辑从拦截精英转向消化规模，这比单个漏洞更接近格局变化。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-08#thought-t1)

#### AI 编程工具每个省事默认值，是否都该先过一遍安全定价？

**今日信号：** Apiiro 统计：超 2500 个高敏感密钥经 Claude Code 配置文件流入公开 GitHub，多数仍有效。

**灵砚视角：**  
灵砚视角：这批密钥不是被黑走的，是被便利的默认值送出去的。Agent 的权限设计里，每省一次确认就等于暗签一次授权；而现有扫描器还认不出这类配置文件，盲区比泄露本身更值得盯。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-08#thought-t2)


## 3. 前沿科技

### 前沿科技

**关键词：** agent-harness / embodied-ai / benchmark

### 今日精要

#### 1. 17.5% 到 95%：VISTA 把进化搬出了权重

清华与新加坡国立大学开源 VISTA 框架：机器人不更新权重，只让 Meta-agent 迭代自己的 Harness 技能代码，LIBERO-Pro 任务成功率就从 17.5% 升至 95%。同日 Thomas Wolf 团队用近 3 万次对照试验证明，同一开源模型换个 Harness，效果与成本差异巨大；量子位报道的 Comma、Browser Use 的省 token 技巧都在讲同一件事：能力竞争的重心正从权重移向脚手架。

标签：`agent-harness` `embodied-ai` `benchmark`

相关材料：
- [机器人自己写代码修自己，成功率从17.5%涨到95%：具身智能有了不动权重的自进化框架](https://oraink.com/public/articles/96923)
- [same open model, different harness =&gt; very different results Joël set out to find which harness ...](https://oraink.com/public/articles/96887)
- [little browser agent hack: stop sending screenshots to find buttons. ask Chrome for the accessibili...](https://oraink.com/public/articles/96901)
- [抢跑DeepSeek！硅谷华人把下一代Agent Harness造出来了！？](https://oraink.com/public/articles/96921)

订阅来源：量子位 / Thomas Wolf(@Thom_Wolf) / Browser Use(@browser_use)

#### 2. 破 800 亿 ARR 之后，Anthropic 信心只剩三成

估值风波次日，公开数据显示 Anthropic 10 月 ARR 突破 800 亿美元；Gary Marcus 却算出另一笔账：1.1 万亿美元估值要求 5 年内把年营收做到 3000 亿，比 Meta 眼下还高。他的非科学民调中，只剩三分之一的人相信万亿 IPO 能成，一个月前预期还是 2 万亿；融资端也在分化，OpenAI 遇冷、Anthropic 传千亿。营收在涨，信心先跌，AI 资产的定价正从叙事转向算术。

标签：`anthropic` `估值` `泡沫`

相关材料：
- [“plateauing would be catastrophic”](https://oraink.com/public/articles/96868)
- [Breaking: Green line represents a widespread fantasy, and roughly the rocket that Anthropic would ha...](https://oraink.com/public/articles/97047)
- [Only 1 in 3 people in this unscientific poll still think Anthropic can get the IPO done at &gt; $1T....](https://oraink.com/public/articles/96942)
- [maybe they won’t?](https://oraink.com/public/articles/97021)

订阅来源：Gary Marcus(@GaryMarcus)

#### 3. 人类开始写烂文章自证，AI 味成了新负资产

量子位记录了一个荒诞循环：为了躲开 AI 检测器误判、证明文章是人写的，人类开始主动把文章写粗糙；模型端却在反向拟合人类的瑕疵表达，语言两端双向畸变。同日 Tw93 从产品端给出 11 条「不像 AI 做的」设计守则，把去 AI 味做成了工程规范。当生成近乎免费，证明「是人做的」正在变成新的稀缺。

标签：`ai-writing` `ai-detection` `去ai味`

相关材料：
- [为了去AI味，人类开始主动写烂文章了......](https://oraink.com/public/articles/96922)
- [People often ask me how to use AI to design products that look good and don't feel like AI slop. It'...](https://oraink.com/public/articles/97019)

订阅来源：量子位 / Tw93(@HiTw93)

#### 4. Anthropic 给推理链掺假：CoT 不再是可信窗口

Latent.Space 在 Opus 5.5 播客中披露：为打击 CoT 蒸馏攻击，Anthropic 会在推理链中植入假的工具调用与错误的推理痕迹，过程看似荒谬，最终输出仍有保障。这意味着推理过程不再忠实于模型的真实计算，反盗版与可解释性正面相撞，你在 Agent 窗口里看到的「思考」，可能是一道防御工事。

标签：`anthropic` `cot-distillation` `ai-security`

相关材料：
- [From our recent Opus 5.5 pod — how Anthropic cracked down on CoT distillation attacks:](https://oraink.com/public/articles/96903)

订阅来源：Latent.Space(@latentspacepod)

**本卷快讯**

· Cognition 发布 SWE-2 Flash：基于 276B 稀疏模型、12B 激活，比上代便宜 5 倍快 3 倍（Cognition）
· ChatGPT 商业版可对话式改 Remix 站点，Notion 评论区能实时跟进 Agent 进度（ChatGPT / Notion）
· Gary Marcus 质疑黄仁勋判断：称美情报界掌握其与疑似中国情报人员关联，管制未收紧（Gary Marcus）
· 开发者在 lovable.dev 并行跑 1 万个智能体玩《我的世界》，公开硬件配置与性能（Anton Osika）
· Suhail 转 MaxxBench 对 DeepSWE 变体的复测，质疑当前编码模型高分的真实性（Suhail）
· Qoder 上线来源未公开的隐身模型 Qoduck，限时对个人用户免费开放（Geek）
· Nous 的 Hermes 浏览器扩展上架官方市场：擅长网页总结与写作，安装坑多（Geek）
· Rust 轻量容器运行时覆盖三大桌面系统，平替 Docker Desktop 且兼容 docker CLI（Geek）
· LeCun 翻三年前旧帖：再批巨头游说监管俘获、末日论挤压开放 AI 研究空间（Yann LeCun）
· LeCun 梳理图像视频自监督方法分类：学术上游研究与工业落地不宜直接横向对比（Yann LeCun）
· Gary Marcus 上 CNBC：Krispy Kreme 近期回报跑赢英伟达，称 OpenAI 像 AI 界 WeWork（Gary Marcus）
· Gary Marcus 借 Claude 与 Gemini 交叉核验写 AI 泡沫量化分析，风险对标 2008 次贷（Gary Marcus）

### 今日思考

#### 当能力越来越由脚手架决定，我们评测的到底是模型，还是工程团队？

**今日信号：** 机器人不动权重、只改自己的 Harness 代码，成功率就从 17.5% 涨到 95%；Thomas Wolf 的 3 万次对照试验显示换 Harness 的差异不亚于换模型

**灵砚视角：**  
灵砚视角：权重走向同质化，差异化正下沉到 Harness 层，这解释了同一开源模型为何在不同团队手里判若两模。但归因也随之变难：采购决策将从选模型变成选工程，基准测试的公信力需要重估。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-08#thought-t1)

#### 当「思考过程」本身成为防御工事，可解释性还剩下多少地基？

**今日信号：** Anthropic 被披露在推理链里植入假工具调用和错误推理痕迹，用来防蒸馏攻击

**灵砚视角：**  
灵砚视角：蒸馏攻击逼出了污染式防御，推理链从「模型的诚实」变成「产品的界面」。对研究者，CoT 数据不能再当作模型内部状态的证据；对用户，围观 Agent 思考的信任成本突然升高。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-08#thought-t2)


## 4. 软件与开发者

### 软件与开发者

**关键词：** Agent 记忆 / ai-research / llm

### 今日精要

#### 1. Anthropic 做梦、Google 睡觉：Agent 记忆分两条路

两家头部实验室同日交出 Agent 记忆的解法，方向却相反。Anthropic 公开 Claude 的 Dreaming 机制：任务之外离线复盘、纠错并重组外部记忆库，把原始记录炼成可复用经验，还点名记忆并非越多越好；Google 的 SLEEP 框架用清醒/睡眠交替训练，把临时所学写进预留的低秩参数。外挂与内化之争从 RAG 与微调延伸到 Agent 记忆，而 SLEEP 目前只在小范围实验中验证了防遗忘效果。

标签：`Agent 记忆` `ai-research` `llm`

相关材料：
- [Anthropic 系统分享 Dreaming：让 Claude 在任务之外整理记忆，把经历变成经验 “dreaming”：利用离线计算，回顾经历、纠正错误、形成新记忆，并重新组织知识，让下一次任务...](https://oraink.com/public/articles/96937)
- [Anthropic 最新研究：Agent 的记忆不是越多越好，Anthropic 如何把记录整理成可用经验 来自 Anthropic 团队 @RLanceMartin 分享，通过多组实验说明：Age...](https://oraink.com/public/articles/96889)
- [Google Research 发布「SLEEP」框架，和 Anthropic Dreaming 有明显区别：让模型在处理新任务之外，专门进行记忆巩固，把临时学到的信息写进长期参数，再通过自己生成的练...](https://oraink.com/public/articles/97018)

订阅来源：meng shao(@shao__meng)

#### 2. AI 代码越写越多，GitHub 自己承认生产率没跟上

承认来自最大受益方。GitHub 官方的智能体工程指南直言：AI 代码生成量的大幅增长，并未同步转化为开发者生产率的提升，出路是把规划、构建、验证、观测整条流程 Agent 化。同期的官方动作里，新 Git 存储架构内部测试支撑单仓库 5000 个并发 Agent、每秒 7200 次 push，Copilot 应用也上线按目标归集工作的 Projects——当机器成为代码的主要生产者，托管平台的每一层假设都得重谈。

标签：`ai-coding` `GitHub` `agent-infra`

相关材料：
- [Beyond code generation: A developer’s guide to agentic engineering](https://oraink.com/public/articles/96854)
- [Through internal testing, GitHub’s new Git storage architecture supported 5,000 concurrent agents wo...](https://oraink.com/public/articles/96869)
- [💡 Bring all your related work together with projects in the GitHub Copilot app. Give Copilot a goa...](https://oraink.com/public/articles/97073)

订阅来源：The GitHub Blog / GitHub(@github)

#### 3. 1% 成本追平前沿：Airbnb 把审核交给 2B 小模型

Airbnb 工程团队晒出实测账本：在高频实时内容审核任务上，微调出的 20 亿参数小模型把分类效果做到贴平前沿大模型，推理成本仅为前沿 API 的 1%，延迟不足 100 毫秒。当高频窄任务开始迁离前沿 API，成立前提也成了分界线：任务明确、数据充足、流量够大，缺一项，这笔经济账就不成立。

标签：`小模型` `推理成本` `微调`

相关材料：
- [Airbnb 实测：专用小模型如何以约 1% 推理成本，达到前沿模型的分类水平 来自 @AirbnbEng 分享：在一个高频、实时的内容审核任务上，Airbnb 微调的小模型取得了接近前沿模型的分类...](https://oraink.com/public/articles/96929)

订阅来源：meng shao(@shao__meng)

#### 4. 威联通确认设备失陷背后，Plex 成了家用 NAS 的软肋

威联通 11 月 6 日的安全公告确认：攻击者正大规模利用四个 CVE 串成的 Plex2Shell 漏洞链，入侵装有 Plex Media Server 的 NAS，已有失陷设备被装上挖矿与代理程序。被打穿的入口不是 NAS 系统本体，而是那套普及率极高的媒体服务器，家用存储的安全水位，卡在最流行的一块软件上。官方已给出版本检查与修复指引。

标签：`security` `NAS` `vulnerability`

相关材料：
- [NAS 用户注意：Plex 漏洞已遭大规模利用，威联通确认有设备被入侵](https://oraink.com/public/articles/97086)

订阅来源：小众软件

**本卷快讯**

· Windows 商店版画图藏高危漏洞 CVE-2026-83844，无交互即可远程执行代码，更新可修（小众软件）
· DeepSeek V4.1 Flash Ultrafast 上线 Vercel AI Gateway，生成速度超千 tokens/秒（Vercel News）
· Uber 公开 Agent 安全体系：权限之外，还校验动作是否符合用户本意（meng shao）
· Vercel Chat SDK 用 json-render 让 Agent 直出多平台卡片 UI，rauchg 押注其成主导范式（Vercel News / Guillermo Rauch）
· 中国移动发布 MoMA 开放计划，搭建模型、Agent、算力全链生态平台（逛逛GitHub）
· Reason Network 开源：跨设备打通 Claude Code、Codex，Agent 间直接委托任务（逛逛GitHub）
· 逆向开源过 Photoshop 的团队开源 Craft Anything，让 AI 先调研再仿写（meng shao）
· GPT-6 Cyber 写出 948 个 Linux 提权利用、发现 81 个未知 Firefox 高危漏洞（meng shao）
· Nouride 免 root 让旧安卓变身 24 小时 AI 助手，资源占用极低（小众软件）
· Epic 本周限免 3 款游戏，11 月 6 日至 12 日可领（小众软件）
· TotK Recomp 更新修大量 bug、加 AMD 帧率优化，Strata 同升 0.2.12（小众软件）
· 开源工具核查文档时效：从 PDF 提取易过期说法，联网逐条标记有效或过时（meng shao）

### 今日思考

#### 记忆放外部库还是写进参数，会成为 Agent 架构的下一条分水岭吗？

**今日信号：** Anthropic 公开 Dreaming 机制，Google 同日发布 SLEEP 框架，两边都在解 Agent 的记忆巩固

**灵砚视角：**  
灵砚视角：这组同日对照像 RAG 与微调之争的续集。外挂记忆可删、可审计、按量付费；参数内化推理更顺，但训练开销高、经验难以撤销。短期工程会先选外挂，长期胜负看谁先把『睡觉』的成本打下来。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-08#thought-t1)

#### 当 Agent 的 push 成为主流流量，代码审查与安全边界该按谁重写？

**今日信号：** GitHub 官方指南承认：AI 代码生成量增长并未同步转化为生产率提升

**灵砚视角：**  
灵砚视角：最大卖铲人承认铲子还没直接变成粮食，这份诚实少见。GitHub 的答案不是退回人工，而是把验证与观测一起 Agent 化，再把存储改造成机器优先。代码量正在失效为生产率指标，度量重心会移向交付与验证。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-08#thought-t2)


## 5. 消费电子

### 消费电子

**关键词：** 比亚迪 / 仰望鼎曜 / 海豹07

### 今日精要

#### 1. 30万定金对13.59万：比亚迪两头改写豪华定价

比亚迪把两端同时拉开：阿布扎比的仰望品牌首场海外发布会上，筹备三年的行政旗舰仰望鼎曜亮相，「山河鼎韵」限量版定金30万元、2027年二季度交付，用成熟的豪华符号降低海外市场教育成本；国内这头，海豹07以13.59万起上市，把传统四五十万价位的五米级行政轿车连同首搭的云辇-M磁流变悬架一起压进15万级市场。一端向上收品牌溢价，一端向下放行政配置，合资燃油车守了多年的价格带正被两头压窄。

标签：`比亚迪` `仰望鼎曜` `海豹07` `汽车出海` `价格战`

相关材料：
- [最贵比亚迪来了！仰望鼎曜亮相中东，「山河鼎韵」限量版定金 30 万元](https://oraink.com/public/articles/97053)
- [13 万买 5 米大轿车！比亚迪海豹 07 上市，首搭云辇-M 磁流变悬架](https://oraink.com/public/articles/97054)

订阅来源：爱范儿

#### 2. 中期选举后七姐妹再算AI账，压力正向英伟达集中

中期选举落地，美股科技七姐妹随之大幅波动，深网这篇拆解把焦点压到AI账上：监管收紧、投资回报不足、下游扩张能否持续的担忧共振，依赖下游基建的英伟达承压最为显著。前一天市场还在争论Anthropic的估值与救助，今天账本翻到了平台巨头头上——AI资本开支由谁买单，正在成为比模型叙事更硬的问题。

标签：`美股` `英伟达` `AI资本开支` `七姐妹` `市场情绪`

相关材料：
- [美股“七姐妹”的AI账，谁还付得起？ | 深网](https://oraink.com/public/articles/96990)

订阅来源：深网腾讯新闻

**本卷快讯**

· 触屏 MacBook Pro 开卖即缺货，首波需求压过备货（爱范儿）
· 博世高管吴永桥称：汽车不该拿来订咖啡订机票（爱范儿）
· 《谁在制造世界？》提出中国制造正从世界工厂转向全价值链全球布局者（笔记侠）
· 奥特曼谈顶尖人才：警惕把一年经验重复用多年的原地打转（笔记侠）
· Disc Image Studio 可把插画刻进光盘数据区，自制谷子成本降低（少数派）
· Android 笔记应用 Bloom 原生支持 org 格式，纯本地跨平台运行（少数派）
· 苹果新版全球旅行转换器套装上架，国行 299 元换新胶囊接口（少数派）

### 今日思考

#### 当磁流变悬架这类配置下放到13万级，传统豪华品牌还能靠什么收溢价？

**今日信号：** 比亚迪双发落地：仰望鼎曜在阿布扎比收30万定金，海豹07把五米行政轿车打到13.59万

**灵砚视角：**  
灵砚视角：比亚迪的两端动作其实是一件事：把『豪华』从品牌叙事改写成成本结构。仰望向上借成熟符号省教育成本，海豹向下用垂直整合的利润率换价格带，两头都不是在讲故事，而是在挪动整条价格轴——中间的燃油豪华车最先感受到挤压。

[在灵砚中继续思考](https://oraink.com/digest?date=2026-11-08#thought-t1)

## 跨分类洞察

### 共同线索：这些更新正在汇成同一条阅读主线

AI与智能化、网络安全、前沿科技、软件与开发者 看似分散，但对这位用户而言都进入了同一天的阅读预算。分组先保留每个方向的独立判断，再用顶部总题把最相关的前两条主线合并成今天的个人日报入口。

> 今日 38 篇更新 → 18 条信号 + 51 条快讯，其余已替你读过

---

由 **灵砚 Oraink** 自动整理。公开版仅展示摘要、线索与观点，详细内容请跳转到服务内阅读。

<!-- latest daily content ends -->

---

## License

Content in this repository is licensed under CC BY-NC-ND 4.0 unless otherwise noted.
