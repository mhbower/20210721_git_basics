# git basics

- 'git init': initialize git repository in current working directory
- 'git status: gives you the status
- 'git add <FILE>': add <FILE> to staging area
- ' git commit': creates a commit, you provide message

- 'git log': shows you the log of the your commits
-'git log --oneline': shows you one line version of log

-'HEAD': where you currently are (version of file you're working with)
-'git diff HEAD~<NUM> <FILE>: compares current file to file <NUM> ago
  -'git dif <HASH> <FILE>: compares curren file to <HASH> version

-use 'git status' to find commands to unstage or restore file
-'git checkout <HASH> <FILE>': restore <FILE> to version in <HASH>
   -if you run 'git checkout <HASH>' without the <FILE>, then you have moved your head.  You can fix this by running 'git checkout main'

- git ignores empty folders
-'use .gitkeep to show a folder that is initially empty and you want to keep it for future use'
-
