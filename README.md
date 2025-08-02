# girlcode-2025-aug

## Basic commands

git clone <URL> -- Clones the server to your remote
git status -- Checks what files are in your working directory and its state (i.e. committed, stashes etc)
git add <file> -- Adds a file
git commit -- Adds all files to local repo
git push -- Adds all files to SERVER repo
git pull -- Pulls all changes from Server repo

added some changes here 


## Merge commands 

    • git config merge.tool vimdiff
Set your preferred editor as the default merge tool.
    • git mergetool
Open your editor of choice to resolve conflicts in a more user‑friendly way.
    • git checkout --ours filename.php
Keep the changes from your branch for the specified file during a merge, while discarding the incoming changes.
    • git checkout --theirs filename.php
Keep the incoming changes for the file, and discard the changes in your local branch.
    • git merge --abort
Abort the merging process using this command.
    • git config merge.conflictstyle diff3
Set the diff3 merge style, which is much more intuitive than the default one.

## Branch commands 

    • git branch
List all the branches in a repository.
    • git branch <branch name>
Create a new branch with the specified name.
    • git checkout <branch name>
Switch to a different branch.
    • git merge <branch name>
Merge the current branch with the specified branch.
    • git branch -d <branch name>
Delete the specified branch.
    • git push origin --delete <branch name>
Delete a remote branch.
    • git checkout -b <branch name> origin/<branch name>
Clone a remote branch and switch to it.
    • git merge <source branch> <target branch>
Merge the two given branches.
    • git branch -m <old name> <new name>
Rename a branch.
    • git rebase <branch name>
Apply all the commits of the current branch ahead of the specified branch.
