# Git Mental Model

Do not memorize commands first. Understand where your changes are.

```text
Working Directory
      |
   git add
      v
Staging Area
      |
  git commit
      v
Local Repository
      |
   git push
      v
GitHub / Remote
```

### Working Directory
The files you are currently editing.

### Staging Area
The changes selected for the next commit.

```bash
git add file.py
```

### Local Repository
Your saved Git history.

```bash
git commit -m "Add feature"
```

### Remote Repository
A copy hosted somewhere else, commonly GitHub.

```bash
git push
```

When confused:

```bash
git status
git diff
git diff --staged
git log --oneline
```

Ask:
1. What changed?
2. What am I about to save?
3. What have I already saved?
