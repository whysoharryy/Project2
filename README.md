# New Project
Created from Delta-Demo local system

# Basic Commands to add in github repo
First create repo in github and get HTTPS url
git add .
git commit -m "Msg"
git remote add origin "https://github.com/whysoharryy/Project2.git"
git push origin main

# Branch Commands
git branch (To check branch Name)
git checkout -b <branch_name>  (To create new branch from main)
git checkout <branch_name> (To navigate to other branch)
git branch -d <branch_name>

# merge
git diff <branch_name>  (To comapare commits,branches etc)
git merge <branch_name>    OR CREATE PULL REQUEST IN GITHUB

Accept request in github
Still app.js wont be present in main branch
# git pull origin main
uploads remote repo to local repo

# Merge Conflicts 
When git is unable to resolve diff between two branches

# Fixing mistakes
Mistake in latest Commit : git reset HEAD~1  
use git log : to get all commit history and hash value 
# git reset abe0017482148c2063526a526dbc7a68529bf91e 

# Forking
Fork is Copying other repo and contributing changes by adding pull request
Fork nodejs , add some change and create pull request







