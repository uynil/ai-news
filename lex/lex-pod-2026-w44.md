# Lex Fridman Podcast 周报 | 2026-W44 (10月26日 – 11月1日)

> 本期收录 1 期节目，嘉宾为 MIT 理论计算机科学家 Ankur Moitra、华盛顿大学流体力学专家 Steven Brunton、Rutgers 数论学家 Alex Kontorovich，主题为「AI 与数学的危机时刻」。

---

## #503 | AI Crisis in Math: Navier-Stokes, Riemann Hypothesis & Complexity Theory

| 字段 | 内容 |
|------|------|
| **发布日期** | 2026-10-26 |
| **嘉宾** | Ankur Moitra、Steven Brunton、Alex Kontorovich |
| **嘉宾身份** | MIT 数学系教授（理论计算机科学）、华盛顿大学机械工程教授（流体力学 / 数据驱动建模）、Rutgers 数学系杰出教授兼系主任（数论） |
| **时长** | 约 3 小时 42 分 |
| **节目链接** | [lexfridman.com/math-ai-crisis](https://lexfridman.com/math-ai-crisis/) |
| **Transcript** | [lexfridman.com/math-ai-crisis-transcript](https://lexfridman.com/math-ai-crisis-transcript/) |
| **YouTube** | [ZAzWPE9CItg](https://www.youtube.com/watch?v=ZAzWPE9CItg) |
| **音频** | [Blubrry MP3](https://media.blubrry.com/takeituneasy/ins.blubrry.com/takeituneasy/lex_ai_math_ai_crisis.mp3) |
| **本地产出** | [transcript](./2026-10-26-math_ai_crisis_transcript.md) · [summary](./2026-10-26-math_ai_crisis_summary.md) |

### 嘉宾简介

**Ankur Moitra**，MIT 数学系 Rockwell International 教授，本年度在普林斯顿高等研究院（IAS）访问；MIT CSAIL 首席研究员，计算理论组与机器学习/统计中心核心成员。

- **学术背景**：理论计算机科学与机器学习理论的交叉地带，研究目标是为机器学习中的推理问题提供**可证明保证**的算法。
- **重大贡献**：近似算法与硬度、张量分解、主题模型、稀疏恢复、矩阵补全等；著有 *Algorithmic Aspects of Machine Learning*（中译本《机器学习算法》，机械工业出版社 2021）。近期工作涉及低秩语言模型与「潜隐学习」（subliminal learning）的机制解释。
- **主要荣誉**：Packard Fellowship、Sloan Fellowship、NSF CAREER、Hertz Fellowship、2026 年 W. Wallace McDowell 奖。
- **本期角色**：复杂度理论侧的解释者——Unique Games Conjecture、P vs NP、AI 学习数学的理论基础。

**Steven L. Brunton**，华盛顿大学机械工程系教授（Boeing Professor of AI and Data-Driven Engineering），NSF 动态系统人工智能研究所（AI Institute in Dynamic Systems）副主任，应用数学系兼任副教授。

- **学术背景**：将机器学习与动力系统、控制理论结合，应用于流体力学、生物运动、光学、能源系统与制造。
- **重大贡献**：**SINDy**（稀疏非线性动力学识别）方法的开创者，可从观测数据自动发现控制方程；与 J. Nathan Kutz 合著 *Data-Driven Science and Engineering*（已出第 2 版，有中译本）。
- **科学传播**：YouTube 频道 [@Eigensteve](https://youtube.com/@Eigensteve)，以高度可视化的流体与数据科学讲座知名。
- **主要荣誉**：PECASE（美国总统青年科学家与工程师奖）、陆军与空军 YIP 奖、UW 工学院教学奖。
- **本期角色**：唯一以工程视角发言的人——Navier-Stokes 的物理意义、以及"数学结果与工程现实之间的鸿沟"。

**Alex Kontorovich**，Rutgers 大学数学系杰出教授（Distinguished Professor），2026–29 年任系主任。

- **学术背景**：普林斯顿大学数学学士（2002，Magna Cum Laude）、哥伦比亚大学博士（2007）；历任布朗（Tamarkin 助理教授）、石溪、耶鲁、Rutgers。研究解析数论，以几何空间分析发展关于整数的理论。
- **重大贡献**：2014 年以"开辟数论新领域、可阐明古老问题"的论文获 AMS **Levi L. Conant 奖**；Lean / Mathlib 生态的重要推动者，任 Lean Focused Research Organization 战略顾问、*Annals of Formalized Mathematics* 编委；2023 年创办 *Journal of the Association for Mathematical Research* 并任 managing editor，2026–27 年任该会会长。
- **科学传播**：2020–21 年任纽约数学博物馆（MoMath）"数学公共传播"杰出访问教授，创建 "Math's Greatest Hits" 等项目；Quanta 杂志科学顾问委员会成员；2026 年 ICM（费城）特别全会演讲。
- **另一重身份**：单簧管/萨克斯演奏家，克莱兹梅尔（klezmer）音乐复兴的关键人物之一，曾与格莱美奖乐团 The Klezmatics 巡演，创办 Klez Dispensers。
- **本期角色**：黎曼猜想与 Lean 形式化的解释者，也是三人中对"数学之价值"论述最系统的一位。

### 话题分段

> 以下为官网 OUTLINE / YouTube 章节时间戳。官方文字稿略去 1:58–9:53 的赞助与评论环节，故文字稿内嵌时间戳比此表**提前约 7 分 55 秒**。

| 时间 | 话题 |
|------|------|
| 00:00 | Introduction |
| 01:58 | Sponsors, Comments, and Reflections（文字稿未收录） |
| 09:53 | Crisis moment in mathematics（危机时刻：三人的真实情绪） |
| 18:10 | Will AI "solve" mathematics?（"被解决的公理"、门童谬误、凸包 vs 半群） |
| 34:21 | Can AI create new math?（Lean/Mathlib、1300 万行 FLT 形式化） |
| 1:13:53 | Riemann hypothesis（ζ 函数即"对素数做信号处理"；7/8 与 11/12 两条带） |
| 1:37:45 | Navier-Stokes（二次非线性、有限时间爆破、涡丝拉伸） |
| 2:03:42 | How nature computes（黏菌、果蝇应变神经元、外野手弧线跑位） |
| 2:12:35 | Unique Games Conjecture and complexity theory（PCP → 间隙放大 → UGC 为真） |
| 2:27:28 | How mathematicians think（师徒制、十年磨一题、"侧视"解题） |
| 2:41:05 | Is math invented or discovered?（问题发明，答案发现） |
| 2:47:13 | Can AI solve P vs NP?（worst-case 分析的功与过、beyond worst-case） |
| 2:57:28 | Why LLMs work so well（自然厌恶计算困难；"爱猫头鹰"实验） |
| 3:11:54 | Problems AI can't solve yet（P vs NP 仍在；RH 本体仍在） |
| 3:16:23 | Grigori Perelman（拒 Fields、拒 Clay；"这是最后一次 Fields 奖吗？"） |
| 3:25:41 | Advice for young people（本科生双峰分布、"假装已有终身教职"、无聊的价值） |

### 要点摘要

OpenAI 在三天前一次性放出约 700 个数学结果（据嘉宾转述，成功率约 10%），其中包含准黎曼猜想、三维 Navier-Stokes 带外力版本的有限时间爆破反例、以及 Unique Games Conjecture 为真。本期是 Lex 组织的"紧急插播"，用三位当事人的视角拆解这个事件。

1. **「解题」被商品化，与它正交的能力随之升值**。Moitra 提出"门童谬误"：把数学家的职业压缩成"证明定理"这一最可见动作，是范畴错误——正如把门童压缩成"开门"就以为自动门能替代他。与此对应，Kontorovich 的判据更锋利：AI 在**广度**上击败任何人类（读完了所有论文），但在**深度**上尚未展示真正的新想法；准 RH 的证明是"一长串全部已知动作的级联"，更像半群式铺开（瓦片可以向四周无限铺）而非凸包内的线性组合。

2. **形式化已被解决，但"可理解的数学"没有**。Anthropic 以 1300 万行 Lean 代码证完费马大定理（sorry-free），参与人数仅 2–3 人，主要提示词是"Continue"，且无该领域专业知识——Kontorovich 两天前在普林斯顿刚预言"这需要很久"，随后"每一句话都错了"。但他强调这"不是漂亮的证明"，AI 仍不擅长 canonization（把草率代码重构为库中规范形式），而"故事 + 形式化背书"才是未来论文的形态。

3. **三大学科各自的结论差异极大，取决于"结果离工程有多远"**。黎曼猜想侧：准 RH 给出 Re(s) ∈ [7/8, 1] 的整条无零点带（七十年来零无零点区域厚度未动），其方法"在原理上无法降到 1/2"，仍需新想法。Navier-Stokes 侧：证明的是三维带光滑外力版本的爆破反例，机制是涡丝拉伸变细如花样滑冰收臂；但 Brunton 给出全场最冷静的判断——"我们解决了一百万美元的数学问题，还存在一个一万亿美元的工程问题"，日常流体工程"几乎完全没有变化"。

4. **AI 的真实影响不止于解题数量，而是重画了研究地貌**。3SUM 的加速使 fine-grained complexity 从"应当合并研究"退回"也许该分开研究"；UGC 为真则一次性确定了一大批 CSP 问题的最优近似算法。代价是博士生"改进一个大家关心的问题"这条成才蓝图失效，期刊与审稿系统本已过载。Moitra 另提出一个隐忧：既然关键新想法一旦公开就可能被 AI 穷尽式铺开，数学家可能变得保守——"那会是我们不该失去的东西"。

5. **最终的落点是非技术命题：稀缺性重排之后人的位置**。Moitra 用「假装你已经拿到终身教职」对抗焦虑；Kontorovich 用乘法表与计算器的七十年教训论证"机器能做不等于你不必会"；Brunton 则给出排序——FLT 被证明那天他去海滩和孩子扔球，"那才是我生命的意义，这些别的东西是上面的樱桃"。

---

*下期预告：持续关注 Lex Fridman Podcast 最新动态。*
