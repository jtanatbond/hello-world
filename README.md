# hello-world
This is a place where for storing ideas, resources, or even share and discuss things with others.

Hi Humans,
It is a pleasure to be here today.

Basic git commands:
https://guides.github.com/introduction/git-handbook/

Cheat Sheet:
https://ndpsoftware.com/git-cheatsheet.html#loc=remote_repo;

Example: Contribute to an existing repository

# download a repository on GitHub.com to our machine
git clone https://github.com/me/repo.git

# change into the `repo` directory
cd repo

# create a new branch to store any new changes
git branch my-branch

# switch to that branch (line of development)
git checkout my-branch

# make changes, for example, edit `file1.md` and `file2.md` using the text editor

# stage the changed files
git add file1.md file2.md

# take a snapshot of the staging area (anything that's been added)
git commit -m "my snapshot"

# push changes to github
git push --set-upstream origin my-branch
