## Git checkout

The `git checkout` command is traditionally used to switch between different branches in a Git repository. It allows you to change the state of your local repository to reflect the content of a specific branch, a specific commit, or even a specific file at a given point in history.

Common usage:

```
git checkout branch_name
```
### Create a new branch

```
git checkout -b branch_name
```

### Geting just one file from other branch

```
git checkout branch_name -- example.txt

git checkout feature_del -- docs/docs/git_del.md
```

## Git merge

The `git merge command` is used to combine changes made in two different branches. It takes the content of one branch and merges it into the branch you are currently on, creating a new commit in the process.

Common usage:
```
git merge branch_name
```

But we also can use `git pull` to merge branchs.

```
git pull branch_name
```

## Git rebase
The `git rebase` command is another way to integrate changes from one branch into another. Unlike `git merge`, which combines the histories of the two branches by creating a new commit, git rebase moves or combines the series of commits to a new "base branch", often maintaining a linear history. 

Common usage:
```
git rebase base_branch_name
```