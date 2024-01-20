---
title: "How-to-contribute-to-someone's-repository-on-GitHub"
date: 2024-01-17
---

Here's a step-by-step guide on how to contribute to someone's repository on GitHub.

**Step 1: Fork the Repository**
Go to the GitHub repository you want to contribute to.
Click the "Fork" button in the upper right corner of the repository page.
This will create a copy of the repository in your GitHub account.

**Step 2: Clone the Forked Repository**
Open your terminal (or Git Bash on Windows).
To clone the repository using HTTPS, copy the link under "HTTPS".
To clone the repository using an SSH key, include a certificate issued by your organization's SSH certificate authority, and copy the link under "SSH".
To clone a repository using GitHub CLI, click GitHub "CLI", and copy the link under it. 
Open the terminal, write `git clone`, and paste your link.

For example: 
```
git clone https://github.com/user/repository.git
```

**Step 3: Create a Branch**
Change into the repository's directory:
```
cd [repository-name]
```
Create a new branch for your changes. Choose a descriptive branch name related to your contribution:
```
git checkout -b feature/my-contribution
```
**Step 4: Make Changes**
Make the necessary changes to the code or documentation in your local branch using your preferred text editor or IDE.

**Step 5: Commit Changes**
Stage the changes:
```
git add .
```
Commit the changes with a descriptive message
```
git commit -m "Add feature/my-contribution"
```

**Step 6: Push Changes to Your Fork**
Push the changes to your forked repository on GitHub:
```
git push origin feature/my-contribution
```

**Step 7: Create a Pull Request (PR)**
Visit your forked repository on GitHub.
Click the "New Pull Request" button.
Ensure the base repository and branch are set to the original repository and the branch you want to merge into.
Write a clear and concise title and description for your pull request.
Click "Create Pull Request" to submit your changes for review.

**Step 9: Merge**
Once the changes are approved, the repository owner or maintainer can merge your pull request.

Congratulations! You have successfully contributed to someone's repository on GitHub. If you face any issues while following these steps, feel free to raise an issue and add that error under that given step. Happy contributing!
