# git-cafe-exercise
## Bundle6
### Exercise1
```bash
user@DESKTOP-TQVNUUS MINGW64 ~/Documents/TheGym2/Git (main)
$ cd git-cafe-exercise/

user@DESKTOP-TQVNUUS MINGW64 ~/Documents/TheGym2/Git/git-cafe-exercise (main)
$ git branch ft/menu

user@DESKTOP-TQVNUUS MINGW64 ~/Documents/TheGym2/Git/git-cafe-exercise (main)
$ git switch ft/menu
Switched to branch 'ft/menu'

user@DESKTOP-TQVNUUS MINGW64 ~/Documents/TheGym2/Git/git-cafe-exercise (ft/menu)
$ touch Menu.html

user@DESKTOP-TQVNUUS MINGW64 ~/Documents/TheGym2/Git/git-cafe-exercise (ft/menu)
$ git add .

user@DESKTOP-TQVNUUS MINGW64 ~/Documents/TheGym2/Git/git-cafe-exercise (ft/menu)
$ git commit -m "menu"
[ft/menu 35d558d] menu
 1 file changed, 11 insertions(+)
 create mode 100644 Menu.html

user@DESKTOP-TQVNUUS MINGW64 ~/Documents/TheGym2/Git/git-cafe-exercise (ft/menu)
$ git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@DESKTOP-TQVNUUS MINGW64 ~/Documents/TheGym2/Git/git-cafe-exercise (ft/menu)
$ git push --set-upstream origin ft/menu
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 422 bytes | 211.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/UmutesiMMA/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/UmutesiMMA/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.
```

