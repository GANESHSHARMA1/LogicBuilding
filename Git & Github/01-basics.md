# 🟢 Git Basics

> **Tip:** Copy and paste the commands into your terminal to run them.

---

### Check Git Version

```bash
git --version
```

- If Git is not installed, download from: `https://git-scm.com/downloads`

---

### Setup Username & Email

```bash
git config --global user.name "Your Name"

git config --global user.email "you@example.com"
```

---

### Create a New Git Repository

```bash
mkdir git-learning

cd git-learning

git init
```

---

### Check Files in Folder

```bash
ls
```

- And to see hidden files (you should notice the `.git` folder):

```bash
ls -a
```

---

### Create a File and Add Content

```bash
echo "Hello Git" > hello.txt
```

---

### Add File to Git Staging

```bash
git add hello.txt
```

---

### Commit the File

```bash
git commit -m "First commit: added hello.txt"
```

---

### View Commit History

```bash
git log --oneline
```

---

---

✅ Congrats! You just created your first Git repo and commit.
Continue to [Branching and Merging →](./02-branching.md)
