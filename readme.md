## Committing:

`git add .`` OR `git add path/to/file` OR `git add *.png`

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

merge a branch into current branch

`git merge BranchNameToMergeFrom`


## Forking

Fork is where you get your own remote copy of the repository. There is a fork button in github, which will make a copy of the repo. After you make your changes in that repo, you can submit a pull request which will ask them to pull in the changes in your fork.
