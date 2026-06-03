# Git Basics
## Setting up Git
```Bash
git config --global "Your Name"
git config --global yourEmail@example.com
```
GitHub recently changed the default branch on new repositories from **master** to **main**.
```Bash
git config --global init.defaultBranch main
```
To verify that things are working properly:
```Bash
git config --get user.name
git config --get user.rmail
```
