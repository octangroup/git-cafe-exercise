# git-cafe-exercise

### Exercise 3

```bash
PS C:\Users\GIS\Documents\theGym\Git\git-cafe-exercise> git checkout -b ft/hot-fix
Switched to a new branch 'ft/hot-fix'
PS C:\Users\GIS\Documents\theGym\Git\git-cafe-exercise> code index-4.html
PS C:\Users\GIS\Documents\theGym\Git\git-cafe-exercise> git add .
PS C:\Users\GIS\Documents\theGym\Git\git-cafe-exercise> git commit -m "Hotfit change contact phone number"
[ft/hot-fix 5ac4bba] Hotfit change contact phone number
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\GIS\Documents\theGym\Git\git-cafe-exercise> git push
fatal: The current branch ft/hot-fix has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/hot-fix

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\GIS\Documents\theGym\Git\git-cafe-exercise> git push -u origin ft/hot-fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 311 bytes | 155.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/hot-fix' on GitHub by visiting:
remote:      https://github.com/Bateyjosue/git-cafe-exercise/pull/new/ft/hot-fix
remote:
To https://github.com/Bateyjosue/git-cafe-exercise.git
 * [new branch]      ft/hot-fix -> ft/hot-fix
branch 'ft/hot-fix' set up to track 'origin/ft/hot-fix'.
PS C:\Users\GIS\Documents\theGym\Git\git-cafe-exercise> 
```