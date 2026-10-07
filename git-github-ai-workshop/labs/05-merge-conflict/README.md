# Lab 05 — Merge Conflict

The instructor can demonstrate a conflict by having two branches modify the same lines.

Conflict markers:

```text
<<<<<<< HEAD
your version
=======
other version
>>>>>>> branch
```

Choose the correct content, remove the markers, test, then:

```bash
git add .
git commit -m "Resolve merge conflict"
```

A conflict is not a failure. It is a decision Git cannot safely make for you.
