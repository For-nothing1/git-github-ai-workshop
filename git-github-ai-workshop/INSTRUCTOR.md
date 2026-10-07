# Instructor Guide — 90 Minutes

## 0–10 min: Git and GitHub concepts
Use `docs/01`, `docs/02`, `docs/03`.

Explain with the model:

```text
Working → Staging → Commit → GitHub
```

## 10–20 min: Setup + first commands
Run Lab 00.

Demonstrate:

```bash
git --version
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git status
```

## 20–35 min: First hands-on
Lab 01.

Students type:

```bash
git status
git diff
git add .
git diff --staged
git commit -m "Add participant profile"
git log --oneline
```

## 35–45 min: Clone / branch / push
Labs 02 and 03.

## 45–55 min: Pull Requests + Issues
Labs 04 and 06.

## 55–62 min: Merge conflict
Lab 05. Instructor-led if time is short.

## 62–75 min: AI coding
Lab 07.

Demonstrate explanation → bug finding → fix → test generation.

## 75–85 min: AI review
Lab 08.

If the current GitHub/Copilot features are available, demonstrate AI-assisted review and fixing.

## 85–90 min: Final challenge
Introduce Lab 09 as the final challenge/takeaway.

### Teaching principle

Do not make students memorize commands.

For every command explain:

**What problem does this solve?**

Then let students type it.

### Complete story

```text
Issue
 ↓
Branch
 ↓
Code
 ↓
Commit
 ↓
Push
 ↓
Pull Request
 ↓
AI Review
 ↓
Human Review
 ↓
Merge
```
