# ⏪ Undo & Reset in Git

> **Tip:** These commands help you undo mistakes safely. Practice them in a test repo!

---

### Undo Last Commit (Keep Changes in Staging)

```bash
git reset --soft HEAD~1
```

---

### Undo Last Commit (Keep Changes in Working Directory)

```bash
git reset --mixed HEAD~1
```

---

### Undo Last Commit (Discard Changes Permanently ⚠)

```bash
git reset --hard HEAD~1
```

---

### Discard Local File Changes

```bash
git checkout -- <file>
```

---

### Remove File from Staging Area

```bash
git reset <file>
```

---

### Temporary Save (Stash)

```bash
git stash
```

---

### Bring back stashed changes:

```bash
git stash pop
```

---

### List all stashes:

```bash
git stash list
```

---

---

✅ Undoing changes is powerful. Be careful with `--hard`!  
Next: [Advanced Git Commands →](./05-advanced.md)
