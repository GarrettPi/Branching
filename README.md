## Git branching practice and cheat sheet


Summary and cheat sheer of git commands, and practice branching.


### Basic commands
* `git init` - initializes a local git repo in current folder
* `git add .` - stage current changes for commit
* `git commit -m "Message"` - commit staged changes to local repo


### Information commands
* `git status` - show status of working folder and repo
* `git log` - show log of commits
* `git log --oneline` - show log of commits, one line each
* `git config -l` - list git configuration

### Branching commands
* `git branch` - list local branches, show which branch we are on
* `git branch -M` - renames current branch to a new name
* `git branch branchName` - creates a new branch 'branchName'
* `git checkout branchName`- go to branch 'branchName'

### Remote commands
* `git remote add origin someUrl` - links local repo with remote repo at 'someUrl'
* `git push origin main` - push local commits to remote branch main
* `git push origin branchName` - push to remote branch 'branchName'
