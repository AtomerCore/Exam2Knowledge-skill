# Error Diagnostic Rubric

5-category mistake classification system.

## Contents

1. [Ranking](#ranking) 2. [Categories](#categories) 3. [Flowchart](#flowchart) 4. [Profiles](#profiles)

---

## Ranking

| # | Type | % |
|---|------|---|
| 1 | Reading | ~22 |
| 2 | Execution | ~19 |
| 3 | Conceptual | ~17 |
| 4 | Procedural | ~15 |
| 5 | Edge Case | ~12 |

---

## Categories

**C1 Conceptual (17%)** — Wrong mental model. Types: Analogy mismatch | Definition conflation | Overgeneralized rule. *Fix:* Verify concept + preconditions

**C2 Procedural (15%)** — Applied incorrectly. Types: Precondition violated | Step omission | Wrong substitution. *Fix:* Checklist + count steps

**C3 Execution (19%)** — Mechanical slips. Types: Sign errors (32%, #1) | Arithmetic | Transcription. *Fix:* Scan signs first + re-do from error

**C4 Reading (**22% — #1**)** — Parse failure. Types: Missed keyword ("NOT") | Wrong quantity | Assumed info. *Fix:* Re-read question (30s)

**C5 Edge Case (12%)** — Violates constraints. Types: Extraneous solution | Domain violation | Boundary ignored. *Fix:* Substitution check mandatory

---

## Flowchart

```
Wrong → Understand? NO→C4 | YES→Concept? NO→C1 | YES→Method? NO→C2 | YES→Execute? NO→C3 | YES→Constraint? YES→C5 | NO→OK
```

---

## Profiles

| Subject | Dominant | Secondary | Traps |
|---------|----------|-----------|-------|
| Algebra | C3 | C5 | Radical extraneous; exponents |
| Calculus | C2 | C1 | L'Hôpital misuse; endpoints |
| Statistics | C4 | C1 | z vs t; one/two-tailed |
| Physics | C1 | C4 | F=ma rotation; vectors |
| Chemistry | C5 | C3 | Limiting reagent; sig figs |
| CS | C2 | C1 | Off-by-one; null case |
