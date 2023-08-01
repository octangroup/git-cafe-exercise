# git-cafe-exercise
## bUNDLE 5
### EXRCISE 2
``` bash
victoire@victoire-Latitude-E7440:~/Videos/the gym/git-cafe-exercise$ git add .
victoire@victoire-Latitude-E7440:~/Videos/the gym/git-cafe-exercise$ git commit -m "changes"
[main 4b21b63] changes
 1 file changed, 1 insertion(+), 1 deletion(-)
victoire@victoire-Latitude-E7440:~/Videos/the gym/git-cafe-exercise$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/izibyosevictoire/git-cafe-exercise.git
   764c72e..4b21b63  main -> main
```

## Bundle 6
### exercise 1

``` bash
victoire@victoire-Latitude-E7440:~/Videos/the gym/git-cafe-exercise$ git add .
victoire@victoire-Latitude-E7440:~/Videos/the gym/git-cafe-exercise$ git commit -m "menu changes"
[ft/menu 6e67712] menu changes
 1 file changed, 1 insertion(+), 1 deletion(-)
victoire@victoire-Latitude-E7440:~/Videos/the gym/git-cafe-exercise$ git push
fatal: The current branch ft/menu has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/menu

victoire@victoire-Latitude-E7440:~/Videos/the gym/git-cafe-exercise$ git push --set-upstream origin ft/menu
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 2.75 KiB | 938.00 KiB/s, done.
Total 8 (delta 5), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (5/5), completed with 3 local objects.
remote: 
remote: Create a pull request for 'ft/menu' on GitHub by visiting:
remote:      https://github.com/izibyosevictoire/git-cafe-exercise/pull/new/ft/menu
remote: 
To https://github.com/izibyosevictoire/git-cafe-exercise.git
 * [new branch]      ft/menu -> ft/menu
Branch 'ft/menu' set up to track remote branch 'ft/menu' from 'origin'.
victoire@victoire-Latitude-E7440:~/Videos/the gym/git-cafe-exercise$ 

```
