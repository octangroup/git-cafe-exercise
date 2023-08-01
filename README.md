# git-cafe-exercise
## Bundle 6 
### Exercise 1
```bash
umuhi@IKYK MINGW64 /d/git-cafe-exercise (feature)
$ git add index-3.html

umuhi@IKYK MINGW64 /d/git-cafe-exercise (feature)
$ git commit -m 'changing the menu page'
[feature bb12958] changing the menu page
 1 file changed, 1 insertion(+), 1 deletion(-)

umuhi@IKYK MINGW64 /d/git-cafe-exercise (feature)
$ git push
fatal: The current branch feature has no upstream branch.
To push the current branch and set the remote as upstream, use


umuhi@IKYK MINGW64 /d/git-cafe-exercise (feature)
$ git push --set-upstream origin feature
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 333 bytes | 166.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'feature' on GitHub by visiting:
remote:      https://github.com/CynthiaUmuhire/git-cafe-exercise/pull/new/feature
remote:
To https://github.com/CynthiaUmuhire/git-cafe-exercise.git
 * [new branch]      feature -> feature
branch 'feature' set up to track 'origin/feature'.

umuhi@IKYK MINGW64 /d/git-cafe-exercise (feature)
$ git checkout main
Switched to branch 'main'
M       README.md
Your branch is up to date with 'origin/main'.

umuhi@IKYK MINGW64 /d/git-cafe-exercise (main)

```