# 🔧 Advanced Git Commands

> These commands are not for daily use but are very powerful tools once you are comfortable.

---

### View Commit Graph

```bash
git log --oneline --graph --all
```

---

### Rebase Commits (Interactive)

```bash
git rebase -i HEAD~3
```

- Allows you to **squash**, **reorder**, or **rename commits**.

---

### Cherry-pick a Commit (Apply Specific Commit)

```bash
git cherry-pick <commit-id>
```

---

### Amend the Last Commit Message

```bash
git commit --amend -m "New commit message"
```

---

### Tagging a Commit

- Create a tag:

```bash
git tag v1.0
```

- Push tags to remote:

```bash
git push origin --tags
```

---

### Remove Untracked Files

```bash
git clean -f
```

---

---

✅ These advanced commands give you more control over history and collaboration.  
Congrats! 🎉 You’ve completed the Git Learning Path.

👉 For a quick overview, check the [Git Cheatsheet](./cheatsheet.md)
