# First Week ALX Git Commands Assignment
<!-- Code Blocks -->
```git
   git init 
   git status
   git add .
```
>This add all unstaged files 
>
>select a file name to add selected files

```git
   git commit -m "Brief Message For Your Commit"
   git remote add origin https://github.com/username/new_repo
```
>Copy & Paste Your new_repo URL 
```git
git push -u origin master
```
>Create New Branch If Not Exist 
```git
git checkout -b new_branch
```

>Select That Branch To Work On it
```git
git checkout new_branch
```


>List Branches
```git
git branch
```

>Merge Different Branches
>select main or master based on your default branch 
```git
git checkout new_branch
git merge main/master
```
>Use Rebase for a clear commit history instead of merge
>check before use it . May cause lose of commit history of your team mates
```git
git checkout new_branch
git rebase main/master
```

>Branch force
>This Move A new_branch to commit history c1 
```git
git checkout new_branch
git branch -f new_branch c1
```

>Rollbacks 
>git reset move back to parent commit as if no commit is done before
>While resetting works great for local branches on your own machine, 
its method of "rewriting history" doesn't work for remote branches that 
others are using.

In order to reverse changes and share those reversed changes with others, we need to use git revert. Let's see it in action.
```git 
git reset
git revert
```

>follow my github account for more(Yohannes Assebe/JohnAssebe)
