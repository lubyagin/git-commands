# Краткое пособие по параметрам Git

`git init --bare` - Use a bare repository as a central server/hub to share your changes with other people.

`git clone` - Скопировать дерево файлов из удалённого (remote) Git-каталога

```
 git clone https://github.com/lubyagin/git-commands.git
 cd git-commands
 touch README
 git add README
 git commit -m "empty README"
 git push
```

