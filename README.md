test-github en la rama mejorandola
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

