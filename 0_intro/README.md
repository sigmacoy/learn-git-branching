# 1. How to commit?
```
git add .
git commit -m "your message"
git push {your_branch}
```

## if new to checkout branch
```
git push --set-upstream origin {your_branch}
```

# 2. Git Branches
New branch
```
git branch {branch_name_1}
git checkout {branch_name_1}
git commit -m "your message"
git push --set-upstream origin {branch_name_1}
```

## Check what branch current
```
git branch
```

## if you want to create a new branch AND check it out at the same time
```
git checkout -b [yourbranchname]
```

# 3. Branches and Merging
Assume you're in branch1. To merge with branch2:
```
git merge branch2
```

## 4. Rebase
Solution website:
```
git checkout -b bugFix
git commit
git checkout main
git commit
git checkout bugFix
git rebase main
```