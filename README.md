# **Git Commands**

## _Repo initialization_
Make sure you are in the root directory of the project you want to push to source control.
```text
git init
```

## _Link to remote_
```text
git remote add origin <repo-url>
```

## _Add file to git_
```text
git add .
```

## _Commit your changes_
```text
git commit -m "<commit message>"
```

## _Create a new local branch_
```text
git checkout -b "<branch-name>"
```

## _Push local changes to server_
```text
git push origin <branch-name>
```

## _Delete local branch_
Make sure to be on another branch than the branch to delete.
```text
git branch -D <branch-name>
```

## _Merge change from another branch_
Make sure to be on the target branch.
```text
git merge <source-branch-name>
```

## _Rebase change from another branch_
Make sure to be on the target branch.
```text
git rebase <source-branch-name>
```

## _Revert your commits_
**--hard**: Reverts without trace.
```text
git revert --hard HEAD~1
```

**--soft**: Reverts to previous commit with original commit changes merged.
```text
git revert --soft HEAD~1
```
**HEAD~(n)**: _n_ signifies number of commit to revert.

