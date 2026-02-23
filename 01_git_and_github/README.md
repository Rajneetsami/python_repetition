# 📘 Git & GitHub Notes

---
I created a **local repository** on my computer to practice Git commands.  
I also pushed this repository to **GitHub**, so you can see the demo there:  

**GitHub Repo:** (https://github.com/Rajneetsami/localrepo.git)
**Note:** The `index.html` file includes a link to a YouTube video.

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
git init                     # initialize repo

git remote add origin <-link of repo->  # connect local repo to github

git clone <repository-url>   # clone existing repo

# 🔹 Basic Workflow
git status                   # check current status

git add .                    # add all files

git add <-file name>         # add specific file

git commit -m "Your message" # commit changes

git log # show commit history

# 🔹 Working with Remote (GitHub)
git remote -v                # verify remote

git push origin main         # push to github

git pull origin main         # pull latest changes

git push -u origin main      # Set upstream (future push: just git push)

# 🔹 Branching
git branch                    # List branches

git checkout -b new-branch    # Create & switch branch

git checkout main             # Switch branch

git branch -d branch-name     # Delete branch

git merge branch-name         # Merge branch

git branch -M main            # Rename branch



# 🔹 Comparing Changes
git diff

git diff branch-name

# 🔹 Reset Commands (Use Carefully ⚠️)

# unstage changes : 

Used when:

Changes are added (staged)

But NOT committed yet

You want them back to "modified"

git reset file-name

git reset

git restore file-name

# undo last commit

git reset HEAD~1

# undo multiple commits

git reset <commit-hash>

git reset --hard <commit-hash>

⚠️ Warning:
--hard removes commits and changes permanently.
Use it carefully.


# abbrevation

IDE = integrated development environment
M = modified
U = untracked files
m = message
PR = pull request

# merge conflicts

An event that takes place when git is unable to automatically resolve differences in a code between two commits.

# 📌 File States in Git

State	    Meaning

Untracked	New file not added yet

Modified	File changed

Staged	    File added and ready to commit

Unmodified	No changes