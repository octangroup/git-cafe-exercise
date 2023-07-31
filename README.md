# git-cafe-exercise
#Bundle 6
## Exercise 1
```
Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (feature)
$ vi menu.html

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (feature)
$ git add .
warning: LF will be replaced by CRLF in menu.html.
The file will have its original line endings in your working directory

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (feature)
$ git commit -m 'menu'
On branch feature
nothing to commit, working tree clean

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (feature)
$ git push
fatal: The current branch feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature


Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (feature)
$ ls
README.md  css/     index-1.html  index-3.html  index.html  menu.html
bat/       images/  index-2.html  index-4.html  js/

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (feature)
$ git push --set-upstream origin feature
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'feature' on GitHub by visiting:
remote:      https://github.com/ell-sie/git-cafe-exercise/pull/new/feature
remote:
To https://github.com/ell-sie/git-cafe-exercise.git
 * [new branch]      feature -> feature
branch 'feature' set up to track 'origin/feature'.
```
## Exercise 2
```
Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (main)
$ git checkout -b bugfix
Switched to a new branch 'bugfix'

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ vi index-4.html

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ git add .

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ git commit -m 'made contact'
[bugfix 8d23aaf] made contact
 1 file changed, 2 insertions(+), 2 deletions(-)

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ git push --set-upstream origin index-4.html
error: src refspec index-4.html does not match any
error: failed to push some refs to 'https://github.com/ell-sie/git-cafe-exercise.git'

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ git push
fatal: The current branch bugfix has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin bugfix


Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ ^C

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ git push --set-upstream origin bugfix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'bugfix' on GitHub by visiting:
remote:      https://github.com/ell-sie/git-cafe-exercise/pull/new/bugfix
remote:
To https://github.com/ell-sie/git-cafe-exercise.git
 * [new branch]      bugfix -> bugfix
branch 'bugfix' set up to track 'origin/bugfix'.
```
## Exercise 3
```
Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ vi index-4.html
Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ git add .

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ git commit -m 'hotfix'
[bugfix dcf6866] hotfix
 1 file changed, 2 insertions(+), 2 deletions(-)

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (bugfix)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 312 bytes | 312.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/ell-sie/git-cafe-exercise.git
   a2384d5..dcf6866  bugfix -> bugfix
```
