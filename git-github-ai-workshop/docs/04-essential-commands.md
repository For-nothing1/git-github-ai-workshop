# Essential Git Commands

```bash
git --version
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

git init
git clone <url>

git status
git diff

git add .
git add filename

git commit -m "message"
git log --oneline

git branch
git switch main
git switch -c feature/name

git remote -v
git remote add origin <url>

git push
git push -u origin feature/name
git pull

git restore --staged filename
git restore filename
```

### Memory

```text
status = what changed?
add = select changes
commit = save checkpoint
push = send to GitHub
pull = get remote changes
branch = separate work
```
