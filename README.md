Repository Setup
git init
git clone <repo-url>
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list
Basic Workflow
git status
git add <file>
git add .
git commit -m "commit message"
git commit -am "commit message"
git log
git log --oneline
Branching
git branch
git branch <branch-name>
git checkout <branch-name>
git checkout -b <branch-name>
git branch -d <branch-name>
git branch -a
git merge <branch-name>
Remote Repositories
git remote
git remote -v
git remote add origin <repo-url>
git remote remove origin
git fetch
git pull origin main
git push origin main
git push -u origin main
Undo Changes
git restore <file>
git restore --staged <file>
git reset HEAD <file>
git reset --soft HEAD~1
git reset --hard HEAD~1
git revert <commit-id>
Stashing
git stash
git stash list
git stash apply
git stash pop
git stash drop
Inspecting Changes
git diff
git diff --staged
git show <commit-id>
git blame <file>
Tagging
git tag
git tag <tag-name>
git tag -d <tag-name>
git push origin <tag-name>
Cleaning
git clean -n
git clean -f
Advanced
git rebase <branch>
git rebase -i HEAD~3
git cherry-pick <commit-id>
git bisect start
git bisect bad
git bisect good
git archive
Example Basic Git Workflow
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/username/repo.git
git push -u origin main# git work
