# Git Exercise

## Bundle 1

### Exercise 1

``` bash
H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions
$ git init
Initialized empty Git repository in C:/Users/H/Desktop/Gym Git Exercise Solutions/.git/

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (master)
$ git branch -M main

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git add README.md

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git commit -m "first commit init"
[main (root-commit) fd89513] first commit init
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git remote add origin https://github.com/danielsrw/Gym-Git-Exercise-Solutions.git

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git status
On branch main
nothing to commit, working tree clean

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 215 bytes | 215.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/danielsrw/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git checkout dev
error: pathspec 'dev' did not match any file(s) known to git

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (main)
$ git checkout -b dev
Switched to a new branch 'dev'

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (dev)
$ git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        bash.exe.stackdump

nothing added to commit but untracked files present (use "git add" to track)

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (dev)
$  push --set-upstream origin dev
bash: push: command not found

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (dev)
$ git push --set-upstream origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/danielsrw/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/danielsrw/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (dev)
$ git checkout -b test
Switched to a new branch 'test'

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/danielsrw/Gym-Git-Exercise-Solutions/pull/new/test
remote:
To https://github.com/danielsrw/Gym-Git-Exercise-Solutions.git
 * [new branch]      test -> test

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (test)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (dev)
$ git branch -D test
Deleted branch test (was fd89513).

H@RSM MINGW64 ~/Desktop/Gym Git Exercise Solutions (dev)
$ git push origin --delete test
To https://github.com/danielsrw/Gym-Git-Exercise-Solutions.git
 - [deleted]         test

```

### Exercise 2
``` bash

```
