# git-cafe-exercise
## Bundle 5
### Exercise 2
```bash

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (main)
$ git add index.html 

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (main)
$ git commit -m "renaming the main Title"
[main 1ce1855] renaming the main Title
 1 file changed, 1 insertion(+), 1 deletion(-)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 330 bytes | 165.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Algor-Fernand/git-cafe-exercise.git
   d1d3f9c..1ce1855  main -> main
```
## Bundle 6
### Exercise 1
```bash 
DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (main)
$ git checkout -b "ft/Menu-page"
Switched to a new branch 'ft/Menu-page'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/Menu-page)
$ git status
On branch ft/Menu-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        menu.html

nothing added to commit but untracked files present (use "git add" to track)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/Menu-page)
$ git add .


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/Menu-page)
$ git commit -m "a new menu page created"
[ft/Menu-page 1e08347] a new menu page created
 1 file changed, 12 insertions(+)
 create mode 100644 menu.html

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/Menu-page)
$ git push
fatal: The current branch ft/Menu-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/Menu-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/Menu-page)
$     git push --set-upstream origin ft/Menu-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 441 bytes | 220.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/Menu-page' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-cafe-exercise/pull/new/ft/Menu-page
remote:
To https://github.com/Algor-Fernand/git-cafe-exercise.git
 * [new branch]      ft/Menu-page -> ft/Menu-page
branch 'ft/Menu-page' set up to track 'origin/ft/Menu-page'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/Menu-page)
$
```