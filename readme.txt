txtTips: Repositories
Make a new folder (aka directory)
$ mkdir <FOLDERNAME>
Navigate into an existing folder (aka change directory)
$ cd <FOLDERNAME>
List the items in a folder
$ ls
Turn Git on for a folder
$ git init

Tips: Commit To It
Check status of changes to a repository
$ git status
View changes to files
$ git diff
Add a file's changes to be committed
$ git add <FILENAME>
To add all files changes
$ git add .
To commit (aka save) the changes you've added with a short message describing the changes
$ git commit -m "<your commit message>"

Didn't Pass?
GitHub & Git config usernames do not match
A common error is not having your GitHub username match the case of the one you set with git config. For instance, 'JLord' isn't the same as 'jlord'
To change your username set with Git, just do the same command you did earlier, but with the correct capitalization:
$ git config --global user.username <USerNamE>
When you've made your updates, verify again!

Tips: Remotes
Add remote connections
$ git remote add <REMOTENAME> <URL>
Set a URL to a remote
$ git remote set-url <REMOTENAME> <URL>
Pull in changes
$ git pull <REMOTENAME> <BRANCHNAME>
View remote connections
$ git remote -v
Push changes
$ git push <REMOTENAME> <BRANCH>

Tips: Forks and Clones
Add remote connections
$ git remote add <REMOTENAME> <URL>
View remote connections
$ git remote -v

Tips: Branches Aren't Just For Birds
You can create and switch to a branch in one line:
$ git checkout -b <BRANCHNAME>
Create a new branch:
$ git branch <BRANCHNAME>
Move onto a branch:
$ git checkout <BRANCHNAME>
List the branches:
$ git branch
Rename a branch you're currently on:
$ git branch -m <NEWBRANCHNAME>
Verify what branch you're working on
$ git status

TIPS: Pull Never Out Of Date
Check Git status
$ git status
Pull in changes from a remote branch
$ git pull <REMOTENAME> <REMOTEBRANCH>
See changes to the remote before you pull in
$ git fetch --dry-run

Tips: Merge Tada
Merge a branch into current branch
$ git merge <BRANCHNAME>
Change the branch you're working on
$ git checkout <BRANCHNAME>
Delete a local branch
$ git branch -d <BRANCHNAME>
Delete a remote branch
$ git push <REMOTENAME> --delete <BRANCHNAME>
Pull from a remote branch
$ git pull <REMOTENAME> <BRANCHNAME>


