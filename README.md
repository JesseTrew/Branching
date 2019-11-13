## Git Branching Practice

### Basic 'git' commands

* 'git init' create new local repo
* 'git add .' - add current working directory to git index
* 'git status' - display status of local repo
* 'git commit -m "message"' -commit changes to local repo

### Basic Branching
* 'git branch branchName' - Create local branch named 'branchName'
* 'git checkout branchName' - Move to branch 'branchName'
* 'git branch' - Display local branches and which we are on
* 'git checkout -b newBranch' - Create and check out branch 'newBranch'

### Merging
* Add and commit local branch.
* Push local branch to remote.
* Pull 'master' from remote into local branches
```bash
git checkout newBranch
git pull origin master
```
* Resolve merge conflicts
* Commit and push local branches
```bash
git add .
git commit 0m 'Merging master with newBranch'
git push origin newBranch
```
* On Github, create Pull Request
* Teammates merge Pull Request
* Teammates merge Pull Request into master.
