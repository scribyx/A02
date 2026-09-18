**This is for HW A02**

# A02: Git + Github Workflow Tutorial

## Step-by-Step Directions

1. **Installation** : Download and install GIT and Visual Studio Code on your computer.
2. **Configure Identity**: Open Git Bash in VS Code and set your global identity:
   bash
   git config --global user.name "username"
   git config --global user.email "your-email@example.com"

3. **Clone**: Create a local folder and convert it into a local Repository using git init, or clone an existing project from Github using git clone (your url)
4. **Remote**: Link your local repository to a Remote repository on GitHub
    git remote add origin (repository url)
5. **Switch Branches**: Work on separate features by creating a new Branch
    git checkout -b feature-branch
6. **Stage Changes**: Edit your project files in VS Code
    git add .
7. **Commit Changes**: Save your staged files by creating a Commit
    git commit -m "tutorial steps"
8. **Pull**: Download updates and combine them into your local branch using Pull:
    git pull origin main
9. **Merge Conflict**: If changes overlap, resolve any Merge Conflict
10. **Push Updates**: Send your local commits to the remote repository using Push
    git push -u origin main

## Glossary

1. **Branch**: independent line of development which is isolated from the main codebase
2. **Clone**: local copy of a remote repository downloaded onto your computer
3. **Commit**: A saved snapshot of changes made to files in your repository
4. **Fetch**: Downloads new updates from a remote repository without automatically merging them with local
5. **GIT**: version control system used to track changes in source code
6. **Github**: A cloud-based hosting platform for managing Git repositories
7. **Merge**: process of combining changes from one branch into another
8. **Merge Conflict**: issue that occurs when Git can't automatically combine two conflicting sets of changes
9. **Push**: command used to upload local repository commits to a remote repository
10. **Pull**: Downloads updates from a remote repository and immediately merges them into your local branch
11. **Remote**: A common repository hosted on a server shared by collaborators
12. **Repository**: digital folder that contains project files and the entire history of changes, tracked by Git

## References
Git Documentation: https://git-scm.com/docs
GitHub Guides: https://docs.github.com
Visual Studio Code Documentation: https://code.visualstudio.com/docs