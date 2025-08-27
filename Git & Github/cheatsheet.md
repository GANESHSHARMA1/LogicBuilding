# ⚡ Git Cheatsheet

### Setup

```bash
git config --global user.name "name"

git config --global user.email "email"
```

---

### Start Repo

```bash
git init
```

---

### Stage + Commit

```bash
git add <file>

git commit -m "message"
```

---

### Branching

```bash
git checkout -b new-branch

git branch

git merge new-branch
```

---

### Undo

```bash
git reset --soft HEAD~1

git reset --hard HEAD

git stash

git stash pop
```

---

### Remotes

```bash
git remote -v

git push origin main

git pull origin main
```
