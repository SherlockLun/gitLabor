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

