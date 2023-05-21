
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
