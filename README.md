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
### Exercise 2
```bash 

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/Menu-page)
$ git checkout -b "ft/bug-fix"
Switched to a new branch 'ft/bug-fix'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/bug-fix)
$ git status
On branch ft/bug-fix
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index-4.html

no changes added to commit (use "git add" and/or "git commit -a")

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/bug-fix)
$ git commit -m "bug-fix: title changed to Contact"
[ft/bug-fix bbe9f91] bug-fix: title changed to Contact
 1 file changed, 1 insertion(+), 1 deletion(-)


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/bug-fix)
$     git push --set-upstream origin ft/bug-fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 318 bytes | 318.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/bug-fix' on GitHub by visiting:
remote:      https://github.com/Algor-Fernand/git-cafe-exercise/pull/new/ft/bug-fix
remote:
To https://github.com/Algor-Fernand/git-cafe-exercise.git
 * [new branch]      ft/bug-fix -> ft/bug-fix
branch 'ft/bug-fix' set up to track 'origin/ft/bug-fix'.

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/bug-fix)
$

```

### Exercise 3
```bash 

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/bug-fix)
$ git checkout -b "ft/hotfix"
Switched to a new branch 'ft/hotfix'

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/hotfix)
$ git add .

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/hotfix)
$ git status
On branch ft/hotfix
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   index-4.html


DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/hotfix)
$ git commit -m "Hotfix: Telephone Number changed"
[ft/hotfix 8aaaa88] Hotfix: Telephone Number changed
 1 file changed, 1 insertion(+), 1 deletion(-)

DOLPHIX ELECTRONICS@DESKTOP-TJ49EDU MINGW64 ~/OneDrive/Desktop/The Gym/Git-Exercise/git-cafe-exercise (ft/hotfix)
$
```