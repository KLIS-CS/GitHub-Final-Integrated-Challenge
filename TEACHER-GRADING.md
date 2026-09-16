# Teacher Grading — Checkpoint 5

Final score: **60 automatic + 40 teacher-reviewed = 100**.

CP5 now grades a **separately created public student repository**. Students submit that repository through the central CP5 Submission Issue Form in this KLIS-CS repository.

## Manual Rubric — 40 points

| Category | Full-credit evidence | Points |
|---|---|---:|
| Workflow independence | Student created the repository from scratch and completed the integrated workflow without relying on step-by-step copying | 10 |
| GitHub Project evidence | CP5 Issue appears in a Project and moved through sensible statuses | 5 |
| Conceptual explanations | Accurate explanations of branch, commit/push, origin, Issue, and PR | 10 |
| Debugging / recovery reasoning | Diagnoses repository state first and proposes safe recovery for all scenarios | 10 |
| Reflection | Specific and connected to development workflow decisions or risk reduction | 5 |
| **Total** |  | **40** |

## What to review

From the student's central CP5 Submission Issue, open the submitted practice repository and verify:

1. the repository was created by the student rather than forked/copied from a template;
2. repository setup quality (`README.md`, `.gitignore`, LICENSE);
3. the `[CP5]` Issue and GitHub Project evidence;
4. the `cp5-USERNAME` feature branch and meaningful commit(s);
5. the open Pull Request into `main` and its closing Issue reference;
6. the student's conceptual and debugging responses in the submission Issue.

## Entering the Teacher Grade

The grader posts a **Teacher grading** block in the central CP5 Submission Issue. Copy it into a new Issue comment and replace the scores:

```text
/manual-grade
Workflow independence: 0/10
Project evidence: 0/5
Concepts: 0/10
Debugging: 0/10
Reflection: 0/5

Feedback:
Write concise feedback here.
```

The workflow calculates the 40-point teacher subtotal automatically and combines it with the automatic 60 points.

Example:

```text
/manual-grade
Workflow independence: 10/10
Project evidence: 5/5
Concepts: 9/10
Debugging: 9/10
Reflection: 5/5

Feedback:
Strong integrated workflow. Your recovery strategy is state-first; make the distinction between commit and push slightly more explicit.
```

The newest valid grading comment by `hbycwyh2008` is used. The short form remains accepted for compatibility:

```text
/manual-grade 38
```
