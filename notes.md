### What is Version Control?

* Also known as "source control"
* Practice of tracking and managing changes to software code
* It enables multiple people to simultaneously work on a single project
* Code is hosted centrally on the internet
* Every developer has an entire copy of the code locally


### Basic Concepts of Version Control

* Version Control keeps a history of changes
* Every code change and file is tracked!
* You can revert commits
* Each change labelled with commit message

### Git is the most used vesion control system 

Commands

    git clone (create local copy of remote repo)
    git add
    
    git commit
    git log
    git push
    git pull
    git init
    git remote add origin <remote_repo_url>
    git push - -set-upstream origin master (create local git repo and connect to remote repo)
    git checkout
    git checkout -b (create new branch locally)
    git branch
    git status
    git branch -d
    git rebase(avoid unnecessary merge commits in git history)
    git rm -r - -cached
    git rm - -cached (remove file from remote repo)
    git stash
    git stash pop(save unfinished changes)
    git reset - -hard HEAD~1(revert & discard changes to commit, ~)
    git reset HEAD~1(revert & keep changes)
    git commit - -amend(merge changes into last commit)
    git reset - -hard HEAD~1
    git push - -force
    git revert <commit_hash>(creates new commit to revert old commit changes)
    git merge

Remove Git

remove local .git file (contains config for git remotes etc) rm -fr .git
best practices
1 branch per feature dev branch: intermediary master branch pull/merge requests delete branch when merged add .gitignore file