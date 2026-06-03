# Error Diagnostic Rubric

5-category mistake classification. Use to catalog and prevent recurring errors.

## Contents

1. [Quick Picker](#quick-picker)
2. [Categories](#categories)
3. [Subject Profiles](#subject-profiles)

---

## Quick Picker

Run this **decision flow** on each error:

```
Wrong answer received
  → Did the student misunderstand what was asked?        YES → C1 Reading
  → Did the student use a wrong concept/definition?      YES → C2 Conceptual
  → Did the student apply a method incorrectly?          YES → C3 Procedural
  → Did the student make a mechanical slip (sign, arithmetic)? YES → C4 Execution
  → Did the student miss a constraint (domain, boundary)? YES → C5 Edge Case
  → None of the above                                   → Re-examine
```

---

## Categories

| ID | Type | Signal Phrase | Prevention |
|----|------|---------------|------------|
| C1 | Reading | "Misread the question" | Re-read question 30s; circle key words (NOT, EXCEPT) |
| C2 | Conceptual | "Wrong idea/model" | Verify definition + preconditions before applying |
| C3 | Procedural | "Used wrong method" | Checklist steps; verify preconditions for formula |
| C4 | Execution | "Calculation mistake" | Scan signs first; re-do calculation from error point |
| C5 | Edge Case | "Missed a special case" | Substitute answer back; check domain/boundary |

**Detail by type:**

- **C1 Reading** (most common, ~22%) — Missed keywords (NOT, EXCEPT), wrong quantity, assumed unstated info. *Fix:* Re-read + highlight constraints.
- **C2 Conceptual** (~17%) — Analogy mismatch, definition conflation, overgeneralized rule. *Fix:* Confirm concept + preconditions first.
- **C3 Procedural** (~15%) — Precondition violated, step omitted, wrong substitution. *Fix:* Count steps; verify each.
- **C4 Execution** (~19%) — Sign errors (#1 sub-type), arithmetic, transcription. *Fix:* Sign-scan first; reverse-verify.
- **C5 Edge Case** (~12%) — Extraneous solution, domain violation, boundary ignored. *Fix:* Substitute back; check domain.

---

## Subject Profiles

| Subject | Dominant | Secondary | Top Traps |
|---------|----------|-----------|-----------|
| Algebra | C4 Execution | C5 Edge Case | Radical extraneous solutions; exponent sign errors |
| Calculus | C3 Procedural | C2 Conceptual | L'Hôpital misuse; missing endpoints |
| Statistics | C1 Reading | C2 Conceptual | z vs t-test; one-tailed vs two-tailed |
| Physics | C2 Conceptual | C1 Reading | F=ma in rotation; vector components |
| Chemistry | C5 Edge Case | C4 Execution | Limiting reagent; significant figures |
| CS | C3 Procedural | C2 Conceptual | Off-by-one; null/empty case |

**Usage tip:** When analyzing a question type, pre-load its dominant category and check those patterns first.
