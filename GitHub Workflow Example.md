# **GitHub Workflow (Example):**

## 1. Fork and Clone:
<pre><code>$ git clone https://github.com/your-username/repository.git
$ cd repository
</code></pre>

## 2. Create a Branch:
`$ git checkout -b new-feature`

## 3. Make Changes and Commit:
<pre><code>$ git add .
$ git commit -m "Added a new feature" 
</code></pre>

## 4. Push to GitHub:
` $ git push origin new-feature `

## 5. Create a Pull Request (PR):
* Go to GitHub.

* Navigate to your repository.

* Click Compare & pull request.

* Add details and submit.

## 6. Merge PR (if approved):
<pre><code>$ git checkout main
$ git pull origin main
$ git merge new-feature
</code></pre>
