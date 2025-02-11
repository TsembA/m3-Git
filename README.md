### What is Version Control?

* Also known as "source control"
* There's couple diffirent git repositories like GitHub, GitLab, Bitbucket
* Companies can have their own Git repositories hosted on company servers
* Practice of tracking and managing changes to software code
* It enables multiple people to simultaneously work on a single project
* Code is hosted centrally on the internet
* Every developer has an entire copy of the code locally


### Basic Concepts of Version Control

* Version Control keeps a history of changes
* Every code change and file is tracked
* You can revert commits
* Each change labelled with commit message

### Git is the most used vesion control system 

Commands

    git clone (create local copy of remote repo)
    git add
    
    git commit
    git log
    
    git push
    gut pull
    git pull -r
    git init
    git remote add origin <remote_repo_url>
    git push - -set-upstream origin master (create local git repo and connect to remote repo)
    git checkout
    git checkout -b (create new branch locally)
    git branch
    git status
    git branch -d
    git rebase(avoid unnecessary merge commits in git history)
    git rebase --continue
    git rm -r --cached
    git rm --cached (remove file from remote repo)
    git stash
    git stash pop (bring changes back ty my local working derictory)
    git reset --hard HEAD~1(revert & discard changes to commit, ~)
    git reset <commit hash> removers old commit
    git reset HEAD~1(revert commit & keep changes)
    git commit --amend(merge changes into last commit)
    git reset --hard HEAD~1
    git push --force
    git revert <commit_hash>(creates new commit to revert old commit changes)
    git merge
    


### Best Practices
* Don’t "git push" straight to main or master branch
* Create a separate branch for each feature or bugfix and name the branch with prefix “feature/xx” and “bugfix/xxx” respectively
* Use .gitignore file to ignore e.g. editor specific files, build folders. Like you keys, node_modules etc..
* Doing Code Reviews via Merge Requests
* Use descriptive and meaningful commit messages
* Commit in relatively small chunks
* Commit only related work
* Avoid very large deviations between local and remote repository 
* Keep your feature/bugfix branch up-to-date with remote master and/or develop branch. So pull often from remote git repository
* Branches shouldn’t be open for too long or master branch should be merged into your feature/bugfix branch often
