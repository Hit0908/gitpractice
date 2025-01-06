# Git Commands for Development

## 1. Create and Initialize a Git Repository
mkdir git-for-devops  
cd git-for-devops/  
git init  

## 2. File Management and Basic Operations
ls                    # List files in the current directory  
clear                 # Clear the terminal screen  
pwd                   # Print the working directory  
vim hello.txt         # Open or create a file in vim editor  
chmod +x hello.txt    # Make the file executable  

## 3. Viewing and Checking Git Status
ls -l                 # List files in long format with permissions  
git status            # Check the status of files in the repository  

## 4. Configuring Git User
git config --global user.email "email"                            # Set email for Git  
git config --global user.name "Username"                          # Set username for Git  

## 5. Adding and Committing Files
git add hello.txt      # Add a specific file to the staging area  
git commit -m "first commit"   # Commit changes with a message  

## 6. Managing Git Staging Area
git add                # Add all changes to the staging area  
git rm --cached hello.txt  # Remove file from staging area, but keep it locally  
git restore hello.txt  # Restore the file from the latest commit  

## 7. Branch Management
git branch             # List all branches in the repository  
git checkout -b dev    # Create a new branch called 'dev' and switch to it  
git checkout master    # Switch back to the 'master' branch  

## 8. Viewing Commit History
git log                # View the commit history  

## 9. Miscellaneous Operations

git commit -m "adding" # Commit changes with a message  
git status            # Check the current status of the repository  

## 10. Creating and Adding Files
touch hi.txt          # Create a new file called 'hi.txt'  
git add hi.txt        # Add the new file to the staging area  
git commit -m "added a new file in dev"  # Commit the new file  
