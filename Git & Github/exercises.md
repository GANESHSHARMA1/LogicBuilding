# 🏋️ Git Practice Exercises

This file contains **hands-on Git exercises** arranged by levels.  
Follow them **step by step** to master Git in real-world scenarios.

---

## 🟢 Level 1: Beginner (Basics)

1. Install Git and configure user details:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

---

2. Initialize a new repository called `my-first-repo`.
3. Create a file `about.txt` and write something in it.
4. Stage the file and commit with the message `"First commit: added about.txt"`.
5. Modify `about.txt` and commit the change.
6. View commit history in a one-line format.
7. Create another file `info.txt`, add it to `.gitignore`, and verify that Git is ignoring it.

---

## 🌿 Level 2: Intermediate (Branching & Remotes)

1. Create a new branch `dev` and switch to it.
2. Add a file `feature.txt`, commit it on `dev` branch.
3. Switch back to `main` and merge `dev` into it.
4. Delete the `dev` branch after merge.
5. Create another branch `bugfix` and commit a debug log.
6. Push your repo to GitHub (`origin`) on `main`.
7. Push the `bugfix` branch to GitHub.
8. Clone the same repository in a new folder and verify both branches exist.

---

## ⏪ Level 3: Undo & Fix Mistakes

1. Commit a wrong message `"mistkae msg"` → then amend the commit to `"correct commit message"`.

   ```bash
   git commit --amend -m "correct commit message"
   ```

2. Commit a temporary file `temp.log` → then unstage it.
3. Create 3 commits (`a.txt`, `b.txt`, `c.txt`) → reset back to `a.txt` commit using `--soft`.
4. Stash uncommitted changes → then apply them back with `git stash pop`.
5. Commit a file `wrong.txt` → then delete it from history using `git rm` + commit.
6. Practice `git checkout -- <file>` to restore a file.

---

## 🔧 Level 4: Advanced Git

1. Make 5 commits and try `git rebase -i HEAD~5` to squash 3 commits into one.
2. Create a new branch `experiment`, make changes, then rebase it onto `main`.
3. Use `git cherry-pick` to copy a specific commit into another branch.
4. Create a tag `v1.0` and push it to GitHub.
5. Run `git log --oneline --graph --all` to visualize branches.
6. Create a `hotfix` branch → commit changes → then merge it into both `main` and `dev`.
7. Delete local and remote branches (`git branch -d` and `git push origin --delete`).
8. Use `git clean -f` to clean untracked files.

---

## 🏆 Level 5: Real-World Team Scenarios

1. **Fork & PR Workflow**

- Fork a public repo on GitHub.
- Clone your fork locally.
- Create a new branch and implement a small change.
- Push your branch and create a Pull Request.

2. **Rebase Workflow Simulation**

- Create 2 branches (`main` and `feature`).
- In `main`, add a commit.
- In `feature`, make 2 commits.
- Rebase `feature` onto `main`.

3. **Resolve a Merge Conflict**

- On branch `main`, write `Hello from main` in `conflict.txt`.
- On branch `dev`, write `Hello from dev` in the same file.
- Merge `dev` into `main` → resolve conflict and commit.

4. **Collaboration Simulation**

- Partner 1 pushes to `main`.
- Partner 2 also edits the same file and pushes.
- Partner 1 pulls changes, resolves conflicts, commits, and pushes again.

5. **Rollback a Mistake**

- Delete an important file and commit the deletion.
- Use `git checkout HEAD~1 <file>` to recover the deleted file.

6. **Bisect for Bug Hunting**

- Simulate a bug in between multiple commits.
- Use `git bisect start` → mark good/bad commits → find buggy commit.

---

## 🎯 Learning Path Recap

✔️ Level 1: Repo setup, add/commit basics  
✔️ Level 2: Branching & remotes  
✔️ Level 3: Undo/reset/stash mistakes  
✔️ Level 4: Advanced workflows (rebase, cherry-pick, tags)  
✔️ Level 5: Real-world scenarios (PRs, conflicts, collaboration, bisect)

---

## 📌 Pro Tips

- Never use `git reset --hard` on shared branches like `main` (use carefully).
- Use branches for **every new feature/fix**.
- Commit often with meaningful messages.
- Always pull (`git pull`) before pushing to reduce conflicts.

---

🎉 Congratulations! If you finish these exercises, you’ll have mastered **most real-world Git & GitHub workflows**.
