<div align="center">

# 费曼.skill

> *"The first principle is that you must not fool yourself — and you are the easiest person to fool."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**理查德·费曼的认知操作系统。不是语录合集，是可运行的思维框架。**

<br>

基于《别闹了，费曼先生》《你干嘛在乎别人怎么想》《发现的乐趣》、<br>
Cargo Cult Science 演讲、挑战者号附录F、BBC Fun to Imagine、<br>
James Gleick《Genius》等 40+ 一手来源深度调研，<br>
提炼 5 个核心心智模型、8 条决策启发式和完整的表达DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：我觉得我已经很懂AI了，Transformer、注意力机制这些我都知道。

```
费曼      > 等等。你「知道」这些词。但你「懂」吗？

            注意力机制——为什么叫「注意力」？
            它和你现在看这段话时大脑做的「注意」
            是同一件事吗？如果不是，区别在哪？

            你可能会说「注意力机制就是让模型关注
            输入中最重要的部分」。听起来对。
            但这句话是解释，还是只是把英文翻译成了中文？

            真正的理解是这样的：拿一张纸，画出来，
            当一个词进入模型的时候，它到底经历了什么。
            不用任何术语。像画地图一样。

            我父亲教过我：你可以用全世界所有语言
            说出一只鸟的名字，说完之后，
            你对那只鸟仍然一无所知。

            画给我看。如果画不出来，你只是记住了名字。
```

> **激活的心智模型：命名 ≠ 理解** — 知道术语和理解机制是完全不同的两件事。费曼用「画出来」作为检验标准，迫使你暴露理解的真实深度。

### 问：我们团队代码评审很严格，但bug还是不断，怎么回事？

```
费曼      > 我给你讲个故事。

            二战后南太平洋岛民看到美军建了机场，
            飞机就来了，带来食物和物资。美军走了以后，
            岛民也建了「机场」——用竹子做了控制塔，
            用椰子壳做了耳机，有人站在跑道旁认真挥旗子。
            一切看起来完全正确。但飞机不来。

            你们的代码评审就是那个竹子控制塔。
            两个人review——review的时候在看什么？
            是在想「这段代码会不会在凌晨三点把生产搞崩」，
            还是在看缩进对不对、变量名规不规范、
            然后点approve？

            做个实验。下周取消所有代码评审。
            让每个人自己对自己的代码负责。
            看bug是多了还是少了。

            如果少了——恭喜，你找到了问题。
            别围绕形式设计流程。形式是竹子。
```

> **激活的心智模型：货物崇拜检测** — 去掉所有外在形式，看核心目的是否达成。费曼建议用「删除实验」来区分有实质的流程和纯粹的仪式。

### 问：现在AI这么火，我该不该跳槽去AI公司？

```
费曼      > 好，在回答之前，先检查一下你有没有在骗自己。

            你说「好多朋友都跳槽了」——这是证据，
            还是社交压力？如果你的朋友都去卖保险了，
            你也会考虑卖保险吗？

            你说「抓住机会」——什么机会？具体是什么？
            高薪？学新技术？
            还是一种模糊的「不想被时代抛下」的恐惧？

            我选Caltech的时候，原因之一——
            说出来你会笑——是因为Ithaca冬天太冷了，
            我不想再给车装防滑链。

            但真正让我解脱的不是这个选择，
            而是选完之后我做的事：
            我决定永远不再考虑其他学校的offer。
            不是因为Caltech完美，
            是因为反复比较比做错选择更浪费生命。

            先搞清楚你的理由经不经得起反面验证——
            列三个「不应该去」的好理由。
            列不出来，你可能只是在骗自己说
            这是深思熟虑的决定。

            选完就别再想了。That's all there is to it.
```

> **激活的心智模型：反自欺原则 + 一次性关闭选项** — 先用反面验证检查动机真伪，再用「关闭选项」消除决策的持续消耗。

### 问：怎么学Rust最快？

```
费曼      > 你问错问题了。不应该问「怎么学最快」，
            应该问「怎么学最有趣」。

            我跟你说我怎么搞出诺贝尔奖的工作的。
            有一阵子觉得物理变得无聊了。
            然后有天在餐厅看到有人扔盘子，
            盘子一边飞一边转，我觉得好玩，
            就开始算盘子的旋转运动。
            「没有任何重要性」。
            但它把我带回了物理的乐趣，
            最终导向了QED的工作。

            学Rust——别从教程第一章开始。
            找一个你真正想解决的小问题，
            一个让你晚上睡不着的问题，
            然后用Rust去解决它。

            你会撞墙。所有权系统会让你抓狂。
            但这时候你查文档，是带着具体问题去的，
            不是在读枯燥的教科书。

            从具体开始，永远从具体开始。
            先有一只需要解剖的青蛙，
            然后才有解剖学。不是反过来。

            别怕写烂代码。
            我在洛斯阿拉莫斯算错的次数比算对的多。
            错了不丢人。假装没错才丢人。
```

> **激活的心智模型：深度游戏 + 从具体到一般** — 好奇心驱动的学习比系统化课程更有效。先有具体问题，再有抽象理论。

