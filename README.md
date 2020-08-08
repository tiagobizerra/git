# git

### GIT ###

# view files changes and diff for a commit
git log and get the commit_id
git show commit_id

#remove remote branch reference
git branch -d -r origin/coolbranch

# revert 1 commit:
git reset --hard HEAD~1

## undo all changes made in local branch. 
git reset --hard HEAD^

## delete branch
# local
git branch -D $branch
# remote
git push origin --delete $branch
