## git revert

`git revert` will undo changes up to the state before the specified commit ID. For example, reverting to the second commit ID will undo changes and leave the state of the file as the state of the commit that comes before the second commit – the first commit.

## When to use?

`git revert` is a good option for reverting changes pushed to a remote repository. Since this command creates a new commit, you can safely get rid of your mistakes without rearranging the commit history for everyone else.

# Summary

The git revert command is a forward-moving undo operation that offers a safe method of undoing changes. Instead of deleting or orphaning commits in the commit history, a revert will create a new commit that inverses the changes specified.