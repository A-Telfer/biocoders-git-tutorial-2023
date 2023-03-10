# Github Quickstart

A more complete tutorial: https://docs.github.com/en/get-started/quickstart/hello-world

## Reference notes from today
Install a git cli (command line interface) for your system before starting! Here's one way to install it: https://git-scm.com/downloads

1. Create a repository on github
2. Clone it locally using the repository's address
*note it may be easier to clone `https://` links rather than `git@` links for first time users*
```
git clone git@github.com:A-Telfer/biocoders-git-tutorial-2023.git
```
3. Change directory to the github repository 
```
cd biocoders-git-tutorial-2023
```
4. Make some changes
5. Add (/stage) the changes
```
git add .
```
6. Commit the changes
```
git commit -m "some message"
```
7. Push the changes to the remote repository
```
git push 
```

## Git status shows you what will be committed
```
git status
```