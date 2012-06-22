kornett
=======

Nytt intranett for korene på Samfundet


Gaid for oppsett
* github: fork repo
* git clone git@github.com:<USERNAME>/kornett.git
* cd kornett
* git remote add --tags tss git://github.com/TrondhjemsStudentersangforening/kornett.git
* git remote set-url --push tss ""
* git fetch tss
* git checkout develop

Hver gang før squash & pull request:
* git pull --rebase tss develop
