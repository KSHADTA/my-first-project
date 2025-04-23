Git + GitHub Summary Cheat Sheet 📄


🔧 Setup

git config --global user.name "Your Name"      # Set your name


git config --global user.email "you@email.com" # Set your email

🚀 Create a Project and Push to GitHub

git init                            # Start Git in a folder

git add .                           # Stage all files
git commit -m "Initial commit"      # Commit changes
git remote add origin <repo-url>    # Link to GitHub
git push -u origin main             # Push to GitHub

🌱 Branching
git checkout -b feature-x           # Create + switch to new branch
git push -u origin feature-x        # Push branch to GitHub
git checkout main                   # Switch back to main
git merge feature-x                 # Merge feature into main
git push                            # Push merge to GitHub

⚠️ Undo / Clean Up
git reset HEAD <file>               # Unstage a file
git checkout -- <file>              # Discard local changes

⚔️ Merge Conflict
Edit the file manually
Remove <<<<<<<, =======, >>>>>>> markers
git add file
git commit
git push

📥 Clone a Repo
git clone <repo-url>                # Download repo to local
cd repo-name                        # Move into the repo

🧠 General Tips
Use code . to open in VS Code
Use git status often to check where you are
Always create a branch before working on new stuff
