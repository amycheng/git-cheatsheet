Git Commands I always forget
============================
... because I do not use them often enough to have them memorized.

`git checkout [branch] [filename]`
- cherry pick a file from another branch

`git rebase -i HEAD~3`
- rebase from the last 3 commits and have the opportunity to clean-up commits

`git rebase -i origin/master`
- pull in master and place commits from your branch to the top of the master commits
- opportunity to clean up commits

`git reset [commit hash]`
- reset branch to commit
- DROPS COMMITS!

`git revert [commit hash]`
- adds another commit undoing changes
