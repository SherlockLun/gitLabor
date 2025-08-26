# gitLabor
#

Instruction um mit wip zu arbeiten (push) und später git commit history aufzuräumen


git commit -m "wip1"
git push

git commit -m "wip2"
git push

git reset --soft HEAD~2

git commit -m "Aenderungen, die vorher in wip1 und wip2 waren."

git push -f origin dev


If the WIP is within several commits before and after the steps are:
1) git rebase -i "commit before wip"
2) Edit Commit Message Name/Description. In best case the same as after WIP.
3) Push Force? Squash?
