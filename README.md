# git-cafe-exercise
# git-cafe-exercise

```
$ git checkout -b ft/menu
Switched to a new branch 'ft/menu'

$ git add menu.html

$ git commit -m "ft(): Add menu"
[ft/menu 742863f] ft(): Add menu
 1 file changed, 20 insertions(+)
 create mode 100644 menu.html

$ git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

$ git push --set-upstream origin ft/menu
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 553 bytes | 553.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/Jmukakalisa/git-cafe-exercise/pull/new/ft/menu
remote:
To https://github.com/Jmukakalisa/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
branch 'ft/menu' set up to track 'origin/ft/menu'.
```