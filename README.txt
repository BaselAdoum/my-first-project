# 🧭 Step 1: Navigate and Set Up Your Project Folder
pwd                          # Show current directory (where you are)
ls                           # List files and folders in the current directory
cd ~/Desktop                 # Move to your Desktop (or another location)
mkdir my-first-project       # Create a new folder for your project
cd my-first-project          # Enter the new folder

# 🧱 Step 2: Initialize a Git Repository
git init                     # Start a new Git repo — creates a hidden .git/ folder to track changes

# 📄 Step 3: Create a File
echo "Hello, World! This is my first file." > README.txt   # Create a README.txt file with sample text

# 🔍 Step 4: Check the Status
git status                   # See which files are untracked, modified, or staged

# ➕ Step 5: Add File(s) to the Staging Area
git add README.txt            # Stage one specific file
# or
git add .                     # Stage ALL changes in the current directory

# 🧾 Step 6: Check Status Again
git status                   # Confirm the file is now staged (ready to commit)

# 💾 Step 7: Commit the Change
git commit -m "Add initial README file"   # Save a snapshot with a message describing the change

# 🔁 Step 8: Repeat the Basic Workflow
git status                   # Check what's changed
git add .                    # Stage all changes
git commit -m "Describe your update"   # Commit with a clear message

# 🧠 Summary Mental Model:
# Working Directory → Staging Area → Repository
# (edit files)         (git add)       (git commit)
git log show you the history of changed 

echo "# my-first-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/BaselAdoum/my-first-project.git
git push -u origin main


git remote add origin https://github.com/BaselAdoum/my-first-project.git
git branch -M main
git push -u origin main

$ git checkout -b new-feature
testing push pull