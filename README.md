# git-cafe-exercise
# Bundle 5
## Exercise 2
```

Lenovo@DESKTOP-6LCGN4B MINGW64 ~ (main)
$ git clone https://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@github.com/ell-sie/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 95
Receiving objects: 100% (107/107), 1.95 MiB | 256.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.

Lenovo@DESKTOP-6LCGN4B MINGW64 ~ (main)
$ cd git-cafe-exercise/

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (main)
$ vi i
images/       index-2.html  index-4.html
index-1.html  index-3.html  index.html

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (main)
$ vi index.html

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (main)
$ git add .

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (main)
$ git commit -m 'changed index'
[main 3f25592] changed index
 1 file changed, 2 insertions(+), 2 deletions(-)

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 320 bytes | 160.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/ell-sie/git-cafe-exercise.git
   d1d3f9c..3f25592  main -> main
```
# Bundle 6
## Exercise 1
```
Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (main)
$ git checkout -b ft
Switched to a new branch 'ft'

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (ft)
$ ls
README.md  css/     index-1.html  index-3.html  index.html
bat/       images/  index-2.html  index-4.html  js/

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (ft)
$ vi menu.html

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (ft)
$ git add .
warning: LF will be replaced by CRLF in menu.html.
The file will have its original line endings in your working directory

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (ft)
$ git commit -m 'menu page '
[ft 1b91ec4] menu page
 1 file changed, 17 insertions(+)
 create mode 100644 menu.html

Lenovo@DESKTOP-6LCGN4B MINGW64 ~/git-cafe-exercise (ft)
$ git push --set-upstream origin ft
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 544 bytes | 181.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft' on GitHub by visiting:
remote:      https://github.com/ell-sie/git-cafe-exercise/pull/new/ft
remote:
To https://github.com/ell-sie/git-cafe-exercise.git
 * [new branch]      ft -> ft
branch 'ft' set up to track 'origin/ft'.
```
