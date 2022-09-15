## Git

### Which of these terms best describes Git?

- [ ] Distributed Version Control System
- [ ] Issue Tracking System
- [ ] Integrated Development Environment
- [ ] Web-Based Repository Hosting Service

### What command lets you create a connection between a local and remote repository?

- [ ] git remote add new
- [ ] git remote add origin
- [ ] git remote new origin
- [ ] git remote origin

### Describe what these Git commands do to the commit history:

```bash
git reset --hard HEAD~5
git merge --squash HEAD@{1}
```

- [ ] They reset the HEAD to the fifth commit in the repo, then merge to the master branch.
- [ ] The current branch's HEAD is reset back five commits, then prior commits are squashed into a single commit.
- [ ] They delete the last five commits.
- [ ] They merge the last five commits into a new branch.

### Your current project has several branches; master, beta, and push-notifications. You've just finished the notification feature in the push-notification branch, and you want to commit it to beta branch. How can you accomplish this?

- [ ] Checkout the _push-notifications_ branch and run `git merge beta`
- [ ] Checkout the _master_ branch and run `git merge beta -> push-notification`
- [ ] Delete the _push-notification_ branch and it will be committed to the _master_ branch automatically
- [ ] Checkout the _beta_ branch and run `git merge push-notification`

### Which of the following is true you when you use the following command?

`git add -A`

- [ ] All new and updated files are staged
- [ ] Files are staged in alphabetical order.
- [ ] All new files are staged
- [ ] Only updated files are staged

### Looking at the following commands, describe what is happening.

```bash
git checkout feature-user-location
git cherry-pick kj2342134sdf090093f0sdgasdf99sdfo992mmmf9921231
```

- [ ] The commit is being tagged for release on the _feature-user-location_ branch
- [ ] A commit is being copied from its original branch over to the _feature-user-location_ branch
- [ ] The commit is being cherry picked as the new HEAD of the commit history
- [ ] A commit is being copied from the _feature-user-location_ branch to the master branch
- [ ] The branch is switched to the _feature-user-location_ branch, and the specified commit is applied to the branch.

### What does the following command do to the git repository?

`git reset --soft HEAD^`

- [ ] It deletes all previous commits and reset the repository history back to its initial state.
- [ ] It resets the working branch to the first commit.
- [ ] It keeps the HEAD at the current commit, but clears all previous commits.
- [ ] It sets HEAD to the previous commit and leaves changes from the undone commit in the stage/index.

### Why would the following command be used?

`git rebase -i HEAD~10`

- [ ] To run a comparative search of the last 10 commits for differences
- [ ] To list the last 10 commits and modify them with either the squash or fixup command
- [ ] To delete the last 10 commits and reset the HEAD
- [ ] In order to locally cache the last 10 commits

### Why would you use a pre-receive hook in your remote repository?

- [ ] You wouldn't, you would use it in the local repository
- [ ] To execute a script when a remote receives a push that is triggered before any refs are updated
- [ ] To fire a script after updates are made to the remote repository
- [ ] To debug all commit tags and release versions

### How could you squash multiple commits together without using git merge --squash?

- [ ] Caching
- [ ] You can't. `git merge --squash` is the only git command for that operation.
- [ ] Rebasing
- [ ] Reflogging

### How can you display a list of files added or modified in a specific commit?

- [ ] Find the commit in the remote repository, as that's the only place that kind of information is stored.
- [ ] Use the `diff-tree` command with the commit hash.
- [ ] Run `git commit --info` with the commit hash.
- [ ] Access the commit stash data with `git stash`.

### After you make changes to a local repository, you run the following command. What will this do?

`git commit -a -m "Refactor code base"`

- [ ] Nothing, you can't use multiple options in the same command
- [ ] Adds all new files to the staging area
- [ ] Commits all new files with a message
- [ ] Adds all modified files to the staging area, then commits them with a message

### What commands would you use to force an overwrite of your local files with the master branch?

- [ ] ⠀
  ```bash
  git pull --all
  git reset --hard origin/master
  ```
- [ ] ⠀
  ```bash
  git pull -u origin master
  git reset --hard master
  ```
- [ ] ⠀
  ```bash
  git pull origin master
  git reset --hard origin/myCurrentBranch
  ```
