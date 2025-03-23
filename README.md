# **Introduction to Git:**

Git is a distributed version control system that helps developers track changes in their codebase, collaborate efficiently, and maintain different versions of their projects.

## **Why Git?**

* Version Control: Track changes and revert to previous versions.

* Collaboration: Work with multiple developers on the same codebase.

* Branching & Merging: Develop features separately without affecting the main code.

* Backup & Recovery: Prevent loss of work by storing it remotely (e.g., GitHub, GitLab).

## **Setting Up Git:**
Download and install Git from [git-scm.com](https://). Verify installation:

` $ git --version `

### **Configuring Git:**
<pre><code>$ git config --global user.name "Your Name"
$ git config --global user.email "your.email@example.com"
$ git config --global core.editor "code --wait"
</code></pre>

# Git Basic:
### Initializing a Repository:
`$ git init`

This creates a .git directory, making the folder a Git repository.

### Cloning a Repository:
` $ git clone <repository_url> `
### Staging and Committing Changes:
<pre><code>$ git add <file>        # Add a specific file
$ git add .             # Add all changes
$ git commit -m "Commit message"
</code></pre>
### Checking Status:
`$ git status`
### Viewing Commit History:
`$ git log --oneline --graph --decorate --all`

# Branching and Merging:
### Creating and Switching Branches:
<pre><code>$ git branch feature-branch  # Create a new branch
$ git checkout feature-branch  # Switch to the branch
$ git switch feature-branch  # Alternative to checkout
</code></pre>
## Merging Branches:
<pre><code>$ git checkout main
$ git merge feature-branch
</code></pre>
# Resolving Merge Conflicts:

1: Open conflicting files.

2: Edit the file to keep necessary changes.

3: Stage the resolved file: git add <file>

4: Commit the merge: git commit -m "Resolved merge conflict"

# Working with Remote Repositories:
### Adding a Remote Repository:
`$ git remote add origin <repository_url>`
### Pushing Changes:
`$ git push origin main  # Push changes to the main branch`
### Pulling Changes:
`$ git pull origin main`
### Fetching Updates (without merging):
`$ git fetch origin`

