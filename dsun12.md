Differences among github fork, git clone, and git branch:
1.Fork: Copy a repo to our own account, where we could make changes without affecting the original project. After we make the changes, we can merge the version we have to the original project by pulling a request.
2.Clone: Copy the files in repos to our own computer. Then we can make changes locally, and use git to synchronize our work with the remote repo.
3.Branch: A new pointer that points to the current version of project. We don't really move onto that branch until we "checkout" to that branch. When we make changes through this new pointer, we are starting a new path. And we can still "checkout" to the old pointer(say master branch) and make other changes, which also will start a different path. 
