# commands
git commands
# create a new git folder
``` git
cd <folder>
git init
```
# push that folder to github
``` git
git remote add <name> <the url of your repository>
```
> i.e.
``` git
git remote add origin https://github.com/W-X-Dai/commands
```
# you need to update your local git folder if you add something new
``` git
git add .
```
and then push them to guthub

# check out if all files added to your local git
``` git
git status
```
# remember to choose the branch you want
``` git
git checkout <branch>
```
>i.e.
``` git
git checkout main
```
# git commit
> before pushing new file to github,you need to add a commit about it
``` git
git commit -m "<commit>"
```
> i.e.
``` git
git commit -m "test"
```
# now you can push your folder to github
``` git
git push <name> <branch>
```
> i.e.
``` git
git push origin main
```
# if you want to gain folder from github
> direct to your target folder first
> then 
``` git
git pull <name> <branch>
```
> i.e.
``` git
git pull origin main
```

# the terminal is too messy
``` git
clear
```

> enjoy github,have fun with git!
# reference
https://cynthiachuang.github.io/Generating-a-Ssh-Key-and-Adding-It-to-the-Github/
https://codertw.com/%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80/585490/
https://backlog.com/git-tutorial/tw/intro/intro2_1.html
https://backlog.com/git-tutorial/tw/stepup/stepup2_3.html
> thank these pages !


