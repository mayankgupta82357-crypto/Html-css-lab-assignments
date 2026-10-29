# Html-css-lab-assignments
b.tech CSE HTML and CSS lab Assignment 


Lab 2 - Pushing and Cloning a Repository

These are generic local commands. If your teacher requires GitHub, create an empty repository on GitHub and use the remote URL shown by GitHub.

Local remote and clone example

Run from the parent directory of your project:

git init --bare html-lab-remote.git

git -C html-lab remote add origin../html-lab-remote.git

git -C html-lab push -u origin main

git clone html-lab-remote.git html-lab-clone

If your local branch is named master, replace main with master, or rename it with:

git -C html-lab branch -M main

GitHub remote example

git remote add origin YOUR_REPOSITORY_URL

git branch -M main

git push-u origin main

git clone YOUR_REPOSITORY_URL

Run only the commands that match your setup. Capture your own screenshots of push, clone, and the cloned folder