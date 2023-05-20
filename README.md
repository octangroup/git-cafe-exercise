# git-cafe-exercise

## Bundle 6 

### Exercise 1 

```bash

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (main)
$ git checkout -b ft/menu
Switched to a new branch 'ft/menu'

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (ft/menu)
$ git status
On branch ft/menu
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index-3.html

no changes added to commit (use "git add" and/or "git commit -a")

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (ft/menu)
$ git add .

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (ft/menu)
$ git commit -m 'modify our menu page'
[ft/menu 0c8e048] modify our menu page
 1 file changed, 1 insertion(+)

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (ft/menu)
$ git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (ft/menu)
$  git push --set-upstream origin ft/menu
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 348 bytes | 348.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/ishimwezachee/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/ishimwezachee/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.

```

### Exercise 2 

```bash
ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (main)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (main)
$ git checkout -b bg/fix
Switched to a new branch 'bg/fix'

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$ git status
On branch bg/fix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index-4.html

no changes added to commit (use "git add" and/or "git commit -a")

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$ git add .

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$ git commit -m 'change menu to contact'
[bg/fix 1c4770b] change menu to contact
 1 file changed, 1 insertion(+), 1 deletion(-)

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$ gi git push
bash: gi: command not found

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$ git push
fatal: The current branch bg/fix has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin bg/fix

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$   git push --set-upstream origin bg/fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 304 bytes | 304.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'bg/fix' on GitHub by visiting:
remote:      https://github.com/ishimwezachee/git-cafe-exercise/pull/new/bg/fix
remote:
To https://github.com/ishimwezachee/git-cafe-exercise.git
 * [new branch]      bg/fix -> bg/fix
branch 'bg/fix' set up to track 'origin/bg/fix'.

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)

```

### Exercises 3 

```bash
ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$ git status
On branch bg/fix
Your branch is up to date with 'origin/bg/fix'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index-4.html

no changes added to commit (use "git add" and/or "git commit -a")

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$ git add .

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$ git commit -m 'a hot fix'
[bg/fix e4849eb] a hot fix
 1 file changed, 1 insertion(+), 1 deletion(-)

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/ishimwezachee/git-cafe-exercise.git
   1c4770b..e4849eb  bg/fix -> bg/fix

ZACHEE@DESKTOP-JM7SBUV MINGW64 ~/Desktop/thegym/trainings/git-cafe-exercise (bg/fix)

```