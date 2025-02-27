Initial Setup
# Set up global username and email
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Starting a Repository
# Initialize a new Git repository
git init

# Clone an existing repository
git clone <repository_url>

Basic Commands
# Check the status of the working directory
git status

# Add files to the staging area
git add <file>       # Add a specific file
git add .           # Add all files

git add -p          # Add file changes interactively

# Commit staged files with a message
git commit -m "Commit message"

Branching and Merging
# List all branches
git branch

# Create a new branch
git branch <branch_name>

# Switch to a branch
git checkout <branch_name>

# Create and switch to a new branch
git checkout -b <branch_name>

# Merge a branch into the current branch
git merge <branch_name>

Working with Remote Repositories
# Add a remote repository
git remote add origin <repository_url>

# Fetch changes from the remote repository
git fetch

# Pull the latest changes from the remote repository
git pull origin <branch_name>

# Push changes to the remote repository
git push origin <branch_name>

Undoing Changes
# Unstage a file (undo `git add`)
git reset <file>

# Reset to the last committed state
git reset --hard

# Restore a modified file to its last committed
