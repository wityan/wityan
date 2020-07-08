# Git Rebase

1. Checkout the Target Branch  `git checkout TARGET_BRANCH`
2. Pull this Branch `git pull`
3. Checkout the Branch you want to Rebase `git checkout WORKING_BRANCH`
4. Initialize Rebase `git rebase -i origin/TARGET_BRANCH`
5. Configure the rebase
6. Rebase until you see this message `Successfully rebased and updated refs/heads/WORKING_BRANCH`
7. Now you have to face push to your branch `git push -f`

*Documentation* [Git - Rebasing](https://git-scm.com/book/de/v2/Git-Branching-Rebasing)

## Tips & Trick
* Make a Backup of your Branch before rebasing
* If you have strange errors while rebasing, abort it and delete both the TARGET and the WORKING branch
