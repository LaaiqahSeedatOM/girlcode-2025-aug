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

