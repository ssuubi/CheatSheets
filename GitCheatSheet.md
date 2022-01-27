# Git Cheatsheet
## Open new branch
1.) Get newest version from master `git pull`

2.) Create Branch `git checkout -b <feature/id-short-name>`

3.) Show active Branch `git branch`

4.) start working :)

5.) `commit` code to local branch

6.) push to new remote branch (`git push --set-upstream origin <branch_name>` -> ONLY for first push, then just `push`)

7.) At a certain time: Merge Request via GitLab

--- optional ---

8.) After accepted merge request: Delete Branch, e.g. (`git branch -d <branch_name>`)f


## Fetch branch

git fetch
git checkout <test/branch>
git branch (shows which branch is active at the moment)
git checkout <master> (back to the master branch)


## Discard changes

git fetch origin (look for changes in master branch)
git reset --hard origin/master (assumed that the remote branch's name is "origin" and the branch is "master")


## Go back to commit
git checkout <commit_id>
git checkout -b <new-branch-name> (open new branch from current commit)
