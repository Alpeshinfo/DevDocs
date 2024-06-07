# Git Commands Cheat Sheet

##### Git Installation

**Install Git on Ubuntu:**
   ```bash
   sudo apt-get update
   sudo apt-get install git
```
**Install Git on CentOS**

```bash
sudo yum update
sudo yum install git
```

**Verify Git installation**:
```bash
git --version
```
### Basic Git Commands
> **git init** : Initialize a new Git repository.</i>
**git clone <repository>**: Clone a repository into a new directory.
**git status** : Show the working tree status.
**git add <file>** : Add file(s) to the staging area.
**git commit -m "message"** : Commit changes with a message.
**git push** : Push local changes to a remote repository.
**git pull** : Fetch from and integrate with another repository or a local branch.
**git branch** : List, create, or delete branches.
**git checkout <branch>**: Switch branches or restore working tree files.
**git merge <branch>**: Merge changes from a specified branch into the current branch.
**git fetch**: Download objects and refs from another repository.
 

### Repository Management

> **git remote add origin <repository>** : Add a remote repository.
**git remote -v**: List all remote repositories.
**git remote show origin** : Show information about a remote repository.
**git remote rename <old> <new>** : Rename a remote.
**git remote remove <repository>** : Remove a remote repository.
**git tag**: Create, list, delete or verify a tag object.

### Undoing Changes

**git reset <file>**: Unstage file(s) from the staging area.
**git checkout -- <file>**: Discard changes in working directory.
**git revert <commit>**: Revert a commit.
**git reset --hard <commit>**: Reset to a previous commit and discard changes.
**git clean -f**: Remove untracked files from the working directory.

### Branching and Merging
>**git branch**: List, create, or delete branches.
**git checkout <branch>**: Switch branches or restore working tree files.
**git merge <branch>**: Merge changes from a specified branch into the current branch.
**git rebase <branch>**: Reapply commits on top of another base tip.
**git cherry-pick <commit>**: Apply changes from a specific commit.
