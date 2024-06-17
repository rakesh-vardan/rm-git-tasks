# Home Tasks

**Task 1: Basic Repository Setup** - *Beginner*
   - Create a new directory and initialize it as a Git repository.
   - Create a new text file, add some content to it, and commit it to the repository.
   - Make changes to the file, commit the changes, and then view the commit history.

**Task 2: Branching and Merging** - *Intermediate*
   - Create a new branch from the master branch.
   - Make some changes in this new branch and commit them.
   - Switch back to the master branch and make some other changes and commit them.
   - Merge the new branch into the master branch and resolve any merge conflicts.

**Task 3: Remote Repositories** - *Intermediate*
   - Create a new repository on GitHub.
   - Connect your local repository to this remote repository.
   - Push your commits from your local repository to the remote repository.
   - Make a change directly on the remote repository (like editing a file from GitHub's interface), then pull the changes to your local repository.

**Task 4: Collaboration** - *Advanced*
   - Clone a remote repository that someone else has created.
   - Create a new branch, make some changes, and commit them.
   - Push your branch to the remote repository.
   - Create a pull request for your changes and merge them into the master branch of the remote repository.

**Task 5: Reverting and Resetting** - *Intermediate*
   - Make several commits to your repository.
   - Use `git revert` to undo one of the commits in the middle of your commit history.
   - Use `git reset` to completely remove a commit from your commit history.

**Task 6: Stashing and Cleaning** - *Intermediate*
   - Make some changes to your repository but do not commit them.
   - Use `git stash` to temporarily save your changes without committing them.
   - Switch to a different branch and make some changes there.
   - Switch back to your original branch and use `git stash pop` to reapply your stashed changes.

**Task 7: Tagging and Releasing** - *Intermediate*
   - Make several commits to your repository.
   - Use `git tag` to mark the current commit as a new version of your software.
   - Push your tags to the remote repository.
   - Go to the GitHub page for your repository and create a new release using your tag.

**Task 8: Cherry-Picking** - *Advanced*
   - Make several commits on a branch.
   - Switch to another branch and use `git cherry-pick` to apply one of the commits from the first branch to the second branch.

**Task 9: Rebasing** - *Advanced*
   - Create a new branch and make several commits on it.
   - Switch back to the master branch and make some more commits.
   - Use `git rebase` to move your branch's commits to be based on the latest commit on the master branch.

**Task 10: Advanced Git Log** - *Advanced*
- Use `git log` to view the commit history.
- Use different options with `git log` to change how the commit history is displayed. For example, try to display the commit history as a graph, or display only the commits that touch a certain file.

**Task 11: Bisecting** - *Advanced*
- Introduce a bug in your code and commit it.
- Use `git bisect` to find the commit that introduced the bug.

**Task 12: Submodules** - *Advanced*
- Create a new repository and add it as a submodule to your existing repository.
- Clone your repository along with its submodule(s).
- Make a change in the submodule, commit it, and push it to its own remote repository.

**Task 13: Git Hooks** - *Advanced*
- Write a simple pre-commit hook that checks for a certain pattern in your code and rejects the commit if the pattern is found.

**Task 14: Git Blame** - *Intermediate*
- Use `git blame` on a file to see who last modified each line of the file.

**Task 15: Git Reflog** - *Advanced*
- Make several commits and then use `git reset` to move the HEAD back a few commits.
- Use `git reflog` to find the commits you "lost" and use `git cherry-pick` to apply them again.

**Task 16: Git Fetch vs Pull** - *Intermediate*
- Explain the difference between `git fetch` and `git pull`. Demonstrate it with a practical example.

**Task 17: Git Revert vs Reset** - *Intermediate*
- Explain the difference between `git revert` and `git reset`. Demonstrate it with a practical example.

**Task 18: Git Archive** - *Intermediate*
- Use `git archive` to create a zip file of your repository at a certain commit.

**Task 19: Git Ignore** - *Beginner*
- Create a `.gitignore` file and configure it to ignore certain types of files in your repository.

**Task 20: Git Alias** - *Intermediate*
- Set up a few `git alias` commands to shorten some of your most frequently used Git commands.