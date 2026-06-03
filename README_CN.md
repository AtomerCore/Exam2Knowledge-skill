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
</p>

---

## ✨ 功能简介

将考试题目转换为**结构化的应试知识体系**。不是系统学习——而是构建**模式识别反射**，实现快速解题。

**适用场景：** 往年试卷、练习题、课件资料 → 高频考点提炼 → 战略性复习计划

## 📁 项目结构

```
.agents/skills/Exam2Knowledge/
├── SKILL.md                  # 核心定义 + 处理流程
├── assets/
│   └── output-template.md    # 标准化输出结构
└── references/
    ├── blooms-taxonomy.md    # 6 级认知层级
    └── diagnostic-rubric.md  # 5 类错误分类
```

## ⚙️ 工作原理

1. **模式识别** — 识别题型和认知层级（[Bloom 分类法](.agents/skills/Exam2Knowledge/references/blooms-taxonomy.md)）
2. **逆向工程** — 提取并分级知识点（[***] 必掌握 到 [*] 选修）
3. **解题模板** — 构建通用步骤 + 决策规则
4. **错误模式库** — 按类别归类错误（[诊断量表](.agents/skills/Exam2Knowledge/references/diagnostic-rubric.md)）
5. **跨题目智能分析** — 频率排名 + 聚类 + 趋势（批量模式）
6. **应试就绪输出** — 优先级行动框架（[输出模板](.agents/skills/Exam2Knowledge/assets/output-template.md)）

## 🎯 决策规则

| 场景 | 行动策略 |
|------|----------|
| 单道题目 | 完整 5 步分析 + 解题模板 |
| 多道题目（≥5） | 增加频率统计 + 聚类分析 |
| 时间紧迫（≤7 天） | 仅输出 [***] + 模板 |
| 时间紧迫（≤3 天） | 仅输出 [***] + 速查框架 |
| 弱项诊断 | 强化错误模式分析 |
| 图片/OCR 输入 | 先校验识别准确性 |
| 学科为文科 | 切换文科分析模式 |

## ✨ 核心特性

- 🎯 **5 步处理流程**，严格按顺序执行
- 🔀 **条件逻辑** — 根据输入类型和时间约束自动调整输出
- ✅ **内置自检** — 格式、内容、一致性、边界四重验证
- 📚 **分级知识** — [***] / [**] / [*] 按考试频率排序
- 🛡️ **能力边界** — 显式声明"能做 / 不能做"
- 🌍 **文科模式** — 针对非 STEM 学科的专门处理

## 📥 支持输入

- ✅ 单道/多道题目或完整试卷（文本格式）
- ✅ 手写试卷的 OCR 结果
- ✅ 所有学科：数学、物理、化学、生物、历史、语言等...
- ❌ 原始图片输入（需先提供 OCR 文本）

## 📄 许可证

[MIT](LICENSE)

---
