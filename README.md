# Git_TutorialHere are some common **Git commands** you might find useful:

### Basic Git Commands:

1. **git init**  
   Initialize a new Git repository in the current directory.

2. **git clone [url]**  
   Clone an existing repository from a URL to your local machine.

3. **git status**  
   Show the status of changes in your working directory (which files are modified, added, or deleted).

4. **git add [file]**  
   Stage a specific file to be committed.

5. **git add .**  
   Stage all changes in the directory for commit.

6. **git commit -m "[message]"**  
   Commit staged changes with a descriptive message.

7. **git log**  
   Show the commit history.

8. **git diff**  
   Show the difference between your working directory and the last commit.

### Branching and Merging:

1. **git branch**  
   List all branches in the repository.

2. **git branch [branch-name]**  
   Create a new branch.

3. **git checkout [branch-name]**  
   Switch to another branch.

4. **git checkout -b [branch-name]**  
   Create a new branch and switch to it.

5. **git merge [branch-name]**  
   Merge changes from a specified branch into the current branch.

6. **git branch -d [branch-name]**  
   Delete a branch locally.

### Remote Repositories:

1. **git remote add origin [url]**  
   Add a remote repository (usually called "origin").

2. **git push origin [branch-name]**  
   Push local changes to the remote repository.

3. **git pull origin [branch-name]**  
   Fetch and merge changes from the remote repository to the local branch.

4. **git fetch**  
   Fetch changes from the remote repository but do not merge them automatically.

### Undoing Changes:

1. **git reset [file]**  
   Unstage a file (remove from staging area).

2. **git reset --hard**  
   Discard all local changes (careful, this deletes uncommitted changes).

3. **git checkout -- [file]**  
   Discard changes in a file and revert to the last committed version.

4. **git revert [commit]**  
   Create a new commit that undoes a previous commit.

### Stashing:

1. **git stash**  
   Save your uncommitted changes temporarily and clean your working directory.

2. **git stash pop**  
   Apply the most recent stash and remove it from the stash list.

3. **git stash list**  
   Show all stashed changes.


