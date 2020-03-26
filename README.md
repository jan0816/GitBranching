## Git Branching

###Overview
Overview and cheat sheet of Git commands. Introduction to branching.


### Basic Commands

* 'git init' - Initialize local git repository
* 'git add' - Stage local working directory for commit
* 'git commit' - Commit staged files to local repo
* 'git status' - Show status of repository
* 'git rm --cached fileName' -Remove fileName from commit index
* 'git log' show commit history
* 'git log --oneline' - Show commit history (compact)


### Branching Commands
* 'git branch' - List local branches, highlight checked-out branches
* 'git branch branchName' - Create branch 'branchName'
* 'git checkout branchName' - Move to branch 'branchName'
<<<<<<< HEAD
* ' git push origin branchName' Push local branch 'branchName' to origin
=======
>>>>>>> 701abcc23a42d3f8b41e25f4c7ca99f50bab1def


### Remote repository commands

* 'git remote add origin remoteRepoUrl' - Link local repo to remoteRepoUrl
* 'git pull origin master' - Pull 'master' branch content from remote origin into current local branches
* 'git push origin master' - Push current local branch to 'master' branch of remote origin
