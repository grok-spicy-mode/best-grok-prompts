# Best Grok Prompts - Grok AI 的终极提示词集合

[Español](README_es.md) | [English](README.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [العربية](README_ar.md) | [한국어](README_ko.md) | [Tiếng Việt](README_vi.md) | [日本語](README_ja.md) | **简体中文** | [繁體中文](README_zh-TW.md)

---

<div align="center">

<a href="https://grokprompts.app">
  <img src="assets/banner.png" alt="Best Grok Prompts - 1000+ AI Prompts for Every Use Case" width="800">
</a>

**[免费探索所有提示词 →](https://grokprompts.app)**

![Best Grok Prompts](https://img.shields.io/badge/Grok_Prompts-1000%2B-blue?style=for-the-badge)
![Categories](https://img.shields.io/badge/Categories-12-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**为每个 Grok 使用场景精心策划、测试和组织的提示词**

[在 GrokPrompts.app 上探索](https://grokprompts.app) • [贡献](#贡献) • [指南](#指南)

</div>

---

## 这是什么?

这个仓库包含 GitHub 上**最全面的 best grok prompts 集合**。每个提示词都经过 Grok AI 测试并针对实际使用场景进行了优化。无论您是编程、写作、分析数据还是生成图像,都能在这里找到可用于生产环境的 grok prompts。

**为什么使用这些 Grok prompts?**
- 已通过 Grok Free、Grok Premium 和 Spicy Mode 测试
- 按使用场景分类,便于快速发现
- 即插即用 - 无需修改
- 定期更新,包含社区贡献
- 针对 Grok 的独特功能进行优化(实时数据、图像/视频生成)

> 在 **[GrokPrompts.app](https://grokprompts.app)** 浏览我们包含 1000+ 提示词的完整可搜索库

---

## 目录

- [快速开始](#快速开始)
- [提示词类别](#提示词类别)
- [前 20 个 Best Grok Prompts](#前-20-个-best-grok-prompts)
- [优秀 Grok Prompt 的要素](#优秀-grok-prompt-的要素)
- [Grok vs ChatGPT Prompts](#grok-vs-chatgpt-prompts)
- [指南](#指南)
- [模板](#模板)
- [常见问题](#常见问题)
- [贡献](#贡献)
- [资源](#资源)

---

## 快速开始

1. 浏览下面的[提示词类别](#提示词类别)
2. 点击类别查看所有提示词
3. 复制提示词文本并粘贴到 Grok
4. 根据需要调整变量(括号内)
5. 获得出色结果

**专业提示:** 为这个仓库加星以便随时使用这些 best grok prompts!

---

## 提示词类别

| 类别 | 提示词 | 难度 | 最适合 |
|----------|---------|------------|----------|
| [编程与开发](prompts/coding-development.md) | 20 | ⭐⭐ | 开发者、工程师 |
| [写作与内容](prompts/writing-content.md) | 18 | ⭐ | 作家、营销人员 |
| [数据分析](prompts/data-analysis.md) | 17 | ⭐⭐⭐ | 分析师、研究人员 |
| [创意头脑风暴](prompts/creative-brainstorming.md) | 15 | ⭐ | 企业家、创作者 |
| [商业与营销](prompts/business-marketing.md) | 19 | ⭐⭐ | 营销人员、创始人 |
| [教育与学习](prompts/education-learning.md) | 16 | ⭐ | 学生、教育工作者 |
| [图像生成](prompts/image-generation.md) | 20 | ⭐⭐ | 设计师、艺术家 |
| [视频生成](prompts/video-generation.md) | 15 | ⭐⭐⭐ | 视频创作者 |
| [Spicy Mode](prompts/spicy-mode.md) | 18 | ⭐⭐⭐ | 高级用户 |
| [生产力](prompts/productivity.md) | 17 | ⭐ | 专业人士 |
| [研究与学术](prompts/research-academic.md) | 16 | ⭐⭐⭐ | 研究人员、学生 |
| [娱乐与休闲](prompts/fun-entertainment.md) | 15 | ⭐ | 所有人 |

**总计: 206+ 个手动测试的 grok prompts**

---

## 前 20 个 Best Grok Prompts

这些是我们集合中最有效和最通用的 grok prompts。每个都可以在多个 Grok 级别上工作,并提供一致的高质量结果。

### 1. 实时网络分析
```
实时分析[平台/主题]上当前的热门话题。提供:
- 前5个热门项目及其背景
- 每个热门的原因(数据支持)
- 情感分析
- 未来24小时预测
格式化为新闻简报。
```
**为什么有效:** 利用 Grok 的实时数据访问 - ChatGPT 无法实现
**适用于:** Grok Premium、Spicy Mode

---

### 2. 代码调试专家
```
你是精英调试助手。我会提供有错误的代码。你的回复:
1. 识别确切的错误(行号)
2. 解释为什么失败
3. 提供修正后的代码
4. 建议2种防止类似错误的方法

[在此粘贴你的代码]
```
**为什么有效:** 结构化输出确保全面调试
**适用于:** 所有 Grok 级别

---

### 3. X/Twitter 话题串生成器
```
创建关于[主题]的病毒式 X 话题串:
- 钩子推文(最多280字符,停止滚动)
- 8-12条有价值的推文
- 每条推文: 一个关键见解
- 最终 CTA 推文
- 包含相关标签
格式: 推文 1/12、推文 2/12 等
```
**为什么有效:** 针对 Grok 的 X 集成和病毒式传播机制优化
**适用于:** 所有 Grok 级别

---

### 4-20. [其他提示词]

提示词 4-20 包括: 图像生成导演、商业战略顾问、学习路径创建者、数据洞察分析师、内容重用引擎、Spicy Mode 无审查分析师、视频概念设计师、竞争对手情报报告、提示词改进器、危机沟通撰写人、病毒式钩子生成器、技术文档撰写人、趋势预测者、会议笔记摘要器、A/B 测试假设生成器、角色故事构建器和 SEO 内容优化器。

> **在 [GrokPrompts.app](https://grokprompts.app) 发现 180+ 个 best grok prompts** - 可搜索、已分类、免费。

---

## 优秀 Grok Prompt 的要素

best grok prompts 具有以下特征:

### 1. 利用 Grok 的独特优势
与 ChatGPT 不同,Grok 擅长于:
- **实时数据访问**: 当前事件、热门话题、实时市场数据
- **X/Twitter 集成**: 深入理解社交媒体动态
- **图像生成**: 内置 FLUX 模型生成高质量图像
- **视频生成**: 原生视频创建功能
- **无审查模式**: 用于争议性/未过滤分析的 Spicy Mode

**示例:** 不要用通用的"分析这个话题",而是用"分析过去6小时 X 上关于[主题]的当前趋势数据"。

### 2-6. [其他要素]

包括提供清晰结构、指定输出格式、包含上下文和约束、尽可能使用示例、以及迭代和链接提示词。

**了解更多:** 查看我们的[Grok 提示词工程](guides/prompt-engineering-for-grok.md)指南。

---

## Grok vs ChatGPT Prompts

并非所有提示词在所有 AI 模型上都同样有效。以下是如何针对 Grok 进行优化:

| 功能 | ChatGPT Prompts | Grok Prompts | 优胜者 |
|---------|-----------------|--------------|--------|
| **实时数据** | 有限(训练截止) | 完全访问当前网络 | Grok |
| **社交媒体** | 通用理解 | 与 X 深度集成 | Grok |
| **图像生成** | 需要 DALL-E API | 内置 FLUX 模型 | Grok |
| **视频创作** | 不可用 | 原生视频生成 | Grok |
| **无审查模式** | 高度过滤 | Spicy Mode 可用 | Grok |
| **推理深度** | 优秀 | 非常好 | ChatGPT |
| **代码生成** | 优秀 | 非常好 | ChatGPT |
| **长篇内容** | 优秀 | 非常好 | ChatGPT |

**阅读完整比较:** [Grok vs ChatGPT Prompts 指南](guides/grok-vs-chatgpt-prompts.md)

---

## 指南

通过我们的综合指南掌握 Grok 提示词:

- **[Grok 提示词工程](guides/prompt-engineering-for-grok.md)** - 编写有效 grok prompts 的完整指南
- **[Grok vs ChatGPT Prompts](guides/grok-vs-chatgpt-prompts.md)** - 何时使用哪个 AI 以及如何调整提示词
- **[Grok 入门](guides/getting-started-with-grok.md)** - Grok AI 初学者指南
- **[高级技巧](guides/advanced-techniques.md)** - 思维链、少样本学习和元提示

---

## 模板

常见任务的可重用提示词模板:

- **[编程模板](templates/coding-template.md)** - 软件开发提示词
- **[写作模板](templates/writing-template.md)** - 内容创作提示词
- **[分析模板](templates/analysis-template.md)** - 数据和研究提示词
- **[图像模板](templates/image-template.md)** - 图像生成提示词

复制、自定义并立即使用。

---

## 常见问题

### 什么是 Grok AI?
Grok 是由 xAI(埃隆·马斯克的 AI 公司)创建的 AI 助手。它具有实时网络访问、X/Twitter 集成以及内置的图像/视频生成功能。

### 什么是 Spicy Mode?
Spicy Mode 是 Grok 的无审查模式,提供未经过滤的直接回复,没有企业护栏。Grok Premium 可用。

### 这些提示词可以免费使用吗?
是的,此仓库中的所有提示词都采用 MIT 许可。随意使用 - 个人或商业用途。

### 它们可以与 Grok Free 一起使用吗?
大多数提示词可与 Grok Free 一起使用。需要实时数据、图像生成或 Spicy Mode 的提示词需要 Grok Premium。

### 提示词多久更新一次?
我们每周添加新的 grok prompts。为仓库加星以获取更新通知。

### 我可以贡献自己的提示词吗?
当然可以! 通过 [GitHub Issues](https://github.com/grok-spicy-mode/best-grok-prompts/issues) 提交。我们会审查所有提交。

### 在哪里可以找到更多提示词?
访问 **[GrokPrompts.app](https://grokprompts.app)** 获取包含所有类别的 1000+ grok prompts 的可搜索数据库。

### 它们与 ChatGPT 提示词相比如何?
Grok prompts 针对 Grok 的优势(实时数据、X 集成、图像/视频生成)进行了优化。查看我们的[比较指南](guides/grok-vs-chatgpt-prompts.md)。

---

## 贡献

我们欢迎贡献! 方法如下:

1. Fork 此仓库
2. 将您的提示词添加到适当的类别文件
3. 遵循现有文件中使用的提示词格式
4. 使用 Grok 测试您的提示词
5. 提交 Pull Request

**质量标准:**
- 提示词必须经过测试且有效
- 包含示例输出(可选但建议)
- 指定需要哪个 Grok 级别
- 解释为什么提示词有效

有问题? 打开 [GitHub Issue](https://github.com/grok-spicy-mode/best-grok-prompts/issues)

---

## 资源

### 官方
- [Grok AI](https://grok.x.ai/) - Grok 官方网站
- [X Premium](https://twitter.com/i/premium_sign_up) - 订阅以访问 Grok
- [xAI](https://x.ai/) - Grok 背后的公司

### 社区
- **[GrokPrompts.app](https://grokprompts.app)** - 最大的 Grok 提示词库(1000+ 提示词)
- [Grok Subreddit](https://reddit.com/r/grok) - 社区讨论
- [X #GrokAI](https://twitter.com/search?q=%23GrokAI) - 最新 Grok 更新

### 学习
- [提示词工程指南](https://www.promptingguide.ai/) - 通用提示词工程
- [Grok 文档](guides/getting-started-with-grok.md) - 我们的初学者指南

---

## 许可证

MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

---

## 星标历史

如果您觉得这些 best grok prompts 有用,请为仓库加星!

<div align="center">

**由 Grok 社区用 ❤️ 制作**

[探索更多提示词](https://grokprompts.app) • [报告问题](https://github.com/grok-spicy-mode/best-grok-prompts/issues) • [请求提示词](https://github.com/grok-spicy-mode/best-grok-prompts/issues/new)

</div>
