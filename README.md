# Git Workflow Guide

A simple reference for commonly used Git commands.
Use this guide for daily Git operations.

---

## 📌 Check Repository Status

Shows the current state of the working directory and staging area.

```bash
git status
```
📥 Stage Changes

Add files to the staging area.

Stage all changes:
```bash
git add .
```
Stage a specific file:
```bash
git add <filename>
```
Stage multiple files:
```bash
git add <file1> <file2>
```
💾 Commit Changes

Save staged changes with a descriptive message.
```bash
git commit -m "Describe what you changed"
```
🚀 Push Changes

Upload local commits to the remote repository.

Push to default (usually main/master):
```bash
git push
```
Push to a specific branch:
```bash
git push origin <branch-name>
```
🔄 Common Workflow

Most commonly used Git command sequence.
```bash
git status
git add .
git commit -m "Describe what you changed"
git push
```
⚙️ First-Time Git Setup (Optional)

Set your global Git identity.
Bash
```bash
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```
🌿 Basic Branch Commands (Optional)

List branches:
```bash
git branch
```
Create a new branch:
```bash
git branch <branch-name>
```
Switch branches:
```bash
git checkout <branch-name>
```
Create and switch in one command:
```bash
git checkout -b <branch-name>
```
⬇️ Pull Latest Changes

Fetch and merge changes from the remote repository.
```bash
git pull
```