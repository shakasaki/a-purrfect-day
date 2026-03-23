# 🐾 The Collaborative Cat Tale

Welcome to the Team Repository! This project is a hands-on exercise to practice **Git Collaboration** as outlined in Lecture 6.

## 📋 Project Instructions

Follow these steps to contribute to our story without breaking the "purr-fect" code.

### 1. Setup
* **Fork** this repository to your own GitHub account.
* **Clone** your fork to your local machine: `git clone <your-ssh-url>`.
* Verify your remote is set to **origin**: `git remote -v`.

### 2. Feature Branching
* **Create a new branch** for your contribution: `git switch -c <your-name>`.
* Add a short paragraph to `story.md`. Be creative!
* **Stage and Commit** your changes: `git add .` and `git commit -m "Add cat plot twist"`.

### 3. Collaboration & Pull Requests
* **Push** your branch: `git push --set-upstream origin <your-name>`.
* Open a **Pull Request (PR)** on GitHub from your branch into `main`.
* **Review** a teammate's PR: Leave a comment and approve it before merging.

### 4. Keeping it Clean
* If your push is rejected, **Pull** the latest changes: `git pull`.
* Use `git stash` if you need to pull while you have uncommitted work.
* Use `git blame story.md` to see who wrote which part of the final tale!.

### 5. Final Release
* Once the story is complete, one team member will create a **tag**:
    `git tag -a submission -m "Final Story Release"`.
    `git push --tags`.

---
