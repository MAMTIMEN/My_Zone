## install
`sudo apt-get install git-all`

## config settings and config files
`git config --list --show-origin`

## user info
`git config --global user.name <user-name>`  
`git config --global user.email <e-mail>`

## text editor
`git config --global core.editor emacs`

## all configs
`git config --list`

## get help
`git help <verb>`  
`git <verb> help`  
`man git-<verb>`  
etc: git help config

## initialize project
`git init`

## tracke changes
`git add <[file name] | [* (to all)]>`

## commit the change
`git commit -m "<discribe this change>"`

## clone project
`git clone <url> [.]|[<new folder name>]`

## corrent status
`git status [<-s> | <--short>]`

## ignore
`create .gitignore file`  
[more git ignore tips](https://github.com/github/gitignore)

## difference
`git diff <--staged>`

## commit
`git commit -a -m "<discribe chnages>"`

## delete
remove file from dir:  
`git rm -f <file name>`  
remove file from cache:  
`git rm --cached <file name>`

## rename
`git mv <old name> <new name>`  
equal to  
`mv <old name> <new name>`  
`git rm <old name>`  
`git add <new name>`

## log
`git log -p <last step>`  
`git log --stat`  
`git log --pretty=format:"<format>"`  
[more git log](https://git-scm.com/book/zh/v2/Git-%E5%9F%BA%E7%A1%80-%E6%9F%A5%E7%9C%8B%E6%8F%90%E4%BA%A4%E5%8E%86%E5%8F%B2)

## revoke
cover last commit   
`git commit --amend`  
revoke last add  
`git reset HEAD <fime name>`

## discard
`git checkout -- <file name>`

## clone
`git clone <url>`

## pull
`git pull`

## push
`git push <remote> <branch>`

## show
`git remote show <origin>`

## remote remove
`git remote [remove|rm] <branch>`

## tag
`git tag -l`  
`git tag -a <version> -m "discribetion"`

## alias
`git config --global alias.co checkout`

## branch
`git branch <new branch name>`  
`git checkout [-b] <branch name>`  
equal to:  
`git branch <branch name>`  
`git checkout <branch name>`   

delet branch:  
`git branch -d <branch name>`

merge branchs:  
`git merge <branch name>` 