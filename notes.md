# Git & GitHub Learning Log

## Post 1 - Kicking Off the Series
Starting a series that breaks down Git and GitHub, one concept at a time.

## Post 2 - What is Version Control? And Why Git?
A version control system (VCS) tracks every change made to a set of files over time.
A few VCS tools exist (SVN, Mercurial, Perforce), but Git became the standard because it's distributed and works offline, unlike tools that depend on a central server.

## Post 3 - Git vs GitHub
Git is the tool that tracks changes on my computer. GitHub is where that project lives online, so it can be accessed from anywhere and shared with others.

## Post 4 - Installing Git & Creating a GitHub Account
Installed Git, verified it with git --version, and configured my identity with git config. 
Created a free GitHub account to host my repositories.

## Post 5 - What is a Repository?
A repository is a project folder that Git is tracking. It can be local (on my computer) or remote (hosted on GitHub). Created my first repo, Git-GitHub-Learning-Log.

## Post 6 - Cloning a Repository
Learned two ways to work with a repo: adding files directly on GitHub, or cloning the full repo, history included, onto my computer with git clone.

## Post 7 - Commits
Learned that a commit is a saved snapshot of my work.
Every change moves through three stages: working area, staging area, and committed files.

## Post 8 - Push & Pull
Learned that push sends my saved commits from my computer up to GitHub, and pull brings down any new commits from GitHub to my computer. 
Also practiced starting a project locally with git init, connecting it to GitHub with git remote add, and sending it up with git push.

## Post 9 - Branches
Learned that a branch is a separate copy of my project where I can try changes without touching main. Once I'm happy with the changes, they can be merged back into main.

## Post 11 - Merging & Merge Conflicts
Merging combines a branch's changes into main, usually automatically. 
But if two edits touch the exact same line differently, Git can't decide which is correct. 
That's a merge conflict, and it asks us to choose instead of silently overwriting one version.