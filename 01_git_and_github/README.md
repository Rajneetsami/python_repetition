# 📘 Git & GitHub Notes

---

## 🔹 What is Git?

Git is a **distributed version control system** used to:

- Track changes in your project (offline)
- Maintain project history
- Collaborate with team members
- Safely experiment using branches
- Restore previous versions ("time travel")

### ⚠️ Why Version Control Is Important

Working without version control is risky because:

- You can lose code
- You can’t easily track changes
- Collaboration becomes messy

✅ **Best Practice:** Commit frequently to maintain a clean and meaningful history.

---

## 🔹 What is GitHub?

GitHub is a **cloud-based platform** that allows developers to:

- Store Git repositories online
- Collaborate with others
- Share projects
- Manage code using pull requests

**Git works locally.**  
**GitHub works online.**

---

# 💻 Basic Terminal Commands


mkdir folder-name    # Create a folder
ls                   # List files
cd folder-name       # Enter folder
cd ..                # Go back one folder
ls -a                # Show hidden files
clear                # Clear terminal


# 🔧 Important Git Commands

# 🔹 Check Git Setup
git --version
git config --global user.name "Your Name"
git config --global user.email "email@example.com"
git config --list

# 🔹 Start a Repository
git init
git clone <repository-url>

# 🔹 Basic Workflow
git status
git add .
git commit -m "Your message"
git log

# 🔹 Working with Remote (GitHub)
git remote -v
git push origin main
git pull origin main
git push -u origin main

# 🔹 Branching
git branch
git checkout -b new-branch
git checkout main
git branch -d branch-name
git merge branch-name

# 🔹 Comparing Changes
git diff
git diff branch-name

# 🔹 Reset Commands (Use Carefully ⚠️)
git reset file-name
git reset
git reset HEAD~1
git reset <commit-hash>
git reset --hard <commit-hash>
⚠️ Warning:
--hard removes commits and changes permanently.
Use it carefully.