- [ ] ⠀

  ```bash
  git fetch --all
  git reset --hard origin/master
  ```

### In a situation where you have several commits for a single task, what is the most efficient way to restructure your commit history?

- [ ] Cherry pick the related commits to another branch.
- [ ] Delete the task commits and recommit with a new message.
- [ ] Squash the related commits together into a single coherent commit.
- [ ] Stash the related commits under a new hash.

### What command would let you modify your previous commit?

- [ ] --fix
- [ ] --quickfix
- [ ] --modify
- [ ] --amend

### After you've successfully merged two branches and committed the changes, what is the next step in keeping your git structure organized?

- [ ] Use the `git reset --soft HEAD` to roll back one commit.
- [ ] Run `git branch -d <branch name>` to delete the merged branch.
- [ ] Use `git clear-all` to clean up any hanging files.
- [ ] Run `git rebase` to move the current commit to its original location.

### While modifying a file, you're unexpectedly assigned an urgent bug fix on another branch. How can you temporarily save your local work without committing?

- [ ] This is not possible, as you cannot save locally without committing.
- [ ] Run `git hold` to save a local copy of what you're doing to return to later.
- [ ] Save your work with `git local-cache`.
- [ ] Use `git stash` to save your work and come back later and reapply the stashed commit.

### What command would you use to create a new git repository?

- [ ] git add
- [ ] git start
- [ ] git new
- [ ] git init

### After staging a series of changes to the index, which command could you use to review them prior to a commit?

- [ ] git diff --cached
- [ ] git diff
- [ ] git diff --HEAD
- [ ] git status -v -v

### What command creates a new branch from the currently checked-out branch?

- [ ] `git -b checkout <nameOfBranch>`
- [ ] `git branch`
- [ ] `git checkout <nameOfBranch>`
- [ ] `git checkout -b <nameOfBranch>`

### After mistakenly staging a file named myFile to the index, how would you remove it from the index to exclude it from your next commit?

- [ ] Use git reset HEAD^.
- [ ] Use git reset myFile.txt.
- [ ] Use git -rm myFile.txt.
- [ ] Use git reset.

### What happens if you run this command from your master branch?

```bash
git checkout -b beta-test
```

- [ ] The beta-test branch will be checked out of the current commit.
- [ ] The beta-test branch will be checked out and deleted.
- [ ] A new branch called beta-test will be created and switched to.
- [ ] The beta-test branch will be merged with the master branch.

### What conflicts can occur when forcing a push after rebasing?

- [ ] The remote master branch could have existing changes overwritten.
- [ ] The origin URL will be reset to its default value.
- [ ] The current HEAD will be deleted and can't be reinstated.
- [ ] Nothing, it's common practice to force a push after rebasing.

### How does this command alter the currently checked-out branch?

`git reset --soft HEAD^`

- [ ] It resets the working branch to the first commit.
- [ ] It sets HEAD to previous commit and leaves changes from the undone commit in the stage/index.
- [ ] It deletes all previous commits and resets the repository history back to its initial state.
- [ ] It keeps the HEAD at the current commit, but clears all previous commits.

### What is the difference between a soft reset (`git reset --soft`) and a hard reset (`git reset –hard`) ?

- [ ] A soft reset only changes the commit that HEAD points to, while a hard reset resets the index and working tree to match the specified commit, discarding any changes.
- [ ] A soft reset caches the old HEAD pointer, while a hard reset deletes it entirely.
- [ ] A hard reset changes only where the HEAD is pointing, while a soft reset changes the HEAD and index.
- [ ] A hard reset caches the old HEAD pointer, while a soft reset deletes it entirely.

### How would you delete a remote branch in your repository?

- [ ] Use `git --delete <branch_name>`.
- [ ] Use `git push <remote_name> --d <branch_name>`.
- [ ] Use `git push <remote_name> --D`.
- [ ] Use `git push <remote_name> --delete <branch_name>`.

### What practice can help reduce the chances of encountering a merge conflict?

- [ ] Provide detailed commit messages that describe the changes being introduced by the commit. <url>
- [ ] make large commits that introduce multiple features. <url>
- [ ] Keep local repository branches in sync with upstream branches in the remote repository by committing,pushing and pulling frequently. <url>
- [ ] Avoid frequent interaction with the remote repository to reduce the probability of pulling conflicts. <url>