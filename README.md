# GIT Exercise

## Bundle 6

### Exercise 1

```bash


vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (main)
$ git checkout -b feature
Switched to a new branch 'feature'

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (feature)
$ git status
On branch feature
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        menu.html


vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (feature)
$ git add menu.html

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (feature)
$ git status
On branch feature
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   menu.html


vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (feature)
$ git commit -m "created menu page"
[feature f4fdada] created menu page
 2 files changed, 26 insertions(+), 1 deletion(-)
 create mode 100644 menu.html

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (feature)
$ git push
fatal: The current branch feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (feature)



```

### Exercise 2

```bash


vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (main)
$ git checkout -b bug fix
fatal: 'fix' is not a commit and a branch 'bug' cannot be created from it

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (main)
$ git checkout -b bugfix
Switched to a new branch 'bugfix'

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (bugfix)
$ git status
On branch bugfix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index-4.html

no changes added to commit (use "git add" and/or "git commit -a")

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (bugfix)
$ git add index-4.html

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (bugfix)
$ git commit -m "changed to contact"
[bugfix 581f982] changed to contact
 1 file changed, 172 insertions(+), 157 deletions(-)

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (bugfix)
$ git push
fatal: The current branch bugfix has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin bugfix

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (bugfix)
$  git push --set-upstream origin bugfix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.17 KiB | 601.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'bugfix' on GitHub by visiting:
remote:      https://github.com/Niyonyungu/git-cafe-exercise/pull/new/bugfix
remote:
To https://github.com/Niyonyungu/git-cafe-exercise.git
 * [new branch]      bugfix -> bugfix
branch 'bugfix' set up to track 'origin/bugfix'.

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (bugfix)
$



```
