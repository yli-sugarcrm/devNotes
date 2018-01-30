# Git and GitHub 

## [Github Markdown](https://guides.github.com/features/mastering-markdown)

## Checkout Pull Request change locally
If you want to check change on a pull request, but can't or don't want to fetch the change from a remote branch (for whatever reason). You can directly pull the change from the upstream branch with ID of the PR, check out [Github Instruction](https://help.github.com/articles/checking-out-pull-requests-locally/)
_**Note:**_ Make sure you use a new branch, or the change may be reject.

## Link to a particular line of code of Github repo
If you want to link Line #123 on a file, just add '/#L<123>' at the end of the URL to the file.


## Show difference on git
"git diff" - for save but unstaged change
"git diff --staged" - for staged change
"git diff *branch_Name* *remote/branch_name*" - for difference between a local branch and remote branch


## Git Stash
"git stash" to remove uncommit change
"git stack pop" to restore stash change