test-github
==========
Traerse un repositorio
> git clone http://github.com/.....

Basic git config
> git config --global user.name "Jaime"
> git config --global user.email "jaime84@gmail.com"

Generate ssh keys, github need key to identify you
> ssh-keygen

create a new repo
> git init
create a new file
> touch README2
add the new file to the repo
> git add README2
check the current repo status
> git status
commit the changes into the repo
> git commit -m "este es el primer archivo desde mi computadora"

Connect local repo with github repo
> git remote add origin https://github.com/jaimebl/test-github.git
> git pull origin master
Send README3 to github repo
> git push origin master

"README.md is modified externally"
> git add README.md (NOT SURE WHY IS NOT ADDED YET, IT COMES FROM GITHUB REPO)
> git commit -m "todos los comandos aprendidos"
> git push origin master

Creating branches
> git branch dev
> git branch mejorandola
Move to branch dev
> git checkout dev
Check branches
> git branch
Merge dev branch with current one (master in this case)
> git merge mejorandola

.gitignore => exclude files