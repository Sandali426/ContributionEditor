# Contribution Editor 💥

Boost your GitHub contribution graph with 100 backdated commits across 5 days!

This script automatically generates commits for the past 5 days (20 per day) and pushes them to your GitHub repository, giving the appearance of consistent activity.

---

## 📦 What It Does

- Creates **100 commits** (20 per day for 5 days).
- Each commit is backdated using `GIT_AUTHOR_DATE` and `GIT_COMMITTER_DATE`.
- Adds a simple line to `progress.txt` for each commit.

---

## 🛠 Requirements

- Git must be installed on your computer.
- A GitHub repository (use GitHub Desktop or Git Bash to sync).
- `bash` terminal (you can use Git Bash on Windows).

---

## 🚀 How to Use

1. **Clone this repo** or create your own and add the script:

   ```bash
   git clone https://github.com/Sandali426/ContributionEditor.git
   cd contributioneditor
