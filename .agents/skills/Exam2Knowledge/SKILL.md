---
name: Exam2Knowledge
description: 'Transforms exam questions into structured, exam-focused knowledge systems. Extracts high-frequency test points, reverse-engineers knowledge from questions, and builds pattern-recognition frameworks for instant problem-solving. Use when users provide exam papers, practice questions, or course materials for test preparation.'
argument-hint: 'Provide the question text, paste multiple questions, or describe the knowledge area to prepare'
user-invocable: true
disable-model-invocation: false
---

# Exam2Knowledge: Exam-Oriented Knowledge Extractor

This skill transforms scattered academic questions into a **targeted, exam-focused knowledge system** designed for one goal: **when you see a question, you immediately recognize the method and can produce the answer**.

Unlike systematic learning approaches that teach concepts from scratch, this skill builds a **pattern-recognition system** optimized for exam performance. It reverse-engineers what knowledge each question is testing, identifies high-frequency test points across multiple years of exams, and creates actionable frameworks for rapid response.

## Core Philosophy

**Not:** "Learn everything from A to Z"
**Yes:** "See question → Recognize pattern → Apply method → Get answer"

This skill builds an **exam-oriented knowledge hierarchy**, not a textbook chapter-by-chapter learning path.

## When to Use This Skill

Use this skill when you need to:

- **Batch Analysis**: Analyze past exam papers (multiple years), practice tests, or course materials collectively
- **High-Frequency Point Mining**: Identify which knowledge points appear most frequently across many questions
- **Reverse Engineering**: Understand what specific knowledge/concepts questions are actually testing
- **Pattern Recognition Training**: Build reflexes for instantly recognizing question types and solution methods
- **Exam Preparation**: Create targeted review materials focused on high-yield topics

### Input Scenarios
- Single question, multiple questions, or full exam papers (text or images)
- OCR results of handwritten/digital exam papers
- Course slides, homework sets, or practice problem collections
- Questions from any subject (math, physics, chemistry, biology, history, languages, etc.)

## Procedure

Follow these steps strictly to transform input questions into an exam-ready knowledge system:

### 1. Intelligent Question Comprehension (Pattern Recognition)
- Accurately identify **subject**, **grade level**, **difficulty level**, and **question type**.
- Determine the **cognitive level required** using [Bloom's Taxonomy](./references/blooms-taxonomy.md).
- **CRITICAL**: Identify the **question's hidden testing intent** — What is this question *really* testing? What knowledge pattern does it represent?
- Extract key conditions, constraints, and implicit information that signal which solution approach to use.
- Classify the question into a **recognizable pattern category** for future instant recognition.

### 2. Reverse-Engineer Knowledge Points (From Question → Knowledge)
- **Work backwards from the question**: Given this question, what *must* the student know to solve it?
- Extract all **core knowledge points**, **examination targets**, and **sub-skills** being tested.
- Structure knowledge points by **exam relevance**, not textbook order:
  - ★★★ **Must-Master** (appears frequently, high-weight in exams)
  - ★★ **Frequently Tested** (moderate frequency, important)
  - ★ **Good to Know** (occasional, bonus points)
- Map each point to its **typical question patterns** — How does this knowledge usually get tested?
- Identify **textbook chapters/sections** only as reference, not as learning sequence.

### 3. Solution Strategy & Methodology (Build Reflex Frameworks)
- Create **universal solution templates** for this *type* of question (not just this specific question).
- Identify the **"breakthrough insight"** — the key pattern recognition moment that triggers the correct method.
- Document **decision heuristics**: "When you see [X], do [Y]" rules for instant application.
- Summarize **step-by-step algorithms** that work for all variations of this question type.
- Include **time-saving techniques** and **exam-specific shortcuts**.

### 4. Common Mistakes & Traps (Error Pattern Library)
- Catalog **where students typically lose points** on this question type.
- Categorize errors using [Diagnostic Rubric](./references/diagnostic-rubric.md):
  - Conceptual misunderstandings
  - Procedural/methodological misapplications
  - Execution/calculation carelessness
  - Reading/interpretation traps
  - Edge case oversights
- Provide **self-check checkpoints** to catch mistakes before submitting.
- Include **warning signs**: "If you see [X] in the question, watch out for [Y]".

### 5. High-Frequency Pattern Correlation (Cross-Question Intelligence) ⭐
- **When analyzing multiple questions together**: Identify which knowledge points repeat most often → **High-Frequency Test Points**.
- Link current question patterns to **related patterns** that often appear on the same exam.
- List **alternative testing formats**: How might this same knowledge be tested differently next time?
- Generate **1-2 practice questions** (without answers) that test the same pattern in a new way.
- Build **knowledge clusters**: Group related patterns that tend to appear together in exams.

### 6. Exam-Ready Knowledge System Output ⭐
- Synthesize findings into a **prioritized, action-oriented review framework**.
- Organize by **exam importance**, not by learning order.
- Emphasize **recognition triggers**: What signals should alert you to apply which method?
- Include **quick-reference summaries** for last-minute review.

## Output Format

You MUST output the final result EXACTLY in the Markdown format defined in [output-template.md](./assets/output-template.md).

For **batch analysis of multiple questions/exams**, additionally provide:
1. **High-Frequency Test Points Summary**: Ranked list of most-tested knowledge points
2. **Pattern Distribution Report**: Which question types appear most often
3. **Knowledge Gap Analysis**: Areas with high question frequency but potentially weak student understanding
4. **Priority Study Plan**: Recommended order for reviewing based on exam weight and frequency

## Special Notes for Batch Processing

When users provide **multiple years of exams** or **large question sets**:
- Perform **cross-exam analysis** to identify trends: Are certain topics becoming more/less frequent?
- Calculate **frequency scores** for each knowledge point based on appearance count.
- Highlight **emerging patterns**: New question types or combinations appearing in recent exams.
- Suggest **strategic focus areas**: Where to invest limited study time for maximum return.

## References

- [Bloom's Taxonomy](./references/blooms-taxonomy.md): Cognitive level classification framework
- [Diagnostic Rubric](./references/diagnostic-rubric.md): Error categorization system
- [Output Template](./assets/output-template.md): Standardized output format specification
