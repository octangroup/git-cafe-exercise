## BUNDLE 6 
# EXERCISE 2
```bash
PS C:\Users\student\Downloads\git-cafe-exercise> git checkout main
Switched to branch 'main'
PS C:\Users\student\Downloads\git-cafe-exercise> git checkout -b bugfix/index-4.html
Switched to a new branch 'bugfix/index-4.html'
PS C:\Users\student\Downloads\git-cafe-exercise> git add index-4.html
PS C:\Users\student\Downloads\git-cafe-exercise> git status
On branch bugfix/index-4.html
Changes to be committed:
        modified:   index-4.html
PS C:\Users\student\Downloads\git-cafe-exercise> git commit -m "changed the title of the index-4.html file to Contact"
[bugfix/index-4.html 3ada082] changed the title of the index-4.html file to Contact
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\student\Downloads\git-cafe-exercise> git push origin  bugfix/index-4.html
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'bugfix/index-4.html' on GitHub by visiting:
remote:      https://github.com/AL2002MI08/git-cafe-exercise/pull/new/bugfix/index-4.html
remote:
To https://github.com/AL2002MI08/git-cafe-exercise.git
 * [new branch]      bugfix/index-4.html -> bugfix/index-4.html
PS C:\Users\student\Downloads\git-cafe-exercise>
```
