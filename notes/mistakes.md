The common safe mechanisms are:


git restore: restores files in the working directory or unstages changes without affecting commit history.


git revert: creates a new commit that undoes an earlier commit, which is the safest way to undo something already 
shared.


git commit --amend: modifies the most recent commit, usually before it has been pushed.


git reset: can move commits around, but should be used carefully because some forms rewrite history.