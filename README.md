# Checkpoint 2 — Feature Branch & Pull Request Workflow

## Goal

Show that you can complete the core Git development workflow safely without working directly on `main`.

This checkpoint tests **execution**:

```text
clone
→ create feature branch
→ edit
→ git status
→ git add
→ git commit
→ git push
→ open Pull Request
```

CP4 later tests the **mental model** behind local/remote repositories, `origin`, `clone`, `push`, and `pull`. CP2 is about actually performing the workflow correctly.

## Start the exercise

Copy this checkpoint into your own GitHub account:

[![Copy Exercise](https://img.shields.io/badge/Copy%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=KLIS-CS&template_name=GitHub-Feature-Branch-Pull-Request-Workflow&owner=%40me&name=cp2-feature-branch-pr-workflow&description=Checkpoint+2:+Feature+Branch+%26+Pull+Request+Workflow&visibility=private)

After the copy is created:

1. Open **Actions**.
2. Select **Start Exercise**.
3. Choose **Run workflow**.
4. Read the Exercise Issue that GitHub Actions creates for you.
5. Clone your copied repository to your computer.
6. Complete the checkpoint **locally**.

> The source repository must be enabled as a GitHub **Template repository** for the Copy Exercise button to work.

## Required Branch

Create this branch locally after cloning:

```text
cp2-YOUR-GITHUB-USERNAME
```

Do **not** work directly on `main`.

## Challenge

On your required CP2 branch:

1. Open `feature.txt`.
2. Replace the starter line with a short description of a feature you are adding.
3. Complete `submission.md`.
4. Use `git status` before and after staging so you can observe repository state.
5. Stage your work with `git add`.
6. Commit with a meaningful commit message.
7. Push the required branch to GitHub.
8. Open a Pull Request from your CP2 branch into `main`.
9. Leave the Pull Request **open** for grading.

Your Pull Request should change only:

```text
feature.txt
submission.md
```

The grader checks that `main` still contains the untouched starter file. If you edit `main` directly, the checkpoint will not receive full automatic credit.

## What the automatic grader checks — 60 points

| Evidence | Points |
|---|---:|
| Correct `cp2-USERNAME` branch exists | 10 |
| `main` still has the untouched starter file | 10 |
| `feature.txt` was changed on the CP2 branch | 10 |
| CP2 branch has at least one commit ahead of `main` | 10 |
| Open Pull Request from CP2 branch → `main`, with only allowed files changed | 15 |
| `submission.md` is complete | 5 |
| **Automatic total** | **60** |

## Teacher review — 40 points

The grader automatically places a fixed teacher rubric in the Pull Request. The teacher copies it into a new PR comment, fills in the scores, and adds feedback.

Teacher categories:

- Branch safety — 10
- Git workflow explanation — 10
- Pull Request understanding — 10
- Reflection & work quality — 10

**Final score = Automatic /60 + Teacher /40 = /100.**

## Checkpoint Navigation

| Checkpoint | Skill | Link |
|---|---|---|
| CP1 | Repository Setup | [Open](https://github.com/KLIS-CS/GitHub-Repository-Setup) |
| **CP2 — You are here** | Feature Branch & Pull Request | [Open](https://github.com/KLIS-CS/GitHub-Feature-Branch-Pull-Request-Workflow) |
| CP3 | Issues & Projects | [Open](https://github.com/KLIS-CS/GitHub-Issues-Projects-Workflow) |
| CP4 | Local ↔ Remote | [Open](https://github.com/KLIS-CS/KLIS-CS-Git-Local-Remote-Workflow) |
| CP5 | Final Integrated Challenge | [Open](https://github.com/KLIS-CS/GitHub-Final-Integrated-Challenge) |

[Back to GitHub Foundations Hub](https://github.com/KLIS-CS/GitHub-Foundations)
