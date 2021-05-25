# 25-05-2021

- 'git init' : this intiiatilizes the git repositorty
- 'git status' : give the status
- 'git add <FILE>' : adds <FILE> to the staging area
- 'git commit':  commits files from stating
  - 'git commit -m "MESSAGE"': commit without opening editor
- 'git log' : gives the log of the git repositorty
  - 'git log --oneline': gives the log and changes in one line - condensed history
- 'git diff' : gives you the difference
  - 'git diff HEAD~3': this gives a difference between current and 3 commits ago
  - 'git diff <SHA> <FILE>': diff a file against a specifc commit
  - 'git diff id#' : this gives a difference between current the version with the id number
- 'git checkout <SHA> <FILE>' : revert <FILE> from <SHA> to current
- 'git checkout <SHA>': moves you to <SHA>
    - 'git diff --staged' : gives difference in staging area
- '.gitignore': file that pattern matches files to gitignore
- '.gitkeep' : convetion to keep a empty folder
