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
$  git push --set-upstream origin feature
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 558 bytes | 279.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'feature' on GitHub by visiting:
remote:      https://github.com/Niyonyungu/git-cafe-exercise/pull/new/feature
remote:
To https://github.com/Niyonyungu/git-cafe-exercise.git
 * [new branch]      feature -> feature
branch 'feature' set up to track 'origin/feature'.

vainqueur@DESKTOP-KTN8E98 MINGW64 ~/git-cafe-exercise (feature)
$


```
