### Repository Setup and Configuration

1. `git init` - Initialize a new Git repository.
2. `git clone [repository URL]` - Clone an existing repository to your local machine.
3. `git config --global user.name "[name]"` - Set the global username for commits.
4. `git config --global user.email "[email]"` - Set the global email for commits.
5. `git config --list` - List all Git configuration settings.

### Working with Files

6. `git add [file]` - Add a specific file to the staging area.
7. `git add .` - Add all changes in the current directory to the staging area.
8. `git commit -m "[message]"` - Commit changes in the staging area with a message.
9. `git status` - Check the status of the working directory and staging area.
10. `git diff` - View changes not yet staged.
11. `git diff --staged` - View changes staged for the next commit.
12. `git rm [file]` - Remove a file from the working directory and staging area.
13. `git mv [old-name] [new-name]` - Rename or move a file.

### Viewing History and Logs

14. `git log` - Show a list of all commits.
15. `git log --oneline` - Show a compact list of commits with one line per commit.
16. `git show [commit ID]` - Show details of a specific commit.
17. `git blame [file]` - Show who last modified each line of a file.

### Branching and Merging

18. `git branch` - List all branches in the repository.
19. `git branch [branch-name]` - Create a new branch.
20. `git checkout [branch-name]` - Switch to a specified branch.
21. `git checkout -b [branch-name]` - Create and switch to a new branch.
22. `git merge [branch-name]` - Merge a specified branch into the current branch.
23. `git branch -d [branch-name]` - Delete a branch.
24. `git rebase [branch-name]` - Reapply commits on top of another branch.

### Stashing Changes

25. `git stash` - Save changes in the working directory to a stash.
26. `git stash apply` - Reapply the most recent stash.
27. `git stash list` - List all stashed changes.
28. `git stash drop` - Remove a specific stash.

### Working with Remote Repositories

29. `git remote add [name] [URL]` - Add a new remote repository.
30. `git remote -v` - List all remote connections.
31. `git fetch [remote-name]` - Fetch changes from a remote repository.
32. `git pull [remote-name] [branch-name]` - Fetch and merge changes from a remote branch.
33. `git push [remote-name] [branch-name]` - Push local commits to a remote branch.
34. `git push --tags` - Push all tags to a remote repository.

### Tagging

35. `git tag [tag-name]` - Create a new tag.
36. `git tag -a [tag-name] -m "[message]"` - Create an annotated tag with a message.
37. `git tag` - List all tags.

### Resetting and Reverting

38. `git reset [file]` - Unstage a file while keeping changes in the working directory.
39. `git reset --soft [commit ID]` - Move the branch pointer to an earlier commit without changing the working directory.
40. `git reset --hard [commit ID]` - Reset the branch and working directory to a specific commit.
41. `git revert [commit ID]` - Create a new commit that undoes the changes of a specified commit.

### Other Useful Commands

42. `git archive [branch-name]` - Create an archive (zip or tar) of a branch.
43. `git cherry-pick [commit ID]` - Apply a specific commit from one branch into another.
44. `git shortlog` - Summarize commit history by author.
45. `git bisect` - Perform a binary search to find a specific commit that introduced a bug.
46. `git clean -f` - Remove untracked files from the working directory.
47. `git reflog` - Show a log of all references, even those not in the commit history.
