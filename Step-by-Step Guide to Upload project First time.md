# Step-by-Step Guide to Upload Your Project to GitHub for the First Time
## 1. Create a GitHub Repository:
1) Go to GitHub.

2) Click the "+" icon in the top-right corner and select "New repository".

3) Enter a Repository Name (e.g., `git-guide`).

4) (Optional) Add a Description.

5) Choose Public or Private.

6) DO NOT check “Initialize this repository with a README” (since we will upload an existing project).

7) Click "Create repository".

## 2. Navigate to Your Project Folder:
Open VS Code, then open the terminal (`Ctrl + ~ in VS Code`) and navigate to your project folder:
<pre>
cd path/to/your/What-is-Git-folder
</pre>

## 3. Initialize Git in the Folder:
<pre> git init</pre>
This creates a `.git` folder inside your project, making it a Git repository.

## 4. Add a Remote Repository:
Copy the repository URL from GitHub and run:
<pre><code>git remote add origin https://github.com/your-username/git-guide.git
</code></pre>
Check if the remote was added correctly:
<pre>git remote -v
</pre>

## 5. Stage and Commit Your Files:
<pre><code>git add .
git commit -m "Initial commit - Added Git guide"
</code></pre>

## 6. Push to GitHub:
First, set the default branch (GitHub uses `main` by default now):
<pre>git branch -M main
</pre>
Now push your code:
<pre>git push -u origin main
</pre>

## 7. Verify on GitHub:
Go to your repository on GitHub, and you should see all your files uploaded!

## 8. (Optional) Create a README:
If you didn’t add a README.md, you can create one:
<pre><code>echo "# Git Guide" > README.md
git add README.md
git commit -m "Added README"
git push origin main
</code></pre>