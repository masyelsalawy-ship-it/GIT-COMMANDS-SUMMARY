# Git & GitHub Commands

## 1. Git Three Main Areas

1. Working Directory → The place where we create and modify files.
2. Stage Index (Staging Area) → The place where we prepare changes before committing.
3. Repository (Repo) → The place where committed changes are stored.

**Note:** Every commit has a unique ID (Commit Hash).

## 2. Basic Git Commands

- git add .` → Add all changes to the staging area.
- git commit -m "message"` → Save changes with a commit message.
- git status` → Show the status of files.
- git restore .` → Discard unstaged changes in all files.
- git restore file_name` → Discard unstaged changes in a specific file.
- git show commit_id` → Show details of a specific commit.
- git diff` → Show differences between working directory and staging area.
- git diff --staged` → Show differences between staging area and repository.

## 3. Git Log Commands

- git log` → Show commit history.
- git log --oneline --all` → Show all commits in a short format.

## 4. HEAD Command

- git reset HEAD~number` → Move HEAD to an earlier commit according to the specified number.

## 5. Branch Commands

- git branch branch_name` → Create a new branch.
- git switch branch_name` → Switch to another branch.
- git checkout -b branch_name` → Create and switch to a new branch.
- git branch` → Show all local branches.
- git merge branch_name` → Merge another branch into the current branch.
- git checkout branch_name` → Switch to an existing branch.

## 6. Repository Commands

- git init` → Initialize a new Git repository.
- git rm --cached file_name` → Remove a file from Git tracking but keep it on the computer.

## 7. Remote Repository Commands

- git remote -v` → Show remote repository URLs.
- git remote add origin repo_link` → Connect the local project to a remote repository.
- git push origin branch_name` → Push changes to the remote repository.
- git fetch remote_name branch_name` → Download remote updates without merging.
- git merge origin/branch_name` → Merge a remote branch into the current branch.
- git pull origin branch_name` → Fetch and merge remote changes in one step.
- git push --set-upstream origin branch_name` → Push a branch and set its upstream tracking branch.

## 8. Clone & Fork

- git clone repo_link` → Create a local copy of a remote repository.
- Fork → Create a copy of another repository on your GitHub account using the Fork button.

## 9. Git Workflow

Working Directory → git add → Staging Area → `git commit` → Repository

**Note:** Git is a version control system, while GitHub is a platform for hosting and sharing Git repositories.
