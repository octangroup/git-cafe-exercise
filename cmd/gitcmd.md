
Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (main)
$ git add index.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.      

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index.html


Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (main)
$ git commit -m "feat: rename the main title"
[main 9253e38] feat: rename the main title
 1 file changed, 1 insertion(+), 1 deletion(-)

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/GSinseswa721/git-cafe-exercise-fork.git
   d1d3f9c..9253e38  main -> main

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (main)
$ git checkout -b feature
Switched to a new branch 'feature'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (feature)
$ touch menu.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (feature)
$ git add .

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (feature)
$ git commit -m "created new page "
[feature a7eafd7] created new page
 1 file changed, 11 insertions(+)
 create mode 100644 menu.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (feature)
$  git push origin feature
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 455 bytes | 455.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'feature' on GitHub by visiting:
remote:      https://github.com/GSinseswa721/git-cafe-exercise-fork/pull/new/feature
remote:
To https://github.com/GSinseswa721/git-cafe-exercise-fork.git
 * [new branch]      feature -> feature

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (feature)
$ git checkout -b bug/fix
Switched to a new branch 'bug/fix'

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git add *

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git commit -m "fixed page title"
[bug/fix 61ba765] fixed page title
 1 file changed, 204 insertions(+)
 create mode 100644 contact.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git push origin bug/fix 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.49 KiB | 851.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'bug/fix' on GitHub by visiting:
remote:      https://github.com/GSinseswa721/git-cafe-exercise-fork/pull/new/bug/fix
remote:
To https://github.com/GSinseswa721/git-cafe-exercise-fork.git
 * [new branch]      bug/fix -> bug/fix

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git add *

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git commit -m "changed number"
[bug/fix 291f806] changed number
 1 file changed, 2 insertions(+), 2 deletions(-)

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git commit -m "changed number"
On branch bug/fix
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    index-4.html

no changes added to commit (use "git add" and/or "git commit -a")

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git add index-4.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git commit -m "changed number"
[bug/fix 2675252] changed number
 1 file changed, 204 deletions(-)
 delete mode 100644 index-4.html

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git push origin bug/fix 
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 499 bytes | 249.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To https://github.com/GSinseswa721/git-cafe-exercise-fork.git
   61ba765..2675252  bug/fix -> bug/fix

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git add *

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git commit -m "changed number"
[bug/fix 71ac5cb] changed number
 1 file changed, 1 insertion(+), 1 deletion(-)

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$ git push origin bug/fix 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/GSinseswa721/git-cafe-exercise-fork.git
   2675252..71ac5cb  bug/fix -> bug/fix

Gloria Sinseswa@DESKTOP-GP85FQ5 MINGW64 ~/documents/git-cafe-exercise-fork (bug/fix)
$