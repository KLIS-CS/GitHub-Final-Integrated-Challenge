# Teacher Grading — Checkpoint 5

Final score: **60 automatic + 40 teacher-reviewed = 100**.

## Manual Rubric — 40 points

| Category | Full-credit evidence | Points |
|---|---|---:|
| Independent workflow quality | Student completed the integrated process without relying on step-by-step copying | 10 |
| GitHub Project evidence | Issue appears in a Project and moved through sensible statuses | 5 |
| Conceptual explanations | Accurate explanations of branch, commit/push, origin, Issue, and PR | 10 |
| Debugging / recovery reasoning | Diagnoses state first and proposes safe recovery for all scenarios | 10 |
| Reflection | Specific and connected to team-development risk reduction | 5 |
| **Total** |  | **40** |

## Entering the Teacher Grade

Every student Pull Request automatically receives a **Teacher grading** block from the bot. Use the fixed template shown there:

```text
/manual-grade
Workflow: 0/10
Project evidence: 0/5
Concepts: 0/10
Debugging: 0/10
Reflection: 0/5

Feedback:
Write concise feedback here.
```

Copy the block into a **new PR comment**, replace the scores, and add feedback. The workflow calculates the 40-point teacher subtotal automatically and combines it with the automatic 60 points.

Example:

```text
/manual-grade
Workflow: 10/10
Project evidence: 5/5
Concepts: 9/10
Debugging: 9/10
Reflection: 5/5

Feedback:
Strong integrated workflow. Your recovery strategy is safe and state-first; make the distinction between commit and push slightly more explicit.
```

The newest valid grading comment by `hbycwyh2008` is used. To revise a grade, post a new completed template.

The older short form remains accepted for compatibility:

```text
/manual-grade 38
```

## Recommended teacher check

CP5 is the mastery checkpoint. Verify that the student can connect the entire workflow without following a step-by-step recipe: Issue/Project planning, feature-branch work, meaningful commit(s), push, PR, closing reference, and safe debugging reasoning. The debugging responses should begin by inspecting repository state before proposing corrective commands.
