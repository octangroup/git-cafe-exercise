## Bundle6

## exercise1

```bash

PS C:\Users\Eligrand\git-cafe-exercise> git checkout -b feature
Switched to a new branch 'feature'
PS C:\Users\Eligrand\git-cafe-exercise> git checkout -b add-menu
Switched to a new branch 'add-menu'
PS C:\Users\Eligrand\git-cafe-exercise> git add .\menu.html
PS C:\Users\Eligrand\git-cafe-exercise> git commit -m 'menu page'
[add-menu ce91f23] menu page
 1 file changed, 12 insertions(+)
 create mode 100644 menu.html
PS C:\Users\Eligrand\git-cafe-exercise> git push origin add-menu
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 473 bytes | 157.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'add-menu' on GitHub by visiting:
remote:      https://github.com/Nezerwa/git-cafe-exercise/pull/new/add-menu
remote:
To https://github.com/Nezerwa/git-cafe-exercise.git
 * [new branch]      add-menu -> add-menu
PS C:\Users\Eligrand\git-cafe-exercise>

```

## exercise2

```bash

PS C:\Users\Eligrand\git-cafe-exercise> git checkout -b bug-fix-branch
Switched to a new branch 'bug-fix-branch'
PS C:\Users\Eligrand\git-cafe-exercise> git .\index-4.html
git: '.\index-4.html' is not a git command. See 'git --help'.
PS C:\Users\Eligrand\git-cafe-exercise> git add .\index-4.html
PS C:\Users\Eligrand\git-cafe-exercise> git commit -m 'Edit title of page'
[bug-fix-branch a92ceed] Edit title of page
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\Eligrand\git-cafe-exercise> git push origin bug-fix-branch
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 300 bytes | 150.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'bug-fix-branch' on GitHub by visiting:
remote:      https://github.com/Nezerwa/git-cafe-exercise/pull/new/bug-fix-branch
remote:
To https://github.com/Nezerwa/git-cafe-exercise.git
 * [new branch]      bug-fix-branch -> bug-fix-branch
PS C:\Users\Eligrand\git-cafe-exercise>

```
