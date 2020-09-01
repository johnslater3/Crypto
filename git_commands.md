### GIT COMMANDS

Important: In w205, please never merge your assignment branch to the master branch.

Using the git command line: clone down the repo, leave the master branch untouched, create an assignment branch, and move to that branch:
•	Clone down your repo 'git clone <https url for your repo>'
•	Change directory into the repo 'cd <repo name>'
•	Create an assignment branch 'git branch <branch name>'
•	Checkout the assignment branch 'git checkout <branch name>'

The previous steps only need to be done once. Once you your clone is on the assignment branch it will remain on that branch unless you checkout another branch.

The project workflow follows this pattern, which may be repeated as many times as needed. In fact it's best to do this frequently as it saves your work into GitHub in case your virtual machine becomes corrupt:
•	Make changes to existing files as needed.
•	Add new files as needed
•	Stage modified files 'git add <filename>'
•	Commit staged files 'git commit -m "<meaningful comment about your changes>"'
•	Push the commit on your assignment branch from your clone to GitHub 'git push origin <branch name>'

