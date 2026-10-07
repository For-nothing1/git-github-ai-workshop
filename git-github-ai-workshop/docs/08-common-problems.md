# Common Beginner Problems

### Git command not found

```bash
git --version
```

Install Git if necessary.

### Wrong branch

```bash
git branch
git switch main
```

### Changes not visible

```bash
git status
git diff
```

### Push rejected

Understand the reason first. Often the remote contains changes you do not have locally.

```bash
git pull
```

Resolve conflicts if necessary, then commit and push.

### Merge conflict

Look for:

```text
<<<<<<<
=======
>>>>>>>
```

Choose the correct final content, remove the markers, test, then:

```bash
git add .
git commit -m "Resolve merge conflict"
```

A merge conflict is Git asking a human to make a decision.
