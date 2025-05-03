# 🚀 Git & Version Control

## 📦 What is Version Control?

* Also known as **source control** 🧭  
* Practice of **tracking and managing changes** to software code 🛠️  
* Enables **multiple people** to collaborate on the same project 🤝  
* Code is **centrally hosted** (e.g., GitHub, GitLab, Bitbucket) 🌐  
* Companies can host **private Git repositories** on internal servers 🏢  
* Every developer has a **local copy** of the full codebase 💻

---

## 🧱 Basic Concepts of Version Control

* Keeps a **history of all changes** 📜  
* Tracks **every file and code update** 🔍  
* Allows you to **revert to previous states** 🔄  
* Each change is labeled with a **commit message** 📝  

---

## 🥇 Git — The Most Popular Version Control System

### 🔧 Common Git Commands

```bash
git clone <repo_url>             # 📥 Copy a remote repo locally
git init                         # 🆕 Initialize a Git repo
git add <file>                   # ➕ Stage changes
git commit -m "msg"              # 💾 Save staged changes
git log                          # 📚 View commit history
git status                       # 📊 See current file status

git push                         # 🚀 Upload changes to remote repo
git pull                         # 🔄 Download and merge from remote
git pull -r                      # 🔁 Pull with rebase

git remote add origin <url>      # 🌍 Connect to a remote repo
git push --set-upstream origin master  # 🔗 Link local master to remote

git checkout <branch>            # 🔀 Switch branches
git checkout -b <branch>         # 🌱 Create and switch to a new branch
git branch                       # 🌿 List branches
git branch -d <branch>           # ❌ Delete a branch

git merge <branch>               # 🧬 Merge changes
git rebase <branch>              # 🧹 Rebase to keep history clean
git rebase --continue            # ⏭️ Continue after conflict resolution

git rm --cached <file>           # 🧽 Untrack a file but keep locally
git rm -r --cached <dir>         # 🧽 Untrack a directory

git stash                        # 📦 Save changes temporarily
git stash pop                    # 🎁 Reapply saved changes

git reset --hard HEAD~1          # 🗑️ Discard last commit
git reset <commit_hash>          # 🔁 Reset to specific commit
git reset HEAD~1                 # ⏪ Undo commit but keep changes

git commit --amend               # ✏️ Edit last commit
git push --force                 # 💣 Force push (use with caution!)
git revert <commit_hash>         # 🚫 Revert changes (safely)




🌟 Best Practices for Using Git

✅ Don’t push directly to main or master
✅ Create feature/bugfix branches using naming like feature/xyz or bugfix/xyz
✅ Use .gitignore to exclude editor files, credentials, and large folders like node_modules
✅ Do code reviews through Merge Requests (MRs)
✅ Write clear, descriptive commit messages 📝
✅ Make small, focused commits 📌
✅ Group related changes in the same commit 🧩
✅ Pull often to stay synced with remote 🔄
✅ Merge often from main/develop to avoid conflicts 🧠
✅ Don’t leave branches open too long ⏳
