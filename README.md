Git Commands :-

1. git branch
This command lists all the local branches in the current repository.
**Usage**: git branch [branch name]  
This command creates a new branch.
**Usage**: git branch -d [branch name]  
This command deletes the feature branch.


3. git status
This command lists all the files that have to be committed.

4. git fetch
5. git pull
**Usage**: git pull [Repository Link]  
This command fetches and merges changes on the remote server to your working directory.



7. git clone
**Usage**: git clone [url]  
This command is used to obtain a repository from an existing URL.


7. git checkout
**Usage**: git checkout [branch name]  
This command is used to switch from one branch to another.
**Usage**: git checkout -b [branch name]  
This command creates a new branch and also switches to it.



9. git checkout remote branch


11. git diff
**Usage**: git diff  
This command shows the file differences which are not yet staged.
**Usage**: git diff –staged 
This command shows the differences between the files in the staging area and the latest version present.
**Usage**: git diff [first branch] [second branch]  
This command shows the differences between the two branches mentioned.




11. git stash
**Usage**: git stash save  
This command temporarily stores all the modified tracked files.
**Usage**: git stash pop  
This command restores the most recently stashed files.
**Usage**: git stash list  
This command lists all stashed changesets.
**Usage**: git stash drop  
This command discards the most recently stashed changeset.

13. git log
This command is used to list the version history for the current branch.
**Usage**: git log –follow[file]  
This command lists version history for a file, including the renaming of files also.

14. git config :
**Usage**: git config –global user.name “[name]”  
This command sets the author name and email address respectively to be used with your commits.
**Usage**: git config –global user.email “[email address]”

13. git init
**Usage**: git init [repository name]
This command is used to start a new repository.


15. git commit
**Usage**: git commit -m “[ Type in the commit message]”  
This command records or snapshots the file permanently in the version history.
**Usage**: git commit -a  
This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.


17. git reset
**Usage**: git reset [file]  
This command unstages the file, but it preserves the file contents.
**Usage**: git reset [commit]  
This command undoes all the commits after the specified commit and preserves the changes locally.
**Usage**: git reset –hard [commit]  This command discards all history and goes back to the specified commit.


19. git merge
**Usage**: git merge [branch name]  
This command merges the specified branch’s history into the current branch.


21. git rebase

23. git cherry-pick
**Usage** : git cherry-pick commitid
This command is used to copy specific commit from one branch to another branch

24. git add 
**Usage**: git add [file]  
This command adds a file to the staging area.
**Usage**: git add *  
This command adds one or more to the staging area.

23. git rm file
This command deletes the file from your working directory and stages the deletion.

24. git show
**Usage**: git show [commit]  
This command shows the metadata and content changes of the specified commit.

25. git tag
**Usage**: git tag [commitID]  
This command is used to give tags to the specified commit.

26. git remote
Usage: git remote add [variable name] [Remote Server Link]  
This command is used to connect your local repository to the remote server.

27. git push
**Usage**: git push [variable name] master  
This command sends the committed changes of master branch to your remote repository.
**Usage**: git push [variable name] [branch]  
This command sends the branch commits to your remote repository.
**Usage**: git push –all [variable name]  
This command pushes all branches to your remote repository.
**Usage**: git push [variable name] :[branch name]  
This command deletes a branch on your remote repository.














 






