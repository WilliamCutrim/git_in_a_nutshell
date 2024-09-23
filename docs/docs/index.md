# Git Basics

## What is Git?
Git is a distributed version control system designed to handle everything from small to very large projects. However, it can also be use to register change in any kind of folder. 

## Commands

* `git init` - Initializes a new Git repository in the current directory.
* `git clone` [URL] - Clones an existing Git repository to your computer.
* `git add` [file] - Adds a specific file to the index (staging area) to be included in the next commit.
* `git commit` -m "[message]" - Creates a new commit with the files from the index and a description message.
* `git status` - Shows the current status of your working directory in relation to the repository.
* `git branch` - Lists all the branches present in the repository.
* `git checkout` [branch] - Switches to the specified branch.
* `git merge` [branch] - Merges the changes from the specified branch into the current branch.
* `git pull` - Fetches the latest changes from a remote repository into the current branch.
* `git push` - Sends local changes to a remote repository.
* `git rm` [file] - Removes a file from both the index and the working directory.
* `git stash` - Temporarily saves uncommitted changes to switch branches.

## Extra Commands

Git cheat sheet [git-cheat-sheet-education.pdf](https://education.github.com/git-cheat-sheet-education.pdf).


<?quiz?>
question: Are you ready?
answer-correct: Yes!
answer: No!
answer: Maybe!
content:
<h2>Provide some additional content</h2>

<?/quiz?>

<?quiz?>
question: What command is used to initialize a new Git repository?
answer-correct: git init
answer: git start
answer: git new
content:
<h2>The <code>git init</code> command creates a new Git repository in the current directory.</h2>
<?/quiz?>

<?quiz?>
question: What is the command to clone a repository from a URL?
answer-correct: git clone [URL]
answer: git copy [URL]
answer: git fetch [URL]
content:
<h2>The <code>git clone</code> command creates a local copy of a remote Git repository.</h2>
<?/quiz?>

<?quiz?>
question: Which command adds a file to the staging area in Git?
answer-correct: git add [file]
answer: git stage [file]
answer: git push [file]
content:
<h2>The <code>git add</code> command adds changes to the staging area, preparing them for a commit.</h2>
<?/quiz?>

<?quiz?>
question: How do you create a new commit with a message in Git?
answer-correct: git commit -m "[message]"
answer: git save -m "[message]"
answer: git push -m "[message]"
content:
<h2>The <code>git commit -m</code> command creates a commit with the staged changes and attaches a message.</h2>
<?/quiz?>

<?quiz?>
question: Which command shows the current status of your working directory?
answer-correct: git status
answer: git show
answer: git log
content:
<h2>The <code>git status</code> command provides information on the current state of your working directory and the index.</h2>
<?/quiz?>

<?quiz?>
question: What command lists all branches in a repository?
answer-correct: git branch
answer: git list
answer: git branches
content:
<h2>The <code>git branch</code> command shows all local branches in your repository.</h2>
<?/quiz?>

<?quiz?>
question: Which command is used to switch between branches?
answer-correct: git checkout [branch]
answer: git switch [branch]
answer: git branch [branch]
content:
<h2>The <code>git checkout</code> command is used to switch between branches in your Git repository.</h2>
<?/quiz?>

<?quiz?>
question: How do you merge changes from one branch into another?
answer-correct: git merge [branch]
answer: git rebase [branch]
answer: git integrate [branch]
content:
<h2>The <code>git merge</code> command integrates changes from one branch into another.</h2>
<?/quiz?>

<?quiz?>
question: Which command fetches changes from a remote repository and merges them into your current branch?
answer-correct: git pull
answer: git fetch
answer: git update
content:
<h2>The <code>git pull</code> command combines both <code>git fetch</code> and <code>git merge</code> in one step.</h2>
<?/quiz?>

<?quiz?>
question: What is the command to send local changes to a remote repository?
answer-correct: git push
answer: git send
answer: git upload
content:
<h2>The <code>git push</code> command sends your commits to a remote repository, such as GitHub.</h2>
<?/quiz?>
