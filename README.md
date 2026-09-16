# Checkpoint 5 — Final Integrated GitHub Challenge

## Goal

Prove that you can start a project **from scratch** and then carry it through a complete Git/GitHub development workflow independently.

CP5 combines both major abilities from the unit:

```text
CREATE a repository
+
MODIFY it safely through Git
+
MANAGE the work in GitHub
+
DEBUG mistakes
```

## Start CP5 — do NOT copy this repository

This KLIS-CS repository is the **instruction and grading portal only**. Your assessed CP5 project must be created by you with **GitHub → New repository**.

Create a new **Public** repository in your own GitHub account named exactly:

```text
cp5-final-integrated-YOUR-GITHUB-USERNAME
```

Do not fork another repository and do not use **Use this template**.

When creating the repository, configure it yourself with:

- `README.md`
- an appropriate `.gitignore`
- a real open-source `LICENSE`

## Scenario

Your team needs a JavaScript feature that displays a welcome message. You are responsible for creating the project, tracking the work, implementing the feature, and submitting it for review.

## Required workflow

### 1. Create the repository

Create the public repository yourself and make the initial repository-setup decisions.

### 2. Clone it locally

Clone your new repository to your computer and inspect it before changing anything:

```bash
git status
git branch
git remote -v
```

### 3. Create and track the work

Create a GitHub Issue whose title begins with:

```text
[CP5]
```

The Issue must:

- clearly describe the feature;
- include at least two acceptance-criteria checkboxes;
- have at least one label;
- be assigned to you.

Add the Issue to a GitHub Project and move it through appropriate statuses such as **Todo → In Progress → Done**.

### 4. Modify the project through a feature branch

Create this branch locally:

```text
cp5-YOUR-GITHUB-USERNAME
```

Do **not** implement the feature directly on `main`.

On the feature branch:

- create `src/index.js`;
- add working JavaScript that produces or displays a welcome message;
- make at least one meaningful improvement to `README.md`;
- use `git status` before staging;
- `git add` the intended changes;
- commit with a meaningful message;
- push the feature branch to `origin`.

### 5. Open a Pull Request

Open a Pull Request from your CP5 branch into `main`.

The PR body must connect the code to your CP5 Issue with a closing keyword, for example:

```text
Closes #12
```

Leave the Pull Request open for teacher review.

### 6. Debugging / recovery

The submission form includes recovery scenarios covering:

- accidentally working on `main`;
- a file missing from a commit;
- a branch with no upstream;
- an incorrect remote URL.

Explain what you would inspect first and how you would recover.

## Submit CP5

When the project is complete, submit the repository through the central CP5 form:

[![Submit CP5](https://img.shields.io/badge/SUBMIT%20CP5-%E2%86%92-0969da?style=for-the-badge&logo=github)](https://github.com/KLIS-CS/GitHub-Final-Integrated-Challenge/issues/new?template=cp5-submission.yml)

The automatic grader inspects your public repository, feature branch, Issue, and Pull Request. GitHub Project quality and debugging explanations remain teacher-reviewed.

## Automatic evidence — 60 points

| Evidence | Points |
|---|---:|
| Correct public student-owned repository created from scratch | 10 |
| README / `.gitignore` / LICENSE / `src/index.js` | 10 |
| Correct feature branch + commit ahead of `main` | 10 |
| `[CP5]` Issue with checklist, label, and assignee | 10 |
| Open PR to `main` with closing Issue reference | 10 |
| Complete conceptual / Project / debugging submission | 10 |
| **Automatic subtotal** | **60** |

## Teacher review — 40 points

Teacher review focuses on:

- workflow independence;
- GitHub Project evidence;
- conceptual understanding;
- debugging / recovery reasoning;
- reflection and work quality.

**Final score = Automatic /60 + Teacher /40 = /100.**

## Checkpoint Navigation

| Checkpoint | Skill | Link |
|---|---|---|
| CP1 | Repository Setup | [Open](https://github.com/KLIS-CS/GitHub-Repository-Setup) |
| CP2 | Feature Branch & Pull Request | [Open](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow) |
| CP3 | Issues & Projects | [Open](https://github.com/KLIS-CS/GitHub-Issues-Projects-Workflow) |
| CP4 | Local ↔ Remote | [Open](https://github.com/KLIS-CS/KLIS-CS-Git-Local-Remote-Workflow) |
| **CP5 — You are here** | Final Integrated Challenge | [Open](https://github.com/KLIS-CS/GitHub-Final-Integrated-Challenge) |

[Back to GitHub Foundations Hub](https://github.com/KLIS-CS/GitHub-Foundations)
