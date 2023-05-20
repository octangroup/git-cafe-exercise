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