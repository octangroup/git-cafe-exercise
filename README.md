
<h1>Bundle 6</h1>


PS E:\git-exercise> git clone https://github.com/Kevinemug/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 100Receiving objects:  91% (98/107), 572.00 KiB | 972.00 /107), 572.00 KiB | 972.00 Receiving objects: 100% (107/107), 1.95 MiB | 2.18 MiB/s, done. 

Resolving deltas: 100% (5/5), done.
PS E:\git-exercise> cd .\git-cafe-exercise\
PS E:\git-exercise\git-cafe-exercise> git add . 
PS E:\git-exercise\git-cafe-exercise> git commit -m"chnges"
[main 92fa0fe] chnges
 1 file changed, 2 insertions(+), 2 deletions(-)
PS E:\git-exercise\git-cafe-exercise> git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 324 bytes | 324.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Kevinemug/git-cafe-exercise.git
   d1d3f9c..92fa0fe  main -> main



PS E:\git-exercise\git-cafe-exercise> git pull origin main
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 1.09 KiB | 4.00 KiB/s, done.
From https://github.com/Kevinemug/git-cafe-exercise
 * branch            main       -> FETCH_HEAD
   92fa0fe..25b250d  main       -> origin/main
 README.md | 25 ++++++++++++++++++++++++-
 1 file changed, 24 insertions(+), 1 deletion(-)
Switched to a new branch 'feature/menu'
PS E:\git-exercise\git-cafe-exercise> git add .
PS E:\git-exercise\git-cafe-exercise> git commit -m "Add new 'Menu' page"
[feature/menu c0d8037] Add new 'Menu' page
 1 file changed, 1 insertion(+), 1 deletion(-)
PS E:\git-exercise\git-cafe-exercise> git push origin feature/menu
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 328 bytes | 328.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: Create a pull request for 'feature/menu' on GitHub by visiting:
remote:      https://github.com/Kevinemug/git-cafe-exercise/pull/new/feature/menu
remote:
 * [new branch]      feature/menu -> feature/menu
Already up to date.
PS E:\git-exercise\git-cafe-exercise> git checkout -b bugfix/change-title
PS E:\git-exercise\git-cafe-exercise> git add index-4.html
PS E:\git-exercise\git-cafe-exercise> git commit -m "Change title of index-4.html to 'Contact'"
[bugfix/change-title c1ef9f6] Change title of index-4.html to 'Contact'
 1 file changed, 1 insertion(+), 1 deletion(-)
PS E:\git-exercise\git-cafe-exercise> git push origin bugfix/change-title
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 324 bytes | 324.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'bugfix/change-title' on GitHub by visiting:
remote:      https://github.com/Kevinemug/git-cafe-exercise/pull/new/bugfix/change-title   
remote:
To https://github.com/Kevinemug/git-cafe-exercise.git
 * [new branch]      bugfix/change-title -> bugfix/change-title
PS E:\git-exercise\git-cafe-exercise> git pull origin main
 * branch            main       -> FETCH_HEAD
Your branch is up to date with 'origin/main'.
PS E:\git-exercise\git-cafe-exercise> git checkout -b hotfix/contact-telephone
PS E:\git-exercise\git-cafe-exercise> git add index-4.html
PS E:\git-exercise\git-cafe-exercise> git commit -m "Update telephone number on contact page"
[hotfix/contact-telephone ec6f1cf] Update telephone number on contact page
 1 file changed, 1 insertion(+), 1 deletion(-)
PS E:\git-exercise\git-cafe-exercise> git push origin hotfix/contact-telephone
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 333 bytes | 333.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'hotfix/contact-telephone' on GitHub by visiting:        
remote:      https://github.com/Kevinemug/git-cafe-exercise/pull/new/hotfix/contact-telephone
remote:
To https://github.com/Kevinemug/git-cafe-exercise.git
 * [new branch]      hotfix/contact-telephone -> hotfix/contact-telephone
PS E:\git-exercise\git-cafe-exercise>




