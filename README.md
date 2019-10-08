# Github_Handbook_Personal  Albert 2019
Steps, command and way to use github

Command Line: The computer program we use to input Git commands. On a Mac, it’s called Terminal. On a PC, it’s a non-native program that you must download to use Git for the first time. 

Repository: A directory or storage space where your projects can live. Sometimes GitHub users shorten this term to “repo”.

Version Control: The basic purpose Git was designed to serve. It keeps snapshots.

Commit: This is the command that gives Git its power. When you commit, you are taking a “snapshot” of your repository.

Branch: This is how multiple people work on a project at the same time without Git getting them confused.

# Inspection and Comparison Help

git help
Bring up the 21 most common git commands.

git status
Checks the status of your repository. See which files are inside it, which changes still need to be committed, and which branch of the repository you’re currently working on.

git diff
Shows the absolute changes between any two commit snapshots. It can be used to see how two branches differ from one another and seeing what has change since a release or some other older point in history.

git log
This command gives you the list of commits and filters through your commit history. You can use this command to find specific commits in your project history – by author, date, content, or history.

#git basic work flow
1. git add   (git add filename   or git add -a add all the files)
2. git status and git diff (can be used to see what has already been modified and staged.)
3.git commit -m "commit message" (This command records a snapshot of the staging area with a specified message to keep track of the changes made)

other useful command
git stash
git stash list
git stash apply 
git stash drop 

# Branching 
Branches can keep things organized when working with others in a project. This allow multiple persons work on same project simultanteously.

Basic work flow
1. git checkout -b branchname (create a branch for each bug fix or feature and switch into it )
2. git commit -m "changes you made to the branch" (when complete bug fix and commit snapshot while in that branch)
3. git checkout master (switch to master branch)
4. git merge branchname (git merge branchname)

other useful command
git branch (list all the branches)
git checkout branchname (switch to specified branch)
git branch -v (see the last commit on each branch)
git branch -d branchname (delete a branch)

# Merge, fetch and push
The workflow
1. git fetch origin (fetch download all the data it has that you do not)
2. git merge origin/master (merge into your current branch which is new to you)
3. git push -u origin master (push all your changes to remote repository o nthe github server)

