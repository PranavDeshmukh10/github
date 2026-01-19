# Below are the commonly used commands for GitHub.

# 🔢 Version

## Git Version
This command is used to check git version install in the PC.
```bash
git --version
```

---

# 📂 Repository Commands

## Initialize a Repository
This command is used to initialize an empty repository.
```bash
git init
```

## Clone a Repository
This command is used to clone the repository
```bash
git clone <repository-url>
```

---

# 📄 File & Status Commands

## Check Status
Below command is used to check the status of the current repository.
```bash
git status
```

## Add a file
This command is used to add a file from Untracked to Staged.
```bash
git add <file_name>
```

## Commit Changes
This command is used to commit/add the file to repo (to move the file from Staged to Tracked)
```bash
git commit -m "commit message"
```
Note: Message (-m "commit message") is a mandotory thing. Without message the file will not get commit to the repo. Message can be anything.

## Remove the file
This command is used to remove a file from Staged (to Unstaged the file)
```bash
git rm --cached <file_name>
```

## Restore a file
This command is used to restore a deleted file.
```bash
git restore <file_name>
```

---

# 🌿 Branching Commands

## List Branches
```bash
git branch
```

## Creat a Branch
```bash
git branch branch-name
```

## Switch Branch
```bash
git checkout branch-name
```
OR
```bash
git switch branch-name
```

## Delete Branch
```bash
git branch -d branch-name
```

---

# 🔀 Merging & Rebase

## Merge Branch
```bash
git merge branch-name
```

## Rebase
```bash
git rebase branch-name
```

---

# 🚀 Remote Repository Commands

## Set Remote Repo.
This is used to see if the remote repo is added or not.
```bash
git remote -v
```

## Add Remote
```bash
git remote add origin <repo-url>
```

## Push Changes
This command is used to push the file to the GitHub repo which is present in GitHub GUI.
```bash
git push origin branch-name
```
Note: To push the files, you will need access to GitHub. Always use peronal acces tokens instead of your username and password to access the GitHub.

## Push & Create a Branch
This will creat a branch as 'master' and will push the changes or code.
```bash
git push origin master
```
Note: Here master is the name for the branch. The name can be anything.

## Pull Code
This command is used to pull the file/code from the GitHub repo to your local machine.
```bash
git pull origin branch-name
```

---

# 🔄 Stash Commands

```bash
git stash
```
```bash
git stash list
```
```bash
git stash apply
```

---

# 🧹 Undo & Reset

## Undo Last Commit
```bash
git reset --soft HEAD~1
```

## Hard Reset
```bash
git reset --hard commit-id
```

---

# 🏷️ Tags

```bash
git tag v1.0
```
```bash
git push origin v1.0
```


