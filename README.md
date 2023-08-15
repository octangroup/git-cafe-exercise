# git-cafe-exercise

# Bundle 5 # Exercise 2
```
$ git clone https://github.com/riyoneri/git-cafe-exercise.git .
Cloning into '.'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 93
Receiving objects: 100% (107/107), 1.95 MiB | 121.00 KiB/s, done.
Resolving deltas: 100% (5/5), done.

RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (main)
$ git add .

RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (main)
$ git commit -m "change our place -> our restaurant"
[main b2066e6] change our place -> our restaurant
 1 file changed, 1 insertion(+), 1 deletion(-)

RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/riyoneri/git-cafe-exercise.git
   d1d3f9c..b2066e6  main -> main

RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (main)
$
```

## Bundle 6 # Exercise1
```
RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (main)
$ git switch -c ft/menu
Switched to a new branch 'ft/menu'

RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (ft/menu)
$ git branch
* ft/menu
  main

RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (ft/menu)
$ git add .

RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (ft/menu)
$ git commit -m "add menu.html"
[ft/menu f8af1c3] add menu.html
 1 file changed, 11 insertions(+)
 create mode 100644 menu.html

RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (ft/menu)
$ git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (ft/menu)
$ git push -u origin ft/menu 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 444 bytes | 444.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/riyoneri/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/riyoneri/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.

RIYO@DESKTOP-DETFET6 MINGW64 /d/Codes/009 - Studies/001 - The-Gym/001 - git/003 - git-cafe-exercises (ft/menu)
$
```