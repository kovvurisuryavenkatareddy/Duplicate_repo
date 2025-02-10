# Duplicate_repo

This repository is initialized and pushed to GitHub using Git. Below are the steps followed:

## Git Setup and Initialization

```sh
# Set your Git username and email (replace with your details)
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

# Initialize a new Git repository
git init

# Add all files to the staging area
git add .

# Commit the changes with a message
git commit -m "first commit"

# Rename the default branch to main
git branch -M main

# Add a remote repository
git remote add origin https://github.com/kovvurisuryavenkatareddy/Duplicate_repo.git

# Push the changes to the remote repository
git push -u origin main
