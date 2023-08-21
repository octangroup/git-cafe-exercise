# git-cafe-exercise
# git-cafe-exercise

- Bundle 6

- Exercise 1

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

- Exercise 2

````
git checkout -b bg/fix-index-4
Switched to a new branch 'bg/fix-index-4'
git add .
git commit -m "bg(): fix index-4 title"
[bg/fix-index-4 e325ce0] bg(): fix index-4 title
 1 file changed, 1 insertion(+), 1 deletion(-)
 git push
fatal: The current branch bg/fix-index-4 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin bg/fix-index-4

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

git push --set-upstream origin bg/fix-index-4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 311 bytes | 311.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'bg/fix-index-4' on GitHub by visiting:
remote:      https://github.com/Jmukakalisa/git-cafe-exercise/pull/new/bg/fix-index-4
remote:
To https://github.com/Jmukakalisa/git-cafe-exercise.git
 * [new branch]      bg/fix-index-4 -> bg/fix-index-4
branch 'bg/fix-index-4' set up to track 'origin/bg/fix-index-4'.
```

- Exercise 3

```
git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

git checkout -b ft/hotfix
Switched to a new branch 'ft/hotfix'

git add .

git commit -m "ft(): hotfix"
[ft/hotfix fa5de7d] ft(): hotfix
 1 file changed, 1 insertion(+), 1 deletion(-)

git push --set-upstream origin ft/hotfix     
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/hotfix' on GitHub by visiting:
remote:      https://github.com/Jmukakalisa/git-cafe-exercise/pull/new/ft/hotfix
remote:
To https://github.com/Jmukakalisa/git-cafe-exercise.git
 * [new branch]      ft/hotfix -> ft/hotfix
branch 'ft/hotfix' set up to track 'origin/ft/hotfix'.
```
