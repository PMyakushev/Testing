1. Как задать имя пользователя и адрес электронной почты
Имя пользователя нужно, чтобы привязывать коммиты к вашему имени. Это не то же самое, что имя пользователя учётной записи GitHub, с помощью которого выполняется вход в профиль на GitHub
git config --global user.name "Pavel Myakishev"
Кроме того, командой git config можно изменять адрес электронной почты, привязанный к вашим коммитам Git. Новый адрес электронной почты будет автоматически отображаться во всех дальнейших коммитах, поданных на GitHub через командную строку.
git config --global user.email "asercrut@yandex.ru"
git config --global credential.helper cache
git init
git add (Name fails)
git commit -m "Name commti"
git status
git log
git log -p
git show
git diff --staged
git diff
git rm dirname (name.md)
git rm dirname/* (name.md)
git mv dir1(name.md) dir2
git checkout (name.md)
git reset HEAD (name.md)
git reset HEAD
Clear
git commti --amend -m "new name commit"
git rever HEAD
git revert
git branch (name.branch)
git checkout -b (name.branch)
git branch
git branch -a
git branch -d (name.branch)
git branch -D (name.branch)
git push origin --delete (name.branch)
gir merge (name.branch)
git merge --no-ff (name.branch)
git log --graph
git log --oneline
git log --decorate
git log --all
git log --all --graph
git log --all --oneline
git log --all --decorate
git merge --abort
git reset
git remote add wecomeapp https://github.com/someurl
git remote -v
git remote show origin
git push origin main
git pull
git pull --verbose
git merge origin
git push --felete origin existing_branch
git rebase (name.branch)
git clone
](https://habr.com/ru/company/ruvds/blog/599929/)

