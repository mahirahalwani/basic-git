## This is a basic Git/Github introduction notes for people who are new or not familiar to Github. (like me :P)


## Why we need Git
- easily retrieves other contributor's changes
- solving conflicts by letting the contributors choose which file to save and which file to delete
- multiple project versions, allowing several contributors to change one file at once
- never lose changes
- simple, leightweight, fast


## Other examples of Github
- GitLab, AWS CodeCommit, BitBucket, etc.

## Command Prompt
- git clone {repository URL}: creates a local project based on the link provided
- git remote -v : displays the link to the remote repository
- git add . : adds all changed files to the staging area
- git add {filename}: adds one or more files to stagign
- git reset {filename}: removes one or more files from staging
- git commit: creates a commit
- -m : adds comment
- git log: gives overview of commit
- git status: gives info about staged and unstaged files
- git branch: displays available brances
- git branch {branch name}: creates a new branch
- git checkout {branch name}: switches to a different branch
- git show {commit hash}: gives info about a specific commit
- git show --name-only {hash}: shows the changed file name only
- git reflog: gives info about all commits on all branches
- git push: sends commits to central repository
- git fetch: retrieves commits from central repository to local project
- git revert: creates a new commit to undo changes
- git reset --soft: removes commit from history but keeps the changes
- git reset --hard: removes commits from history and changes
- git merge: merges the branches
- git init: creates a new local repository in a folder or reinitialize an existing one
- git remote add: add a new remote repository to your project
- git diff sourceBranch targetBranch: compares differences between two different branches
- git tag: adds a tag references
- git stash: moves changes into a stash
- git rebase: reapplies commits on top of another base tip
- git clean: removes untracked files

** visit https://git-scm.com/ for all the git commands explanation

## Pull Requests
- A way for one contributer to have a look at another contributor's code, gives opinions and reviews, and approves or rejects changes
- Helps solve merge conflicts


## Thesaurus
1. Commit:
   A set of saved repository changes.
   Never lost.
   Has a hash key.
   Always the same.
3. Revert: Undoes the changes of a certain commit.
4. Staging: Makrs the files that we want to commit hence not all files are being committed.
5. Branches: A series of commits that can be manipulated independently.
6. Fetch: Retrieves from remote repository to local repository.
7. Push: Sends local file repository to remote repository.
