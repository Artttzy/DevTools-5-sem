# Васильев Артём Сергеевич М33041
## Лабораторная работа №2

### 1. Было использовано расширение Git Graph
### 2. Комманды:
    git checkout ci
    git rebase -i HEAD~2
    git checkout master
    git cherry-pick ci
    git branch -D ci
![](docs\t1.jpg)
![](docs\t2.jpg)
### 3. Комманды:
    git reflog
    git checkout aca3abb
    git branch old-master
![](docs\t3.jpg)
### 4. Комманды:
    git blame prisma/seed.ts
![](docs\t4.jpg)
### 5. Команды:
    npm install --save-dev jest
    git checkout master
    git bisect start
    git bisect bad
![](docs\t5.jpg)
![](docs\t6.jpg)
### 6. Команды:
    git filter-branch --tree-filter "rm -f .env" -- --all
    echo .env >> .gitignore
![](docs\t7.jpg)
![](docs\t8.jpg)
### 7. Команды:
    git filter-branch -f --env-filter "GIT_AUTHOR_NAME=''; GIT_AUTHOR_EMAIL=''; GIT_COMMITTER_NAME='' GIT_COMMITTER_EMAIL=''" HEAD~1..HEAD
![](docs\t9.jpg)
![](docs\t10.jpg)
### 8. Команды:
    git config rerere.enabled true
    git merge feature

    git reset --hard HEAD~1
    git merge feature
![](docs\t11.jpg)
### 9. Команды:
    git fsck
![](docs\t12.jpg)### 8. Команды:
    git config rerere.enabled true
    git merge feature
### 10. Команды:
    git gc --prune=now --aggressive
![](docs\t13.jpg)
### 11. Команды:
    git remote add origin https://github.com/Artttzy/DevTools-5-sem.git
    git push -u origin master
    git branch report
    git add -p
    e