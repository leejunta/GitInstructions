Git Instructions to Add to Repository
=====================================

1) Change directory where files are  
2) Configure user making changes  
     `git config --global user.name "Firstname Lastname"`  
     `git config --global user.email emailaddress`  
3) Initialize Git repository  
     `git init`  
4) Connect local directory to repo at Github  
     `git remote add myorigin https://github.com/username/reponame  
5) Check the status of local repository
     `git status`
6) Add file to repository  
     `git add filename`  
     * Use '.' instead to add all files  
7) Commit to the master branch  
     `git commit -am "Comment"`  
     * `-a` commits all the files  
     * `-m` adds a comment  
8) Push the Git repo into Github
     `git push myorigin master`


