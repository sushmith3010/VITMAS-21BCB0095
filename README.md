# VITMAS-21BCB0095

GITHUB commands listed with its use and syntax
1) git init: intialize a new git repository.
suntax: git init[repository name]

2) git add: adds changes to the staging area
syntax: git add[file]

3) git commit: records changes to the repository.
syntax: git commit-m "commit message"

4) git push: pushes changes to a remote repository
syntax: git push[remote][branch]

5) git pull: pulls changes from a remote repository
syntax: git pull[remote][branch]

6) git clone: clones a remote repository to a local directory.
syntax:git clone[repositoryURL]

7) git branch: Lists, creates, or deletes branches. 
syntax: git brach[-a][-v][--merged][--no merged][...]

8) git checkout: switches to a different branch or commit.
syntax: git checkout[-q][-f][-m][][--]...

9) git merge: merges two or more branches.
syntax: git merge[--no-ff][-n][--commit][--squash][--no-edit][-s][-X]... ...

10)git status: displays the current status of the repository.
Syntax: git status [-s] [-u[]] [--ignored] [--ignore-submodules[=]] [--] [...]

11)git log: displays the commit history of the repository.
syntax: git log [--follow] [--grep=] [--author=] [--before=] [--after=] [--pretty[=]] [--graph] [--oneline] [--decorate] [--abbrev-commit] [--reverse] [--] [...]

12) git stash: stashes changes for later use. 
syntax: git stash save [-p] [-k] [--] []

13) git remote: lists, creates, or deletes remote repositories.
syntax: git remote [-v | --verbose] add [-t ] [-m ] [--[no-]tags] [--mirror=<fetch|push>] git fetch: Fetches changes from a remote repository but doesn't merge them into the local branch. Syntax: git fetch [remote]

14)git revert: reverts a commit by creating a new commit that undoes the changes made by the original commit.
syntax: git revert [commit]

15)git reset: resets the current branch to a specific commit. 
syntax: git reset [commit]

16)git rebase: applies changes from one branch onto another branch. 
syntax: git rebase [branch]

17)git tag: creates a tag for a specific commit in the repository. 
syntax: git tag [-a] [-m ] [] []

18)git diff: shows the differences between two commits or between the working directory and the repository. 
syntax: git diff [--options] [] [--] [...]

19)git rm: removes a file from the repository.
syntax: git rm [--force] [--cached]

20)git mv: renames a file in the repository.
syntax: git mv

21)git submodule: manages Git submodules, which are Git repositories embedded within a parent Git repository. 
syntax: git submodule [--quiet] add [-b ] [--name ] [--reference ] [--] []

22)git remote: manages remote repositories that the local repository can track.
syntax: git remote [-v | --verbose] add [-t ] [-m ] [--[no-]tags] [--mirror=<fetch|push>] git blame: Shows who last modified each line of a file. Syntax: git blame [-L ] [--]

23)git cherry-pick: applies the changes of a specific commit onto the current branch. 
syntax: git cherry-pick [-n] [-e] [-s] [-x] [--ff] [-m parent-number] [-s] [-x] ...

24)git bisect: helps to find which commit introduced a bug by performing a binary search.
syntax: git bisect [] []

25)git show: displays information about a specific commit.
syntax: git show [] []
