# Initialize a new Git repository
git init

# Clone an existing repository
git clone <repository-url>

# Check repository status
git status

# List branches
git branch

# Create a new branch
git branch <branch-name>

# Switch to a branch
git checkout <branch-name>

# Create and switch to a new branch
git checkout -b <branch-name>

# Using the newer switch command
git switch <branch-name>
git switch -c <branch-name>

# Add a specific file
git add <file-name>

# Add all changes
git add .

# Commit staged changes
git commit -m "Commit message"

# Stage and commit tracked files
git commit -am "Commit message"

git remote -v

# Add a remote
git remote add origin <repository-url>

# Push changes
git push origin <branch-name>

# Push and set upstream
git push -u origin <branch-name>

# Pull latest changes
git pull origin <branch-name>

# Fetch changes without merging
git fetch

