# Git Rebase

`git rebase` rewrites the commit history. It can be harmful to do it in shared branches. 

It can cause complex and hard to resolve merge conflicts. In these cases, instead of rebasing your branch against the default branch, consider pulling it instead. 

```
git pull origin master
```

It has a similar effect without compromising the work of your contributors.