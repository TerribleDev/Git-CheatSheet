## Committing:

`git add .` OR `git add path/to/file` OR `git add *.png`

`git commit -m "Your Message"`

`git push origin YourBranchName` (gh-pages)



## Branching:

List branches: `git branch`

Create branch with the current branch `git checkout -b BranchName`


delete local branch `git branch -D BranchName`

push delete branch `git push origin :branchName`

## Cloning

To put cloning in lamens term you download the remote repository locally

`git clone https://github.com/tparnell8/Git-CheatSheet.git`


## Merging

merge/rebase a branch into current branch by doing the following


`git fetch --all` (fetch all changes from remote server)
`git merge/rebase origin/BranchNameToMergeFrom` (merge in the changes from the remote branch)

### Rebase or merge

***Rebase*** rewinds your commits back until you are at the same commit as the other branch. Then applies their changes, and then your changes. this is good if you want all of your commits at the tip of the branch, but may cause excessive merge conflicts.

***Merge*** simply merges the target branch into your branch.



## Forking

Fork is where you get your own remote copy of the repository. There is a fork button in github, which will make a copy of the repo. After you make your changes in that repo, you can submit a pull request which will ask them to pull in the changes in your fork.

## Rewind commits
To move back to a previous commit, but keep the changes as unstaged do `git reset HEAD~1`

To move back to the previous commit and throw away the changes do `git reset HEAD~1 --hard`
