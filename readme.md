# Git Guide
### 1. Config user
```
git config --global user.name "Allan Quintieri" 
git config --global user.mail "444190.clot@fje.edu" 
git config --list
```
### 2. Init Git
```
mkdir "Git Guide"
cd " .\Guit Guide"
git init
dir -hidden
```
### 3. First Commit
```
git status
git add .\file.text
git status
git commit -m "Commit message: brief description"
git status
```
### 4. Create Branch
```
git branch dir/readme/steps-4-to-6
git branch
```
### 5. Checkout Branch
```
git checkout dit/readme/steps-4-to-6
git status
```
### 6. Merge to Master
```
git checkout master
git status
git merge dir/readme/steps-4-to-6
git status
git log
```