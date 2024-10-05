# Mastering Git and GitHub

## ⚔️ Git Advices

1. Write your commit in the imperative form

2. When writing your commit message make it answer the following question
    - If applied to the codebase this commit will `________`


## 📊 Workflow

1. Clone the repo.
2. Create a new branch from the `main` or another branch.
3. Make your changes.
4. Push the branch to the remote repo.
5. Open a Pull Request.
6. Merge the changes.
7. Pull the merged changes into your local `main` branch.
8. Repeat from step `2`.

## 💻 Git Commands

### Check Git Version
```
git --version
```
- Displays the installed Git version.

### View Repository Status
```
git status
```
- Shows the working directory’s current state and the staging area.

### Initialize a Git Repository
```
git init
```
- Initializes a new Git repository in the current directory.

### Clone a Repository
```
git clone <repo-url>
```
- Clones a remote Git repository to your local machine.

### Stage Changes
```
git add <file>
```
- Stages changes for the next commit.

### Commit Changes
```
git commit -m "your message"
```
- Commits the staged changes with a descriptive message.

### Push Changes
```
git push origin <branch>
```
- Pushes the committed changes to a remote repository on the specified branch.

### Pull Changes
```
git pull origin <branch>
```
- Pulls the latest changes from the remote repository into your current branch.

### List Branches
```
git branch
```
- Lists all local branches in the repository.

### Create and Switch to a New Branch
```
git checkout -b <new-branch>
```
- Creates a new branch and switches to it.

### Switch to an Existing Branch
```
git checkout <branch>
```
- Switches to the specified branch.

### Force Checkout to Main Branch
```
git checkout -f main
```
- Discards local changes and switches to the 'main' branch.

### Revert a Commit
```
git revert <commit-hash>
```
- Reverts the specified commit without altering the commit history.

### Reset to a Previous Commit
```
git reset --hard <commit-hash>
```
- Resets the repository to a previous commit, removing all subsequent commits.

### Fetch Remote Changes
```
git fetch
```
- Downloads objects and refs from another repository, without merging.





