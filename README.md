## Git Branching

Git cheat sheet and branching practice

example add to main 

### Basic Commands

* 'git init' - initialize local git repo
* 'git add filname' - stage 'filename' for commit
* 'git commit -m "msg"' - commit to local repo with message 'msg'
* 'git branch -m newName' - change name of current branch

### Information Commands
* 'git status' - show commit status of local repo
* 'git log' - show commit log
* 'git log --oneline' - show commit log (compact format)
* 'git config -l' - list repo configuration

### Branching Commands

* 'git branch' - list local branches
* 'git branch branchName' - create local branch 'branchName'
* 'git checkout branchName' - switch to branch 'branchName'

### Remote Commands

* 'git remote add origin repoUrl' - create alias 'origin' for remote repo 'repoUrl'
* 'git push origin branchName' - push to remote branch 'branchName'  
* 'git push -u origin branchName' push to remote branch 'branchName', making it the defailt remote 