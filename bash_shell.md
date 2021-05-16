### By Luis Méndez.
## Git Shell

`git init`

>Create empty Git repo in specified directory. Run with no arguments to initialize the current directory as a git repository.

`git clone`
>Clone repo located at repo into local machine,

`git config  user.name`
>Define author name to be used for all commits in current repo.

`git config --global user.email <email>`
>Define the author email to be used for all commits by the current user.

`git add`
>Stage all changes for the next commit. 

`git commit -m`
>Commit the staged snapshot, but instead of launching a text editor, uses text as the commit message.

`git status`
>List which files are staged, unstaged, and untracked.

`git log`
>Display the entire commit history using the default format.

`git diff`
>Show unstaged changes between your index and working directory.


`git clean -n`
>Shows which files would be removed from working directory.

`git branch`
>Create a new connection to a remote repo. 

` git pull <remote>`
> Fetch the specified remote’s copy of current branch and immediately merge it into the local copy.

`git reset`
>Reset staging area to match most recent commit, but leave the working directory unchanged

`git checkout -b <branch>`
>Create and check out a new branch named branch. 

`git merge <branch>`
>Merge branch into the current branch.

`git push <remote> <branch>`
>Push the branch to <remote>, along with necessary commits and objects.