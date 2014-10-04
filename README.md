# Haskell Basics
This is suposed to be a collection of examples on how to do stuffs in haskell
To help me learn both haskell and git

## Git Commands

### Creating a repository online for the <b> first time<b> 

``` sh
$ touch README.md
$ git init 
$ git add README.md
$ git commit -m "first commit" 
$ git remote add origin https://...
$ git push -u origin master
 put in username & password 

```

###When adding changes to the online repo
``` sh
$ git add . #To add all changes made to files
$ git add -u #To add deletion of files or something like that
$ git commit -m "the new changes" 
$ git push 
 put in username & password

```

###To avoid using username & password every commit

``` sh
$ git remote set-url origin git@github.com:YourUserName/YourReponame.git
```

###To cache username & pasword
``` sh
$ git config --globalcredential.helper wincred
```
