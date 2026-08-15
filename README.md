

<h1 align="center">
  🎓 Exam2Knowledge <br/>
  <sub>v1.0.0</sub>
</h1>

<p align="center">
  <a href="README_CN.md">中文</a> | English
</p>

<p align="center">
  <em>"See question → Recognize pattern → Apply method → Get answer"</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version: 1.0.0" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" />
  <img src="https://img.shields.io/badge/AgentSkills-Standard-green.svg" alt="Agent Skills Standard" />
</p>

---

## ✨ What It Does

Transforms exam questions into **structured, exam-focused knowledge systems**. Not systematic learning — this builds a **pattern-recognition reflex** for instant problem-solving.

**Perfect for:** Past exam papers, practice questions, course materials → High-frequency test points → Strategic study plan

## 📁 Structure

```
.agents/skills/Exam2Knowledge/
├── SKILL.md                  # Core definition + processing pipeline
├── assets/
│   └── output-template.md    # Standardized output structure
└── references/
    ├── blooms-taxonomy.md    # 6-level cognitive hierarchy
    ├── diagnostic-rubric.md  # 5-category error classification
    └── quantified-rubric.md  # Quantified self-check standards
```

## ⚙️ How It Works

1. **Pattern Recognition** — Identify question type & cognitive level ([Bloom's Taxonomy](.agents/skills/Exam2Knowledge/references/blooms-taxonomy.md))
2. **Reverse Engineering** — Extract & tier knowledge points ([***] Must-Master to [*] Optional)
3. **Solution Template** — Build universal steps + decision rules
4. **Error Pattern Library** — Catalog mistakes by category ([Diagnostic Rubric](.agents/skills/Exam2Knowledge/references/diagnostic-rubric.md))
5. **Cross-Question Intelligence** — Frequency ranking + clusters + trends (batch mode; self-check standards in [Quantified Rubric](.agents/skills/Exam2Knowledge/references/quantified-rubric.md))
6. **Exam-Ready Output** — Prioritized action framework ([Output Template](.agents/skills/Exam2Knowledge/assets/output-template.md))

## 🎯 Decision Rules

| Scenario | Action |
|----------|--------|
| Single question | Full 5-step analysis + solution template |
| Multiple questions (≥5) | + frequency statistics + clusters |
| Weak spot diagnosis | Strengthen error pattern analysis |
| Image/OCR input | Verify OCR accuracy first |
| Humanities subject | Switch to humanities analysis mode |

## ✨ Key Features

- 🎯 **5-step processing pipeline** with strict execution order
- 🔀 **Conditional logic** — output adapts to input type & time constraint
- ✅ **Built-in self-check** — format, content, consistency, boundary verification
- 📚 **Tiered knowledge** — [***] / [**] / [*] frequency-based ranking
- 🛡️ **Capability boundaries** — explicit "can do / cannot do" declaration


## 📥 Supported Input

- ✅ Single/multiple questions or full exam papers (text format)
- ✅ OCR results from handwritten exams
- ✅ All subjects: Math, Physics, Chemistry, Biology, History, Languages...
- ❌ Raw image input (require OCR text first)

## 📄 License

[MIT](LICENSE)

---
