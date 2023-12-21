<h1 align="center">Install GIT</h1>
<CODE>brew install git</CODE>
<h3 align="center">Add directory to GIT</h3>
<i>Go to directory<br></i>
<CODE>cd 'directory path'<br></CODE>
<CODE>git init<br></CODE>
<p>Сheck status<br></p>
<CODE>git status</CODE>
<h3 align="center">Adding changes</h3>
<CODE>git add 'name files'<br></CODE>
<CODE>git add --all<br></CODE>
<CODE>git add .<br></CODE>
<p>Сheck status<br></p>
<CODE>git status<br></CODE>
<h3 align="center">Save changes</h3>
<CODE>git commit -m 'message about changes'<br></CODE>
<p>Сheck status<br></p>
<CODE>git status<br></CODE>
<h3 align="center">Chek version log</h3>
<CODE>git log</CODE>

<h1 align="center">GitHub</h1>
<h1><a href="https://github.com">GitHub</a></h1>

<h3 align="center">Create SSH key</h3>
<i>Go to home directory<br></i>
<CODE>ssh-keygen -t ed25519 -C rbalavin@gmail.com<br></CODE>
<CODE>ls -a .ssh/<br></CODE>
<i>Copy public key<br></i>
<CODE>pbcopy < ~/.ssh/id_ed25519.pub<br></CODE>
<h3 align="center">Create repository on <a href="https://github.com">GitHub</a></h3>
<i>Go to directory<br></i>
<CODE>cd 'directory path'<br></CODE>
<CODE>git remote add origin git@github.com:rbalavin/'name repository'.git<br></CODE>
<p><CODE>git push -u origin master</CODE> first<br></p>
<p><CODE>git push</CODE> second</p>

