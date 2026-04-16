# Contributing to Vigorware

[English](#contributing) | [中文](#贡献指南)

---

## Contributing

Thank you for your interest in Vigorware.

Vigorware is not a code project — at least not yet. It is a set of **conceptual propositions** about the next-generation software paradigm. Contributing here means **participating in an ongoing academic dialogue about the nature of software**.

We welcome challenges, critiques, and extensions, but we also ask that every contribution reflects genuine, careful thought.

### Core Axioms vs. Open Territory

#### 🔒 Core Axioms

The four foundational axioms are not open for removal via PR (though we welcome improvements to how they are articulated):

- Probabilistic Coexistence
- Runtime Mutability
- Multi-Agent Collaboration
- Intent-First Design

> If you believe these axioms are fundamentally flawed, we encourage you to open a Discussion rather than a PR. A well-reasoned refutation is a valuable contribution — but its place is the discussion forum, not a direct edit to core documents.

#### 🔓 Open Territory

The following areas are fully open for original exploration:

- Deepening, formalizing, or challenging the six core characteristics
- New theoretical essays (consistency models, type systems, security analysis, etc.)
- Application scenario analysis
- Comparative studies with other paradigms
- Historical and philosophical perspectives

### Contribution Types

| Type                  | Description                                                     | Method                   |
| --------------------- | --------------------------------------------------------------- | ------------------------ |
| 🐛 **Errata**         | Factual errors, logical gaps, inaccurate references             | Issue or PR              |
| 📝 **Polish**         | Wording improvements, structural refinement                     | PR                       |
| 🌐 **Translation**    | Multilanguage translation                                       | PR                       |
| 💬 **Discussion**     | Questioning, extending, or connecting core concepts             | Discussion               |
| 📄 **Original Essay** | New theoretical exploration within the Vigorware framework      | PR (open an Issue first) |
| 🔬 **Formalization**  | Translating conceptual claims into formal definitions or models | PR (open an Issue first) |

### Writing Standards

- Every essay should present a clear **thesis**, not merely survey a topic
- Significant claims require **evidence** — logical reasoning, analogy, citation, or counterexample analysis
- Maintain a balance between academic rigor and readability
- Avoid marketing language
- Honestly discuss limitations and boundaries

### Code of Conduct

- **Critique ideas, not people**
- **Assume good faith**
- **Embrace uncertainty** — this is an exploratory project
- **Respect diverse perspectives**

---

## 贡献指南

感谢你对 Vigorware 的关注。

Vigorware 不是一个代码项目——至少目前还不是。它是一组关于下一代软件存在形态的**概念性主张**。因此，这里的「贡献」不是提交代码，而是**参与一场关于软件本质的持续学术对话**。

我们欢迎挑战、质疑和延伸，但也要求每一项贡献都经过认真的思考。

### 核心公理与开放领域

在贡献之前，请理解 Vigorware 的知识结构分为两层：

#### 🔒 核心公理（Core Axioms）

以下四项公理构成 Vigorware 的理论基石，我们不接受试图否定这些公理的贡献（但欢迎对其表述方式的改进）：

- 概率性共存
- 运行时可变性
- 多主体协作
- 意图优先

> 如果你认为这些公理本身存在根本性缺陷，我们建议你发起 Discussion 而非直接提交 PR。好的反驳同样是珍贵的贡献——但它的归宿是讨论区，而非直接修改核心文档。

#### 🔓 开放领域（Open Territory）

以下方向完全开放，我们积极欢迎原创性探索：

- 核心特征（六项特征）的深化、形式化或挑战
- 新的理论文章（如一致性模型、类型系统、安全性分析等）
- 具体应用场景的推演
- 与其他范式（Software 2.0、自主计算、Actor Model 等）的比较研究
- 历史与哲学层面的思辨

### 贡献类型

按参与深度由浅入深排列：

| 类型            | 说明                               | 方式                          |
| --------------- | ---------------------------------- | ----------------------------- |
| 🐛 **勘误**     | 事实性错误、逻辑漏洞、引用不准确   | Issue 或 PR                   |
| 📝 **润色**     | 措辞改进、结构优化、可读性提升     | PR                            |
| 🌐 **翻译**     | 各国语言翻译与本地化               | PR                            |
| 💬 **讨论**     | 对核心概念的质疑、延伸、联想       | Discussion                    |
| 📄 **原创文章** | 在 Vigorware 框架下的新理论探索    | PR（需先开 Issue 讨论选题）   |
| 🔬 **形式化**   | 将概念性主张转化为形式化定义或模型 | PR（需先开 Issue 讨论方法论） |

### 写作规范

思想性仓库的质量取决于写作的严谨性。请遵守以下规范：

**结构要求：**

- 每篇文章应有明确的**论点（Thesis）**，而非仅仅是话题的罗列
- 重要主张需提供**论据**——可以是逻辑推演、类比论证、文献引用或反例分析
- 涉及已有工作时，需给出**准确的引用或归属**

**风格要求：**

- 保持学术性与可读性的平衡——不追求晦涩，但拒绝空洞
- 避免营销性语言（如「颠覆性」「革命性」「碾压」）
- 承认局限性。诚实地讨论一个想法的边界，比夸大其适用范围更有价值

**格式要求：**

- 使用 Markdown 格式
- 各国语言文档请放入`docs/`对应的语言文件夹中，如中文文档存放于 `docs/zh_CN/`，英文文档存放于 `docs/en/`
- 文件名应为文章标题的简明表述
- 如果包含图表，请使用 Mermaid 或提供可编辑的源文件

### 提交原创文章的流程

1. **开 Issue 讨论选题**  
   简要描述你想探讨的问题、你的初步论点以及它与 Vigorware 框架的关联。这一步是为了避免重复工作，也让社区有机会在早期提供反馈。

2. **撰写初稿并提交 PR**  
   在 PR 描述中说明文章的核心论点和主要结论。

3. **Review 与迭代**  
   维护者和社区成员将从以下维度进行 Review：
   - **逻辑一致性** — 论证链是否完整、是否存在跳跃？
   - **与框架的关系** — 是延伸、补充还是挑战？关系是否清晰？
   - **原创性** — 是否提供了新的洞察，而非重述已有观点？
   - **诚实性** — 是否公正地讨论了局限和反论？

4. **合并与归属**  
   合并后，文章将在文档索引中列出，并注明作者归属。

### 关于署名

这是一个思想性项目，我们尊重每一位贡献者的智识劳动：

- 原创文章将保留作者署名
- 重大的概念性贡献（如提出新的子理论）将在文档中致谢
- 所有贡献者将列入 Contributors 列表

### 行为准则

思想的碰撞需要安全的环境。我们要求所有参与者：

- **对事不对人** — 批评论点，而非批评提出论点的人
- **善意假定** — 假设对方的出发点是建设性的
- **接受不确定性** — 这是一个探索性项目，没有人掌握全部答案
- **尊重多元视角** — 不同学科背景和思维方式的碰撞正是本项目的价值所在

---

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
