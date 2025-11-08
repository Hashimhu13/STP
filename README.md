# STP Test

This is a small static HTML project (an Arabic/English practice test) ready to be deployed to GitHub Pages.

How to deploy (quick):

1. Initialize git, commit, and push:

   - If you have the GitHub CLI installed and authenticated (recommended):
     gh repo create stp-test --public --source=. --remote=origin --push

   - Or, manually create a GitHub repo and add remote:
     git init -b main
     git add .
     git commit -m "Initial commit"
     git remote add origin https://github.com/<your-username>/stp-test.git
     git push -u origin main

2. GitHub Pages will serve `index.html` from the `main` branch root. The site URL will be:

   https://<your-username>.github.io/stp-test

If you want me to attempt the `git` and `gh` steps from here, tell me and confirm the repository name (default: `stp-test`) or provide the remote URL and I will push.
