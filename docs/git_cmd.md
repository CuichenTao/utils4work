# Command line instructions

> Git global setup

- git config --global user.name "Taocuichen"
- git config --global user.email "taocuichen@wantdata.cn"


> Create a new repository

- git clone git@git.jndroid.com:taocuichen/Wash-test.git
- cd Wash-test
- touch README.md
- git add README.md
- git commit -m "add README"
- git push -u origin master


> Existing folder or Git repository

- cd existing_folder
- git init
- git remote add origin git@git.jndroid.com:Corpus/Wash.git
- git add .
- git commit
- git push -u origin master


> Command to add new branch

- git checkout -b deploy/release
- git push --set-upstream origin deploy/release

> delete branch

- git branch -D deploy/release    # force to delete local branch
- git branch -r -d origin/deploy/release    # delete remote branch
