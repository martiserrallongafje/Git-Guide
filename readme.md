# Git Guide

### 1. Config user
```
git config --global user.name "Your Full Name"
git config --global user.email "your-email-address"
git config --list
```

### 2. Init git
```
mkdir "Git Guide"
cd ".\Git Guide"
git init
dir -hidden
```

### 3. First Commit
```
git status
git add <file>
git status
git commit -m "Commit message: brief description"
git status
```

### 4. Create Branch
```
git branch dir/branch-name
git branch
```

### 5. Checkout Branch
```
git checkout dir/branch-name
git status
```

### 6. Merge to master
```
git checkout master
git status
git merge dir/branch-name
git status
```
