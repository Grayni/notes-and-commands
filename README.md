# notes-and-commands  
commands: linux, npm, git, etc.  

***
##### commands linux:

1. add free right on redact and change npm:  
    __sudo chown -R $(whoami) ~/.npm__  
  
##### commands Git:  
  
1. cancel git add:  
    __git commit reset__  
  
2. change on capital letter name of file for correct saving:  
    __git mv filename.txt FileName.txt –f__

3. look current remote repository
    __git remote -v__

4. pass local repository in remote repository
    __git init__
    __git add your_file__
    __git commit -m "first commit"__
    __git remote add origin https://github.com/you_repository/you_project__
    __git push -u origin master__ (or your branch instead master)

