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
**git init** : <sub><sup>Initialize a new Git repository.</sup></sub><br>
**git clone <repository>**: <sub><sup>Clone a repository into a new directory.</sup></sub><br>
**git status** : <sub><sup>Show the working tree status.</sup></sub><br>
**git add <file>** : <sub><sup>Add file(s) to the staging area.</sup></sub><br>
**git commit -m "message"** : <sub><sup>Commit changes with a message.</sup></sub><br>
**git push** : <sub><sup>Push local changes to a remote repository.</sup></sub><br>
**git pull** : <sub><sup>Fetch from and integrate with another repository or a local branch.</sup></sub><br>
**git branch** : <sub><sup>List, create, or delete branches.</sup></sub><br>
**git checkout <branch>**: <sub><sup>Switch branches or restore working tree files.</sup></sub><br>
**git merge <branch>**: <sub><sup>Merge changes from a specified branch into the current branch.</sup></sub><br>
**git fetch**: <sub><sup>Download objects and refs from another repository.</sup></sub><br>
 

### Repository Management

**git remote add origin <repository>** : <sub><sup>Add a remote repository.</sup></sub><br>
**git remote -v**: <sub><sup>List all remote repositories.</sup></sub><br>
**git remote show origin** : <sub><sup>Show information about a remote repository.</sup></sub><br>
**git remote rename <old> <new>** : <sub><sup>Rename a remote.</sup></sub><br>
**git remote remove <repository>** : <sub><sup>Remove a remote repository.</sup></sub><br>
**git tag**: <sub><sup>Create, list, delete or verify a tag object.</sup></sub>

### Undoing Changes

**git reset <file>**: <sub><sup>Unstage file(s) from the staging area.</sup></sub><br>
**git checkout -- <file>**: <sub><sup>Discard changes in working directory.</sup></sub><br>
**git revert <commit>**: <sub><sup>Revert a commit.</sup></sub><br>
**git reset --hard <commit>**: <sub><sup>Reset to a previous commit and discard changes.</sup></sub><br>
**git clean -f**: <sub><sup>Remove untracked files from the working directory.</sup></sub>

### Branching and Merging
**git branch**: <sub><sup>List, create, or delete branches.</sup></sub><br>
**git checkout <branch>**: <sub><sup>Switch branches or restore working tree files.</sup></sub><br>
**git merge <branch>**: <sub><sup>Merge changes from a specified branch into the current branch.</sup></sub><br>
**git rebase <branch>**: <sub><sup>Reapply commits on top of another base tip.</sup></sub><br>
**git cherry-pick <commit>**: <sub><sup>Apply changes from a specific commit.</sup></sub><br>
