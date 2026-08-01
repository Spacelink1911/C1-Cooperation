# Shared Repository for Group C1 of the 15th Competition. 

# Git
> This Log is for rebuilding the repository and the website.
## **Add & Status**
To create and **initialize** a Git repository:
```batch
git init
```
This creates a new subdirectory named .git that contains all of your necessary repository files — a Git repository skeleton.
To gain a copy of an already existed repository:
```batch
git clone
git clone https://github.com/libgit2/libgit2
```
To check the status of your git repository:
```batch
git status
```
If the status hasn't changed:
```batch
On branch main
No commits yet
nothing to commit (create/copy files and use "git add" to track)
```
If the status has changed (e.g. a file named 'README' was added to the directory):
```batch
On branch main
No commits yet
Untracked files:
    (use "git add <file>..." to include in what will be committed)
	README
nothing added to commit but untracked files present (use "git add" to track)
```
To **add** the 'README' to the repository:
```batch
> git add README
```
To remove the 'README' from the repository:
```batch
git rm README
```
To rename the 'README' (let's say, rename it as 'README.md'):
```batch
git mv README README.md
```
To show the **detailed** updates of the files whose changes not staged for commit:
```batch
> git diff
```
To **submit** the update:
```batch
git commit
```

## **Log**
To view the history:
```batch
git log
git log -p
git log --stat
```

## **Remote**
To see which remote servers you have configured:
```batch
git remote
```
To push the local repository to the one on github:
```batch
git push -u origin main
```