<h1 align="center">
  🎓 Exam2Knowledge <br/>
  <sub>(Exam2Knowledge.skill)</sub>
</h1>

<p align="center">
  中文 | <a href="README.md">English</a>
</p>

<p align="center">
  <em>"看到题目 → 识别模式 → 应用方法 → 得到答案"</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
  <img src="https://img.shields.io/badge/AgentSkills-Standard-green.svg" alt="Agent Skills Standard" />
  <a href="https://github.com/AtomerCore/Exam2Knowledge-skill/stargazers"><img src="https://img.shields.io/github/stars/AtomerCore/Exam2Knowledge-skill.svg?style=flat&label=Stars" alt="Stars" /></a>
</p>

---

## ✨ 功能简介

将考试题目转换为**结构化的应试知识体系**。不是系统学习——而是构建**模式识别反射**，实现快速解题。

**适用场景：** 往年试卷、练习题、课件资料 → 高频考点提炼 → 战略性复习计划

## 📁 项目结构

```
.agents/skills/Exam2Knowledge/
├── SKILL.md              # 核心定义（~135 词）
├── assets/
│   └── output-template.md   # 模板结构（~95 词）
└── references/
    ├── blooms-taxonomy.md    # 认知层级（~180 词）
    └── diagnostic-rubric.md  # 错误分类（~190 词）
```

## ⚙️ 工作原理

1. **模式识别** — 识别题型和认知层级（[Bloom 分类法](.agents/skills/Exam2Knowledge/references/blooms-taxonomy.md)）
2. **逆向工程** — 提取并排序知识点（[***] 必掌握 到 [*] 选修）
3. **反射框架** — 构建通用解题模板（覆盖 80%+ 变体）
4. **错误模式库** — 按类别归类错误（[诊断量表](.agents/skills/Exam2Knowledge/references/diagnostic-rubric.md)）
5. **跨题目智能分析** — 频率排名 + 聚类 + 趋势（批量模式）
6. **应试就绪输出** — 优先级行动框架（[输出模板](.agents/skills/Exam2Knowledge/assets/output-template.md)）

## 🎯 决策规则

| 场景             | 行动策略                |
| ---------------- | ----------------------- |
| 单道题目         | 完整分析 + 解题模板     |
| 多道题目         | 增加频率排名 + 趋势分析 |
| 时间紧迫（<2周） | 仅聚焦 [***] 必掌握内容 |
| 弱项科目         | 针对特定错误模式        |

## 📥 支持输入

- ✅ 单道/多道题目或完整试卷（文本/图片）
- ✅ 手写试卷的 OCR 结果
- ✅ 所有学科：数学、物理、化学、生物、历史、语言等...

## 📄 许可证

[MIT](LICENSE)

---
