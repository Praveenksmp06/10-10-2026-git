# 10-10-2026-git

- `clone` : one time download
- `status` : to check the modifications
- `diff` : to view the differences
- `add` : to store the changes in the stage, then we will be able to commit
- `commit` : commit -m "MESSAGE" : message for the files in staging area
- main -> (changes) -> stage -> commit
-  origin = github(remote)
- `push` : pc to github
- `pull` : github to pc
- push where(origin) what (main)
- branch to main
- `log` - to view the commit, push , pull (git log --oneline --graph --all)
- `switch -c b1` - create and switch to the new branch -  git switch main, git switch b1
- `HEAD` : tells you where you are.
- `prune` : --prune (or -p): Removes remote-tracking branches (like origin/some-old-branch) from your local system if they were deleted on GitHub. This keeps your remote branch list clean.
- `git branch -d b1` : Deletes the local branch named b1.
- FORK -> CLONE -> PUSH/PULL -> PULL REQUEST -> PULL(from upstream) - PUSH(to main)
- `git remote -v` - repo remote connection
- `git remote add upstream "path"` -     git pull upstream main
- Version control with git - https://swcarpentry.github.io/git-novice/
- R packages book - https://r-pkgs.org/
- R studio only mode link(no terminal) - https://github.com/tidyverse/tidy-dev-day/blob/main/README.md
-New line by jennifer

