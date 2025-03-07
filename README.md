# Initialize git in your local directory (if not already done)
git init

# Add the GitHub repository as your remote origin
git remote add origin https://github.com/Dandyoung/catchup.git

# Pull the existing content from the repository (if any)
git pull origin main  # or 'master' depending on the default branch name

# If you have local changes you want to push
git add .
git commit -m "Initial commit" 
git push -u origin main  # or 'master' depending on the default branch name