📘 Git Commands Cheat Sheet

A simple and clear guide to commonly used Git commands for beginners.

🚀 Initial Setup
Command	Description
git init	Initialize a new Git repository
git clone <url>	Clone an existing repository
git config --global user.name "Your Name"	Set username
git config --global user.email "email@example.com"	Set email


📁 Staging & Committing
Command	Description
git status	Check file status (modified, staged, untracked)
git add .	Stage all changes
git add <file>	Stage a specific file
git commit -m "message"	Commit staged changes
git log	View commit history


🌿 Branching Commands
Command	Description
git branch	List all branches
git branch <branch-name>	Create a new branch
git checkout <branch>	Switch to a branch
git checkout -b <branch>	Create and switch to new branch
git branch -d <branch>	Delete a branch
🔄 Merging Branches

Command	Description
git merge <branch>	Merge selected branch into current branch
git merge --abort	Cancel merge if conflict occurs
git rebase <branch>	Reapply commits on top of another base branch

⏫ Push & Pull
Command	Description
git push	Push commits to remote repo
git push origin <branch>	Push specific branch
git pull	Fetch + merge changes from remote
git fetch	Fetch changes but don’t merge

🗂️ Undo & Fix Commands
Command	Description
git reset <file>	Unstage a file
git reset --hard	Remove all local changes permanently
git revert <commit>	Undo a commit by creating a new one
git restore <file>	Restore file to last commit

🌐 Remote Repository
Command	Description
git remote -v	View remote URLs
git remote add origin <url>	Add remote repository
git remote remove origin	Remove remote
🐧 Basic Linux Commands (For README)
Command	Meaning
ls	List files and folders
cd <folder>	Change directory
pwd	Show current path
mkdir <name>	Create a folder
rm <file>	Delete a file
rm -r <folder>	Delete a folder
cp <src> <dest>	Copy files
mv <old> <new>	Move or rename files
touch <file>	Create an empty file
cat <file>	Display file contents
clear	Clear terminal screen
🔥 Git Workflow Example

1️⃣ Initialize project

git init


2️⃣ Create and switch to new branch

git checkout -b feature/login


3️⃣ Stage and commit changes

git add .
git commit -m "Add login UI"


4️⃣ Push branch to GitHub

git push origin feature/login


5️⃣ Merge to main

git checkout main
git merge feature/login