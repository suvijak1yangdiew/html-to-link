# Static website (GitHub Pages)

This folder contains a simple static website that will be deployed using GitHub Pages.

## Getting started

1. Make sure the main HTML file is named `index.html` and is placed directly in this folder.
2. Place any supporting assets (CSS, JS, images) in subfolders such as `css/`, `js/`, `images/`, etc.

## Initialize git repository (run these in PowerShell)

```powershell
cd "c:\New folder"

# If you haven't set global git name/email on this machine yet:
git config --global user.name "YOUR_NAME"
git config --global user.email "YOUR_EMAIL@example.com"

# Initialize the repository
git init

# (Optional but recommended) Check current status
git status

# Add all project files to the first commit
git add .

# Create initial commit
git commit -m "Initial commit for static website"
```

After this, you can add a GitHub remote and push, following the rest of your plan.

