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
**git init** : <i>Initialize a new Git repository.</i><br>
**git clone <repository>**: <i>Clone a repository into a new directory.</i><br>
**git status** : <i>Show the working tree status.</i><br>
**git add <file>** : <i>Add file(s) to the staging area.</i><br>
**git commit -m "message"** : <i>Commit changes with a message.</i><br>
**git push** : <i>Push local changes to a remote repository.</i><br>
**git pull** : <i>Fetch from and integrate with another repository or a local branch.</i><br>
**git branch** : <i>List, create, or delete branches.</i><br>
**git checkout <branch>**: <i>Switch branches or restore working tree files.</i><br>
**git merge <branch>**: <i>Merge changes from a specified branch into the current branch.</i><br>
**git fetch**: <i>Download objects and refs from another repository.</i><br>
 

### Repository Management

**git remote add origin <repository>** : <i>Add a remote repository.</i><br>
**git remote -v**: <i>List all remote repositories.</i><br>
**git remote show origin** : <i>Show information about a remote repository.</i><br>
**git remote rename <old> <new>** : <i>Rename a remote.</i><br>
**git remote remove <repository>** : <i>Remove a remote repository.</i><br>
**git tag**: <i>Create, list, delete or verify a tag object.</i>

### Undoing Changes

**git reset <file>**: <i>Unstage file(s) from the staging area.</i><br>
**git checkout -- <file>**: <i>Discard changes in working directory.</i><br>
**git revert <commit>**: <i>Revert a commit.</i><br>
**git reset --hard <commit>**: <i>Reset to a previous commit and discard changes.</i><br>
**git clean -f**: <i>Remove untracked files from the working directory.</i>

### Branching and Merging
**git branch**: <i>List, create, or delete branches.</i><br>
**git checkout <branch>**: <i>Switch branches or restore working tree files.</i><br>
**git merge <branch>**: <i>Merge changes from a specified branch into the current branch.</i><br>
**git rebase <branch>**: <i>Reapply commits on top of another base tip.</i><br>
**git cherry-pick <commit>**: <i>Apply changes from a specific commit.</i><br>
