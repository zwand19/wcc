# Wands Coding Class

# Git commands

### Pull a repository

`git clone https://github.com/zwand19/wcc`

Will create a folder "wcc" at the current location in terminal and copy all of the code from the repository into the folder

### Check status

`git status`

Will list all files that are out of sync with the server, and will tell you if you are up to date with the current code in the repository

### Get the latest code

`git pull --rebase`

This will pull all of the latest files from the repository. If you have changed any files that you are pulling down from the repository, you may need to resolve merge conflicts.

### Add your code

`git add .`
`git commit -m "add a commit message here"`
`git pull --rebase`
`git push`

The first step tells git that you want to push all of the changes you have made. The '.' character means everything from the current directory. if you only wanted to push a specific file, you could run `git add path\to\file.html` and commit only that. This is referred to as "staging files".

The second step packages all of your "staged files" (from git add) into a changeset and tags it with a message.

The third step ensures you have the latest code from the repository before trying to push any new changes.

The fourth step will push your commit to the repository, and then anyone else could pull it down.