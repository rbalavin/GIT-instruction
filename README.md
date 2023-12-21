##Install GIT##
```brew install git```
##Add directory to GIT##
_Go to directory_
```cd 'directory path'```
```git init```
Сheck status
```git status```
##Adding changes##
```git add 'name files'
git add --all
git add .```
Сheck status
```git status```
##Save changes##
```git commit -m 'message about changes'```
Сheck status
```git status```
##Chek version log##
```git log```

###GitHub###
https://github.com

##Create SSH key##
_Go to home directory_
```ssh-keygen -t ed25519 -C rbalavin@gmail.com```
```ls -a .ssh/```
__Copy public key__
```pbcopy < ~/.ssh/id_ed25519.pub```
##Create repository on https://github.com##
_Go to directory_
```cd 'directory path'```
```git remote add origin git@github.com:rbalavin/'name repository'.git```
```git push -u origin master``` first
```git push``` second

