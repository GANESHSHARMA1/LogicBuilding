# 🌿 Branching and Merging

### Create a New Branch### Create a New Branch

```bash
git branch feature-1
```

---

### Switch to Branch

```bash
git checkout feature-1
```

---

> (Shortcut to create + switch directly:)

```bash
git checkout -b feature-1
```

---

### Make Changes in This Branch

```bash
echo "New feature started" > feature.txt

git add feature.txt

git commit -m "Added feature.txt in feature-1 branch"
```

---

### Switch Back to Main Branch

```bash
git checkout main
```

---

### Merge Feature Branch into Main

```bash
git merge feature-1
```

### Delete the Branch (Optional)

```bash
git branch -d feature-1
```

---

✅ Done! Branching helps keep separate lines of development.
Continue to [Using GitHub Remotes →](./03-remote.md)
