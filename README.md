<h1 align="center">Install GIT</h1>
<CODE>brew install git</CODE>
<h3 align="center">Add directory to GIT</h3>
<i>_Go to directory_</i>
<CODE>cd 'directory path'</CODE>
<CODE>git init</CODE>
Сheck status
<CODE>git status</CODE>
<h3 align="center">Adding changes</h3>
<CODE>git add 'name files'</CODE>
<CODE>git add --all</CODE>
<CODE>git add .</CODE>
Сheck status
<CODE>git status</CODE>
<h3 align="center">Save changes</h3>
<CODE>git commit -m 'message about changes'</CODE>
Сheck status
<CODE>git status</CODE>
<h3 align="center">Chek version log</h3>
<CODE>git log</CODE>

<h1 align="center">GitHub</h1>
<a href="https://github.com">GitHub</a>

<h3 align="center">Create SSH key</h3>
<i>Go to home directory</i>
<CODE>ssh-keygen -t ed25519 -C rbalavin@gmail.com</CODE>
<CODE>ls -a .ssh/</CODE>
<i>Copy public key</i>
<CODE>pbcopy < ~/.ssh/id_ed25519.pub</CODE>
<h3 align="center">Create repository on <a href="https://github.com">GitHub</a></h3>
<i>Go to directory</i>
<CODE>cd 'directory path'</CODE>
<CODE>git remote add origin git@github.com:rbalavin/'name repository'.git</CODE>
<p><CODE>git push -u origin master</CODE> first</p>
<p><CODE>git push</CODE> second</p>

