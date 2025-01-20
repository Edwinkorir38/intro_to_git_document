Introduction to Git

Git is a distributed version control system that allows developers to track changes in their code, collaborate with others, and manage project history efficiently. This guide introduces the basics of Git to help you get started.

Table of Contents

What is Git?

Installing Git

Basic Git Commands

Working with Branches

Collaborating with Others

What is Git?

Git is an open-source tool created by Linus Torvalds in 2005. It helps developers:

Track changes in their codebase.

Experiment with new features using branches.

Collaborate with a team efficiently.

Installing Git

To install Git, follow these steps:

Windows:

Download Git from git-scm.com.

Run the installer and follow the setup instructions.

macOS:

Open Terminal and run:

brew install git

Verify installation with:

git --version

Linux:

Update your package index:

sudo apt update

Install Git:

sudo apt install git

Verify installation:

git --version

Basic Git Commands

Here are some essential commands to get you started:

Initialize a repository:

git init

Clone a repository:

git clone <repository_url>

Check status:

git status

Add changes to staging area:

git add <file_name>

Add all files:

git add .

Commit changes:

git commit -m "Commit message"

View commit history:

git log

Working with Branches

Branches allow you to work on new features without affecting the main codebase.

Create a new branch:

git branch <branch_name>

Switch to a branch:

git checkout <branch_name>

Create and switch to a branch:

git checkout -b <branch_name>

Merge a branch into the main branch:

git checkout main
git merge <branch_name>

Delete a branch:

git branch -d <branch_name>

Collaborating with Others

Git makes collaboration seamless when paired with platforms like GitHub, GitLab, or Bitbucket.

Push changes to a remote repository:

git push origin <branch_name>

Pull changes from a remote repository:

git pull origin <branch_name>

Fetch changes without merging:

git fetch

Additional Resources

Git Official Documentation

Pro Git Book

GitHub Learning Lab
