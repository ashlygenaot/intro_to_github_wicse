# Intro to GitHub — WiCSE

Welcome to the WiCSE Intro to GitHub workshop!

In this workshop, you'll learn the basics of Git and GitHub and practice a real collaborative development workflow.

## What You'll Learn

- Git vs. GitHub
- Repositories
- Branches
- Commits
- Pushes
- Pull requests
- Merging

## Workshop Workflow

```text
Fork → Clone → Branch → Edit → Commit → Push → Pull Request → Merge
```

---
## Hands-On Challenge

### Make Your First GitHub Contribution

Now it's your turn!

You'll contribute a small profile to this repository while practicing the GitHub workflow we just learned.

### 1. Fork the Repository

Click the Fork button at the top of this GitHub repository.

This creates your own copy of the repository under your GitHub account.

### 2. Clone Your Fork

Copy the URL of your fork and run:
```bash
git clone <your-fork-url>
```
Then move into the project:
```bash
cd intro-to-github-wicse
```
### 3. Create a Feature Branch

Create a new branch for your contribution:
```bash
git switch -c feature/your-name
```

Example:
```bash
git switch -c feature/ashly
```

Check that you're on the correct branch:
```bash
git branch
```
You should see a * next to your feature branch.

### 4. Create Your Profile

Create a new file inside the participants folder.

Name it:
```bash
participants/your-name.md
```

Example:
```bash
participants/ashly.md
```

Add the following information:
```bash
# Your Name

- Major:
- School:
- Year:
- Currently learning:
- GitHub:
```
Feel free to add another fun fact about yourself!

### 5. Check Your Changes

Before committing, check what Git sees:
```bash
git status
```
Make sure your new profile appears in the list of changes.

### 6. Commit Your Changes

Stage your changes:
```bash
git add .
```

Then create a commit:
```bash
git commit -m "Add your-name profile"
```

Example:
```bash
git commit -m "Add Ashly profile"
```
Remember: write a commit message that clearly describes what you changed!

### 7. Push Your Branch

Push your branch to GitHub:
```bash
git push -u origin feature/your-name
```

Example:
```bash
git push -u origin feature/ashly
```
Your branch should now appear on GitHub.

### 8. Open a Pull Request

Go to your GitHub repository.

You should see an option to Compare & pull request.

Create a pull request from:
```bash
your feature branch → main
```

Pull Request Title

Use:
```bash
Add Your Name profile
```

Example:
```bash
Add Ashly profile
```

Pull Request Description

Tell us what you changed:
```bash
## Changes

- Added my participant profile
- Added my GitHub username and current learning topic
```

### 9. Review Your Changes

Before merging, click the Files changed tab.

Look at the diff and make sure your changes are correct.

Ask yourself:

- Did I add the correct file?
- Is my information correct?
- Did I accidentally change anything else?

### 10. Merge Your Pull Request

Once your pull request is ready, merge it into main.

### Congratulations! You just made your first GitHub contribution!

---
## Challenge Checklist

Before you're finished, make sure you completed:

- Forked the repository
- Cloned your fork
- Created a feature branch
- Created your participant profile
- Checked git status
- Committed your changes
- Pushed your branch
- Opened a pull request
- Reviewed your diff
- Merged your pull request

---
## Finished Early?
Try one of these:

Option 1 — Customize the Starter Project

Open the starter-project folder and customize the HTML/CSS.

Option 2 — Review Someone Else's PR

Look at another participant's pull request and review their changes.

Option 3 — Add Something Extra

Add another section to your participant profile, such as:

- Favorite programming language
- Career goal
- Favorite project
- Fun fact

---
## Questions?

Ask one of the WiCSE workshop presenters for help!
