# Git and Bitbucket Branching

## What is Branching?
Branching in Git and Bitbucket allows developers to isolate their work from others, making it possible to work on multiple features or fixes simultaneously without affecting the main codebase.

## Commands for Git

* `git branch <name>` - Creates a new branch locally.
* `git checkout -b <name>` - Creates a new branch and switches to it.
* `git push -u origin <name>` - Pushes the new branch to the remote repository and sets up tracking.

## Commands for Bitbucket

### Via Web Interface
1. **Navigate to the repository:** Open your repository in Bitbucket.
2. **Create a New Branch:** Click on 'Create branch' in the sidebar.
3. **Set Details:** Choose the branch name, type (feature, hotfix, etc.), and the base branch.
4. **Create:** Click 'Create' to finalize the branch creation.

## Quick Question

<?quiz?>
question: From which branch should all new development or hotfix branches be created?
answer-correct: main
answer: test_development
answer: feature
content:
<h2>According to best practices, all branches for new development or hotfixes should be created from the <code>main</code> branch to ensure they start from a stable base.</h2>
<?/quiz?>

<?quiz?>
question: Which command do you use to create and switch to a new branch simultaneously?
answer-correct: git checkout -b new-branch-name
answer: git branch -m new-branch-name
answer: git switch new-branch-name
content:
<h2>To create and immediately switch to a new branch, you can use <code>git checkout -b new-branch-name</code>. This is a convenient shortcut for creating a new branch and then checking it out in one step.</h2>
<?/quiz?>

## Extra Resources

* Git cheat sheet [git-cheat-sheet-education.pdf](https://education.github.com/git-cheat-sheet-education.pdf).
* Bitbucket branching model guide [bitbucket-branching-model](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow).
