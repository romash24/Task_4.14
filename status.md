[< к содержанию](./readme.md)

## git status

**git status** - проверяет текущее состояние репозитория. 

```
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   add.md
        modified:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        checkout.md
        clone.md
        commit.md
        reset.md
        status.md

no changes added to commit (use "git add" and/or "git commit -a")
```

`git status -s` - выводит статус в более компактном виде.

```
 M add.md
 M readme.md
?? checkout.md
?? clone.md
?? commit.md
?? reset.md
?? status.md
```