# Git and GitHub Commands Guide

This guide includes essential Git and GitHub commands that are commonly used in version control and collaborative development.

## 1. Install Git
Download and install Git. During installation, accept the default settings unless you have specific preferences.

## 2. Configure Git (First Time Setup)

### Set up Git
Open your terminal or command prompt and configure your user information for Git using the following commands:
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

## 3. Create a Local Repository
Navigate to the directory where your project is located and initialize it as a Git repository (if not already done):
```bash
git init
```

## 4. Add Files to the Repository
Add your project files to the repository. You can add individual files using:
```bash
git add filename
```

Or add all files in the directory with:
```bash
git add .
```

## 5. Commit the Files
Commit your added files to your local repository:
```bash
git commit -m "Initial commit"
```
Replace "Initial commit" with a meaningful message describing what you are committing.

## 6. Create a Repository on GitHub
(i)   Go to GitHub and sign in. <br>
(ii)  Click the "+" icon in the top right corner and select "New repository." <br>
(iii) Name your repository, add a description (optional), and choose whether it's public or private.<br>
(iv)  Click "Create repository."

## 7. Link Your Local Repository to GitHub
Copy the URL of your newly created GitHub repository. Then, link your local repository to GitHub with:
```bash
git remote add origin <REPOSITORY_URL>
```
Replace <REPOSITORY_URL> with the URL of your GitHub repository.

## 8. Push Your Code to GitHub
Finally, push your code to GitHub with:
```bash
git push -u origin main
```

## 9. Subsequent Pushes
For any subsequent pushes after the initial push, you can simply use:
```bash
git push
```

These steps cover the basics of pushing code from a local repository to a GitHub repository.
