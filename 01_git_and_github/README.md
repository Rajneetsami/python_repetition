
📘 Git & GitHub Notes
🔹 What is Git?
Git is a distributed version control system used to:
Track changes in your project (offline)
Maintain project history
Collaborate with team members
Safely experiment using branches
Restore previous versions ("time travel")
It is risky to work without version control because:
You can lose code
You can’t easily track what changed
Collaboration becomes messy
✅ Best practice: Commit frequently to maintain a clean history.

🔹 What is GitHub?
GitHub is a cloud-based platform that allows developers to:
Store Git repositories online
Collaborate with others
Share projects
Manage code using pull requests
Git works locally.
GitHub works online.

💻 Important Terminal Commands
mkdir        # Create a folder
ls           # List files
cd folder    # Enter folder
cd ..        # Go back one folder
ls -a        # Show hidden files
clear        # Clear terminal

🔧 Important Git Commands
🔹 Check Git Setup
git --version
git config --global user.name "First Name"
git config --global user.email "email@example.com"
git config --list

🔹 Start a Repository
git init              # Initialize repository
git clone <url>       # Clone repository

🔹 Basic Workflow
git status            # Check changes
git add .             # Add all changes
git commit -m "message"
git log               # View commit history

🔹 Working with Remote (GitHub)
git remote -v
git push origin main
git pull origin main
git push -u origin main

🔹 Branching
git branch                     # List branches
git checkout -b new-branch     # Create & switch branch
git checkout main              # Switch to main
git branch -d branch-name      # Delete branch
git merge branch-name          # Merge branch

🔹 Comparing Changes
git diff
git diff branch-name

🔹 Reset Commands (Be Careful ⚠️)
git reset file-name                 # Unstage file
git reset                           # Unstage all
git reset HEAD~1                    # Go back 1 commit (soft)
git reset <commit-hash>
git reset --hard <commit-hash>      # Delete commits permanently
⚠️ --hard removes commits and changes permanently.