<h1 align="center">Install GIT</h1>
`brew install git`
<h1 align="center">Add directory to GIT</h1>
_Go to directory_
```cd 'directory path'```
```git init```
Сheck status
```git status```
<h1 align="center">Adding changes</h1>
```git add 'name files'
git add --all
git add .```
Сheck status
```git status```
<h1 align="center">Save changes</h1>
```git commit -m 'message about changes'```
Сheck status
```git status```
<h1 align="center">Chek version log</h1>
```git log```

<h1 align="center">GitHub</h1>
<a href="https://github.com">GitHub</a>

<h1 align="center">Create SSH key</h1>
_Go to home directory_
```ssh-keygen -t ed25519 -C rbalavin@gmail.com```
```ls -a .ssh/```
__Copy public key__
```pbcopy < ~/.ssh/id_ed25519.pub```
<h1 align="center">Create repository on <a href="https://github.com">GitHub</a></h1>
_Go to directory_
```cd 'directory path'```
```git remote add origin git@github.com:rbalavin/'name repository'.git```
```git push -u origin master``` first
```git push``` second

