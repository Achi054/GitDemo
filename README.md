# Git Commands

## Repo initialization
Make sure you are in the root directory of the project you want to push to source control.
```text
git init
```

## Link to remote
```text
git remote add origin <repo-url>
```

## Add file to git
```text
git add .
```

## Commit your changes
```text
git commit -m "<commit message>"
```

## Create a new local branch
```text
git checkout -b "<branch-name>"
```

## Push local changes to server
```text
git push origin <branch-name>
```

## Delete local branch
Make sure to be on another branch than the branch to delete.
```text
git branch -D <branch-name>
```

## Merge change from another branch
```text
git merge <source-branch-name>
```