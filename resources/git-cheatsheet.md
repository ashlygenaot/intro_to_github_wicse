# Git Cheat Sheet

## 1. Check Your Status

```bash
git status
```
Shows the current state of your working directory, including changed and untracked files.

---
## 2. Create a Branch

```bash
git switch -c feature/your-name
```
Creates a new branch and switches you to it.

Example:
```bash
git switch -c feature/ashly
```

---
## 3. Check Your Branch
```bash
git branch
```
Shows your local branches. The * indicates the branch you're currently on.

---
## 4. Stage Your Changes
```bash
git add .
```
Stages all changed and new files for your next commit.

---
## 5. Commit Your Changes
```bash
git commit -m "Add my profile"
```
Creates a snapshot of your staged changes.

---
## 6. Push Your Branch
The first time you push a new branch:
```bash
git push -u origin feature/your-name
```

After that, you can usually use:
```bash
git push
```
Push = send your local commits to GitHub.

---
## 7. Switch Branches
```bash
git switch main
```
Switches you to the main branch.

To switch to an existing feature branch:
```bash
git switch feature/your-name
```

---
## 8. Pull Changes
```bash
git pull origin main
```
Downloads the latest changes from GitHub and updates your local branch.

Pull = get changes from GitHub.

---
## The GitHub Workflow
```bash
Fork
  ↓
Clone
  ↓
Branch
  ↓
Edit
  ↓
Commit
  ↓
Push
  ↓
Pull Request
  ↓
Review
  ↓
Merge
```

---
## Git vs. GitHub
Git = version control tool that tracks changes to your project.

GitHub = platform that hosts Git repositories and helps teams collaborate.

---
## When You're Stuck
Start with:
```bash
git status
```

Read Git's output before running another command.

### If you're still stuck, ask for help!
