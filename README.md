<h1 align="center">Install GIT</h1>
<CODE>brew install git</CODE>
<h3 align="center">Add directory to GIT</h3>
<p><i>Go to directory: </i>
<CODE>cd 'directory path'</CODE><br>
<CODE>git init</CODE><br>
<i>Сheck status: </i>
<CODE>git status</CODE> (untracked/tracked, staged & modified)</p>

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git commit -m" --> tracked/comitted;
``` 

<h3 align="center">Adding changes</h3>
<p><CODE>git add 'name files'</CODE><br>
<CODE>git add --all</CODE><br>
<CODE>git add .</CODE><br></p>
<h3 align="center">Save changes</h3>
<CODE>git commit -m 'message about changes'<br></CODE>
<h3 align="center">Cheсk version log</h3>
<p><CODE>git log</CODE> full log<br>
<CODE>git log --oneline</CODE> abbreviated log</p>
<h1 align="center"><a href="https://github.com">GitHub</a></h1>
<h3 align="center">Create SSH key</h3>
<p><i>Go to home directory</i><br>
<CODE>ssh-keygen -t ed25519 -C rbalavin@gmail.com</CODE><br>
<CODE>ls -a .ssh/</CODE><br>
<i>Copy public key</i><br>
<CODE>pbcopy < ~/.ssh/id_ed25519.pub</CODE><br>
<i>Paste the public key in your <a href="https://github.com">GitHub</a> profile settings</i></p>
<h3 align="center">Create repository on <a href="https://github.com">GitHub</a></h3>
<p><i>Go to directory</i><br>
<CODE>cd 'directory path'</CODE><br>
<CODE>git remote add origin git@github.com:rbalavin/'name repository'.git</CODE><br>
<CODE>git push -u origin master</CODE> first<br>
<CODE>git push</CODE> second</p>
<h3 align="center">Chenge commit</h3>
<p>1) <CODE>--amend</CODE> calculation to work with the last commit (<CODE>HEAD</CODE>).<br>
2) You can add new files to a commit using <CODE>git commit --amend --no-edit</CODE>. Thanks to the <CODE>--no-edit</CODE> option, the commit message will remain as it was<br>
3) The command <CODE>git commit --amend -m "Updated commit message"</CODE> allows you to change the commit message.</p>

