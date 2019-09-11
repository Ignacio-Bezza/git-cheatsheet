# ReadMe.md

This is my git cheat sheet. #Keepitasecret
This is me addoing texty remotely

## git commands

```bash
git init REPO-NAME
```
- This will create repository called REPO-NAME
	
```bash
git status
```
- shows the status of the git repository

```bash
git show
``
- shows the commit history and changes

```bash
git add FILENAME ANOTHERFILENAME
```
- adds the files FILENAME and ANOTHERFILENAME to the stash

```bash
git commit -m "MESSAGE"
```
- commits the stashed files to the repo, and adds
the MESSAGE that describes what was done 

```bash
git log
```
- It shows history of the commits made to this point of time.

```bash
git config --global alias.adog "log --all --decorate --oneline --graph
```
- creates a git alias for the log all decorate oneline graph command.
- use this alias by entering `git adog` (much shorter)

```bash
git remove 
- assign the remote "originb" to the URI given
- replace URI with the relevant github/etc location

```bash
git push -u origin master 
```
- Push the committed changes to the "origin"


## Other GIT Things

**.gitignore** is a file that tells git files/folders that are
not to the part of the repository (that is - 
ignored when adding/committing)

# Comprehensive .gitignore found at:
# https://github.com/github/gitignore/blob/master/Python.gitignore
