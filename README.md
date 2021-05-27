# Git-Practices

Start initilizing git in the git bash!

```
git init
```

## Actualize your branches!
Every day, before start working in a project with my team, i have to actualize the **branches**:

```
git fetch
```

### what if two or more persons are working in the same **branch**?
Remenber always to pull all the work that is currently in the remote branch!

**First check that you are in the branch you want to work!**
```
git branch -a
```
The one with the asterisk (`*`) is the where you actually are! 
If you're not in the desired branch you have to change branches:
```
git checkout <name-desired-branch>
```

One you're in the desired branch to work, (or if you already were) just pull!
```
git pull <link-repo> <branch-name>
```

## Commit&Push regulary!
Remenber always to push regularly to save your work!  

**First check that you are in the branch you want to work! It is important to push in the right branch!**
```
git branch -a
```
The one with the asterisk (`*`) is the where you actually are! 
If you're not in the desired branch you have to change branches:
```
git checkout <name-desired-branch>
```

One you're in the desired branch to work, (or if you already were) commit and push!
```
git add * 
git commit -m "<message>"
git pus <link-repo> <branch-name>
```

*Remenber that in `git add *` the asteriks means to add all the files into the commit*