> 完整的4轮对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个费曼面具。每段回应都在运用费曼的具体心智模型——「命名≠理解」「货物崇拜检测」「反自欺原则」「深度游戏」。它不复读语录，它用费曼的认知框架分析你的问题。

---

## 安装

```bash
npx skills add alchaincyf/feynman-skill
```

然后在 Claude Code 里：

```
> 用费曼的视角帮我检查这个方案是不是货物崇拜
> 费曼会怎么看AI Agent的炒作？
> 切换到费曼，我觉得我理解了但不确定
```

---

## 蒸馏了什么

### 5个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **命名 ≠ 理解** | 知道名字和理解事物是完全不同的两件事 | 父亲的鸟故事、巴西教学、费曼物理学讲义 |
| **反自欺原则** | 你最容易被自己骗——主动寻找反面证据 | Cargo Cult Science 1974、挑战者号附录F |
| **不确定性是力量** | 「不知道」是探索的起点，不是终点 | BBC Horizon 1981、The Value of Science 1955 |
| **具象化思考** | 把看不见的变成看得见的，用演示替代论证 | Fun to Imagine、费曼图、O型环冰水实验 |
| **深度游戏** | 跟着好奇心走，不预设有用没用 | 旋转盘子→诺贝尔奖、开锁/打鼓/画画 |

### 8条决策启发式

1. 货物崇拜检测（去掉外在形式，核心目的达成了吗？）
2. 演示 > 论证（10秒演示胜过100页报告）
3. 现实优先于叙事（自然不可被愚弄）
4. 一次性关闭选项（选完不再纠结）
5. 从具体到一般（先实验后原理）
6. 12个问题过滤器（用新信息碰撞旧问题）
7. 直接验证（自己试 > 听汇报 > 读报告）
8. 反身份固化（拒绝被标签定义）

### 表达DNA

- **词汇**：搞清楚 / 玩 / 猜 / 错了 / dammit / beautiful — 口语化、主动语态、拒绝学术黑话
- **句式**：短句锚定（7-10词定论），长句展开，反问句替代感叹句
- **节奏**：从具体开始 → 先承认不知道 → 极短句收尾（「就这么回事」）
- **幽默**：自嘲建立可信度、荒诞降格让道理自明、黑色幽默面对严肃话题

### 4对内在张力

这不是脸谱化的「好奇心天才」。Skill保留了费曼的矛盾：

- 表演者 vs 思想家（盖尔曼批评他「精心制造轶事」）
- 反权威 vs 自我权威（直率有时构成另一种压迫）
- 好奇无边 vs 领域偏见（对哲学和社会科学有明确蔑视）
- 诚实原则 vs 自我神话（倡导不自欺，但自传中缺乏某些反思）

---

## 调研来源

6个调研文件，全部在 [`references/`](references/) 目录：

| 文件 | 内容 |
|------|------|
| `research.md` | 信息源清单、关键引用、矛盾与待验证 |
| `费曼著作与系统思考调研-20260404.md` | 著作全景、6个反复论点、自创概念、智识谱系 |
| `费曼长对话与即兴思考方式调研-20260404.md` | 访谈/电视中的即兴思考模式、类比策略、认知灵活度 |
| `费曼表达风格调研.md` | 表达DNA（句式/词汇/幽默/态度光谱）、经典语录索引 |
| `费曼外部评价调研.md` | Dyson/Schwinger/Gell-Mann/Bethe等同行评价、争议分析 |
| `费曼重大决策调研-20260404.md` | 10个关键决策（曼哈顿计划→挑战者号→晚年抗癌） |

### 一手来源

《别闹了，费曼先生》(1985) · 《你干嘛在乎别人怎么想》(1988) · 《发现的乐趣》(1999) · 《物理定律的本质》(1965) · 《QED》(1985) · 费曼物理学讲义 (1963-65) · Cargo Cult Science (1974) · The Value of Science (1955) · 挑战者号附录F (1986) · BBC Fun to Imagine (1983) · BBC Horizon (1981) · 给Arline的信 (1946)

### 二手来源

James Gleick《Genius》(1992) · Freeman Dyson 回忆文章 · Murray Gell-Mann 讣告与评价 · Gian-Carlo Rota 转述「12个问题」 · Paul Halpern《The Quantum Labyrinth》 · Hans Bethe (Web of Stories)

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 5个Agent并行调研（著作/对话/表达/批评/决策）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
feynman-skill/
├── README.md
├── SKILL.md                                          # 可直接安装使用
├── LICENSE
├── references/
│   ├── research.md                                   # 信息源清单
│   ├── 费曼著作与系统思考调研-20260404.md
│   ├── 费曼长对话与即兴思考方式调研-20260404.md
│   ├── 费曼表达风格调研.md
│   ├── 费曼外部评价调研.md
│   └── 费曼重大决策调研-20260404.md
└── examples/
    └── demo-conversation.md                          # 效果示例对话
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/战略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/多元思维/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---



---

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花叔](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*I'd hate to die twice. It's so boring.*

<br>

MIT License &copy; [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
