# Lab 03 — Branching

Create:

```bash
git switch -c feature/my-feature
```

Edit `feature.txt`.

Then:

```bash
git add .
git commit -m "Add my feature"
git push -u origin feature/my-feature
```

Switch back:

```bash
git switch main
```

Observe that the branch keeps your feature work separate.
