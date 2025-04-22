# Git Workshop

## Git Commands Covered:

`git clone` - clones the repository onto your local machine

`git status` - displays the status of your worktree/workspace

`git add .` - stages all the files in the current worktree

`git commit -m "commit msg"` - commits the files that are currently staged with the commit msg specified

`git log` - logs the current commit history

`git checkout <branch>` - changes the current branch to the specified branch

`git checkout -b <branch-name>` - makes a new branch called `branch-name` and changes the current branch to the new branch

`git push` - pushes the current branch to the remote repository (think of it as uploading to the cloud)

`git push -u origin <branch-name>` - same as `git push` but you first make the remote branch that you want to upload to (you would need to do this for new branches)

`git pull` - pull changes from the remote repository to your local repository

### Notes
- make a new branch for every feature (don't reuse your branches)
- `git pull` before making a new branch so that you can have all the changes currently on the repository
