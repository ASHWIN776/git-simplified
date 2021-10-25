# Git Simplified

## What is Git?

Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

Git is software that runs locally. Your files and their history are stored on your computer. You can also use online hosts (such as GitHub or Bitbucket) to store a copy of the files and their revision history. Having a centrally located place where you can upload your changes and download changes from others, enable you to collaborate more easily with other developers. Git can automatically merge the changes, so two people can even work on different parts of the same file and later merge those changes without losing each other’s work!

## Installing GIT

### In Windows
The most official build is available for download on the Git website. Just go to https://git-scm.com/download/win and the download will start automatically.

### In Linux
For Debian based distribution, use `apt`:
```
$ sudo apt install git-all
```

### In macOS
There are several ways to install Git on a Mac. The easiest is probably to install the Xcode Command Line Tools. On Mavericks (10.9) or above you can do this simply by trying to run git from the Terminal the very first time.
```
$ git --version
```

## Git Setup
The first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information.

```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

## Recording Changes to the Repository
1. Checking the status of files
```
$git status
```

2. Tracking New Files and Staging them
```
$ git add <fileName>
```

3. Committing your Changes
```
$ git commit
```
## Viewing Commit History
After you have created several commits, or if you have cloned a repository with an existing commit history, you’ll probably want to look back to see what has happened.
```
git log
```
