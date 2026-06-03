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
Create an SSH key to upload to your repository without having to type in your username and password every time.
-  Check if you have an Ed25519 algorithm SSH key already installed. ```ls ~/.ssh/id_ed25519.pub```
-  If no such file or directory, then create a new SSH key:
```Bash
ssh-keygen -t ed25519
```
Log into GitHub and click on your profile picture in the top right corner. Then, click on Settings.
SSH and GPG keys >> New SSH Key >> Copy your public SSH key ```cat ~/.ssh/id_ed25519.pub``` >> Paste the key as Authentication Key and then, click Add SSH key.


