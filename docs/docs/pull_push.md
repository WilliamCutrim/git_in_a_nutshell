## Git pull

The `git pull` command is used to fetch changes made in a remote repository and merge those changes into your local repository. It essentially combines the functionalities of `git fetch` and `git merge`. 

`git fetch` updates local branches with updates from the remote repository but doesn't perform an automatic merge. git merge is responsible for merging those changes into the current branch. So, `git pull` performs both these operations in one step.

Common usage:
```
git pull origin main
```
This command pulls changes from the master branch of the remote repository identified as origin and merges those changes into the current branch of your local repository.

Pull example:
Common usage:
```
Some code
```

## Git push

The `git push` command is used to push your local changes to a remote repository. After you've committed your changes to your local repository, you can use `git push` to share them with other team members or to store them in a remote repository for backup and history.

Common usage:
```
git push origin main
```

# Quick Question

<?quiz?>
question: What is the command to send local changes to a remote repository?
answer-correct: git push
answer: git send
answer: git upload
content:
<h2>The <code>git push</code> command sends your commits to a remote repository, such as GitHub.</h2>
<?/quiz?>