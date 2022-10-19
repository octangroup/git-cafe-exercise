# git-cafe-exercise



BUNDLE 1

EXERCISE 1

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop
$ git clone https://github.com/Delyc/Gym-Git-Exercise.git
Cloning into 'Gym-Git-Exercise'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop
$ cd Gym-Git-Exercise

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ touch index.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ code .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ mv index.html main.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git commit -m "created index.html and renamed to main.html"
[main 4fd7f55] created index.html and renamed to main.html
 1 file changed, 12 insertions(+)
 create mode 100644 main.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 502 bytes | 502.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Delyc/Gym-Git-Exercise.git
   3397bec..4fd7f55  main -> main

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git checkout -b dev
Switched to a new branch 'dev'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git checkout -b test
Switched to a new branch 'test'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (test)
$ git branch -d test
error: Cannot delete branch 'test' checked out at 'C:/Users/TheGym/Desktop/Gym-Git-Exercise'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (test)
$ git checkout dev
Switched to branch 'dev'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git branch -d test
Deleted branch test (was 4fd7f55).




EXERCISE 2


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ touch home.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git stash
Saved working directory and index state WIP on dev: 4fd7f55 created index.html and renamed to main.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ touch about.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git stash
Saved working directory and index state WIP on dev: 4fd7f55 created index.html and renamed to main.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ touch team.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git stash
Saved working directory and index state WIP on dev: 4fd7f55 created index.html and renamed to main.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git stash list
stash@{0}: WIP on dev: 4fd7f55 created index.html and renamed to main.html
stash@{1}: WIP on dev: 4fd7f55 created index.html and renamed to main.html
stash@{2}: WIP on dev: 4fd7f55 created index.html and renamed to main.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git stash apply stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git stash apply stash@{2}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git commit -m "restored home and about page from stash"
[dev 90f0a85] restored home and about page from stash
 2 files changed, 24 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git push --set-upstream origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 586 bytes | 586.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Delyc/Gym-Git-Exercise/pull/new/dev
remote:
To https://github.com/Delyc/Gym-Git-Exercise.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git stash apply stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git reset --hard
HEAD is now at 90f0a85 restored home and about page from stash


BUNDLE 2
EXERCISE 1



TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/bundle-2)
$ touch services.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/bundle-2)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/bundle-2)
$ git commit -m "created services page"
[ft/bundle-2 7fc23ff] created services page
 1 file changed, 12 insertions(+)
 create mode 100644 services.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/bundle-2)
$  git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 483 bytes | 483.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Delyc/Gym-Git-Exercise/pull/new/ft/bundle-2
remote:
To https://github.com/Delyc/Gym-Git-Exercise.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.


Exercise 2


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git pull origin main
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 613 bytes | 153.00 KiB/s, done.
From https://github.com/Delyc/Gym-Git-Exercise
 * branch            main       -> FETCH_HEAD
   4fd7f55..1bec6c6  main       -> origin/main
Updating 4fd7f55..1bec6c6
Fast-forward
 about.html    | 12 ++++++++++++
 home.html     | 12 ++++++++++++
 services.html | 12 ++++++++++++
 3 files changed, 36 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign)
$ touch service.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign)
$ git commit -m "changed service page"
[ft/service-redesign b9c9712] changed service page
 1 file changed, 1 insertion(+), 1 deletion(-)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign)
$ git push --set-upstream origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/Delyc/Gym-Git-Exercise/pull/new/ft/service-redesign
remote:
To https://github.com/Delyc/Gym-Git-Exercise.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git commit -m "changed service page from main"
[main dbd6ef0] changed service page from main
 1 file changed, 1 insertion(+), 1 deletion(-)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 319 bytes | 319.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Delyc/Gym-Git-Exercise.git
   1bec6c6..dbd6ef0  main -> main

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign)
$ git diff origin/main ft/service-redesign
diff --git a/services.html b/services.html
index 329d651..c9e8a2e 100644
--- a/services.html
+++ b/services.html
@@ -7,6 +7,6 @@
     <title>Document</title>
 </head>
 <body>
-    <h1>This is services page, changed from main</h1>
+    <h1>This is services page, changed</h1>
 </body>
 </html>
\ No newline at end of file

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign)
$ git merge origin main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign|MERGING)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign|MERGING)
$ git commit -m "merged main and ft/service-redesign branch"
[ft/service-redesign 636b377] merged main and ft/service-redesign branch

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign)
$ git push
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 238 bytes | 238.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Delyc/Gym-Git-Exercise.git
   b9c9712..636b377  ft/service-redesign -> ft/service-redesign




BUNDLE 3
Exercise 1



TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/service-redesign)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/team-page)
$ touch team.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/team-page)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/team-page)
$ git commit -m "creating team page"
[ft/team-page 4619064] creating team page
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/team-page)
$ git push --set-upstream origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 474 bytes | 474.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Delyc/Gym-Git-Exercise/pull/new/ft/team-page
remote:
To https://github.com/Delyc/Gym-Git-Exercise.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/team-page)
$ git log
commit 461906464dec5050af15220452cb79cd91d6e526 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Delyc <d.twizeyima@alustudent.com>
Date:   Wed Oct 19 17:06:15 2022 +0200

    creating team page

commit 636b377d05652323c01b25452a3aee089d592698 (origin/ft/service-redesign, ft/service-redesign)
Merge: b9c9712 dbd6ef0
Author: Delyc <d.twizeyima@alustudent.com>
Date:   Wed Oct 19 17:03:50 2022 +0200

    merged main and ft/service-redesign branch

commit dbd6ef0fa8c9f8508fdbc92ec6593725746ec2ca (origin/main, origin/HEAD, main, ft/contact-page)
Author: Delyc <d.twizeyima@alustudent.com>
Date:   Wed Oct 19 17:00:45 2022 +0200

    changed service page from main

commit b9c9712d66a00e44e30c876701f1f27042c1b030
Author: Delyc <d.twizeyima@alustudent.com>
Date:   Wed Oct 19 16:58:49 2022 +0200

    changed service page

commit 1bec6c63bb6d1c3016fa66bdbf8e585172b6a2f7
Merge: 4fd7f55 7fc23ff
Author: Chrissie <chrissiemhrk@gmail.com>
Date:   Wed Oct 19 16:43:13 2022 +0200

    Merge pull request #2 from Delyc/ft/bundle-2

    Ft/bundle 2

commit 7fc23ff6036da9ee2dc592862f3f41983ff86bd7 (origin/ft/bundle-2, ft/bundle-2)
Author: Delyc <d.twizeyima@alustudent.com>
Date:   Wed Oct 19 16:35:30 2022 +0200

    created services page

commit 90f0a85dbd6e5a6ec6b9ee915a34c53999ce28bf (origin/dev, dev)
Author: Delyc <d.twizeyima@alustudent.com>
Date:   Wed Oct 19 16:30:35 2022 +0200

    restored home and about page from stash

commit 4fd7f558c65fa64549ba84635932fe70c779847c
Author: Delyc <d.twizeyima@alustudent.com>
Date:   Wed Oct 19 16:19:24 2022 +0200

    created index.html and renamed to main.html

commit 3397bec29467fefd1f6cc030ab558cf5b68bc215
Author: Delyce Twizeyimana <d.twizeyima@alustudent.com>
Date:   Wed Oct 19 15:23:30 2022 +0200

    Initial commit

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/contact-page)
$ git cherry-pick 461906464dec5050af15220452cb79cd91d6e526
[ft/contact-page d2292a0] creating team page
 Date: Wed Oct 19 17:06:15 2022 +0200
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/contact-page)
$ touch contact.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/contact-page)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/contact-page)
$ git commit -m "merged last commit from team branch and created contact page"
[ft/contact-page 80683ca] merged last commit from team branch and created contact page
 1 file changed, 12 insertions(+)
 create mode 100644 contact.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/contact-page)
$ git push --set-upstream origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 750 bytes | 750.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Delyc/Gym-Git-Exercise/pull/new/ft/contact-page
remote:
To https://github.com/Delyc/Gym-Git-Exercise.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/faq-page)
$ touch faq.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/faq-page)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/faq-page)
$ git commit -m "created faq page"
[ft/faq-page 23559fd] created faq page
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/faq-page)
$ git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 469 bytes | 469.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Delyc/Gym-Git-Exercise/pull/new/ft/faq-page
remote:
To https://github.com/Delyc/Gym-Git-Exercise.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/faq-page)
$ git revert 461906464dec5050af15220452cb79cd91d6e526
[ft/faq-page 04a7dbf] Revert "creating team page"
 1 file changed, 12 deletions(-)
 delete mode 100644 team.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/faq-page)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 279 bytes | 279.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Delyc/Gym-Git-Exercise.git
   23559fd..04a7dbf  ft/faq-page -> ft/faq-page





Exercise 2


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git commit -m "changine home page from main"
[main 59054e9] changine home page from main
 1 file changed, 1 insertion(+), 1 deletion(-)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 322 bytes | 322.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Delyc/Gym-Git-Exercise.git
   dbd6ef0..59054e9  main -> main

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git checkout -b ft/home-page-redesign
fatal: a branch named 'ft/home-page-redesign' already exists

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/home-page-redesign)
$ git rebase  main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/home-page-redesign)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/home-page-redesign)
$ git commit -m "home changes from home-redesign"
[ft/home-page-redesign 1341ea8] home changes from home-redesign
 1 file changed, 1 insertion(+), 1 deletion(-)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/home-page-redesign)
$ git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 16, done.
Counting objects: 100% (16/16), done.
Delta compression using up to 4 threads
Compressing objects: 100% (14/14), done.
Writing objects: 100% (14/14), 1.45 KiB | 496.00 KiB/s, done.
Total 14 (delta 8), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (8/8), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Delyc/Gym-Git-Exercise/pull/new/ft/home-page-redesign
remote:
To https://github.com/Delyc/Gym-Git-Exercise.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.



BUNDLE 4

Exercise 1


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git remote add git-copy https://github.com/Delyc/Gym-git-Exercise__repo2.git

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git commit -m "new chnages and new remote"
[main ece10af] new chnages and new remote
 1 file changed, 1 insertion(+), 1 deletion(-)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git push git-copy main
Enumerating objects: 23, done.
Counting objects: 100% (23/23), done.
Delta compression using up to 4 threads
Compressing objects: 100% (21/21), done.
Writing objects: 100% (23/23), 2.95 KiB | 1006.00 KiB/s, done.
Total 23 (delta 11), reused 3 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (11/11), done.
To https://github.com/Delyc/Gym-git-Exercise__repo2.git
 * [new branch]      main -> main


Exercise 2


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/footer)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/footer)
$ git commit -m "changing home from main"
[ft/footer 1f625df] changing home from main
 1 file changed, 1 insertion(+), 1 deletion(-)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/footer)
$ git push --set-upstream origin ft/footer
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 628 bytes | 628.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Delyc/Gym-Git-Exercise/pull/new/ft/footer
remote:
To https://github.com/Delyc/Gym-Git-Exercise.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/footer)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/footer)
$ git commit -m "creating footer page"
[ft/footer ed2a0d2] creating footer page
 1 file changed, 12 insertions(+)
 create mode 100644 footer.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/footer)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 470 bytes | 470.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Delyc/Gym-Git-Exercise.git
   1f625df..ed2a0d2  ft/footer -> ft/footer

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/footer)
$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/squashing)
$ git merge --squash ft/footer
Already up to date. (nothing to squash)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/squashing)
$ git checkout ft/footer
Switched to branch 'ft/footer'
Your branch is up to date with 'origin/ft/footer'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/footer)
$ git branch -d ft/squashing
Deleted branch ft/squashing (was ed2a0d2).

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/footer)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/squashing)
$ git merge --squash ft/footer
Updating ece10af..ed2a0d2
Fast-forward
Squash commit -- not updating HEAD
 footer.html | 12 ++++++++++++
 home.html   |  2 +-
 2 files changed, 13 insertions(+), 1 deletion(-)
 create mode 100644 footer.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/squashing)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/squashing)
$ git commit -m "footer changes squashing "
[ft/squashing 4855ace] footer changes squashing
 2 files changed, 13 insertions(+), 1 deletion(-)
 create mode 100644 footer.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/squashing)
$ git push --set-upstream origin ft/s
error: src refspec ft/s does not match any
error: failed to push some refs to 'https://github.com/Delyc/Gym-Git-Exercise.git'

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/squashing)
$ git push --set-upstream origin ft/squashing
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 592 bytes | 592.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/Delyc/Gym-Git-Exercise/pull/new/ft/squashing
remote:
To https://github.com/Delyc/Gym-Git-Exercise.git
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (ft/squashing)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ mv home.html index.html

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git commit -m "renaming home to inde"
[main f3ac7fd] renaming home to inde
 1 file changed, 0 insertions(+), 0 deletions(-)
 rename home.html => index.html (100%)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 237 bytes | 237.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Delyc/Gym-Git-Exercise.git
   59054e9..f3ac7fd  main -> main




BUNDLE 5

Exercise 2


TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/Gym-Git-Exercise (main)
$ cd ..

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop
$ git clone https://github.com/Delyc/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (107/107), done.
remote: Compressing objects: 100% (101/101), done.
remote: Total 107 (delta 5), reused 104 (delta 4), pack-reused 0
Receiving objects: 100% (107/107), 1.95 MiB | 1.76 MiB/s, done.
Resolving deltas: 100% (5/5), done.

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop
$ cd git-cafe-exercise/

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/git-cafe-exercise (main)
$ code .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/git-cafe-exercise (main)
$ git add .

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/git-cafe-exercise (main)
$ git commit -m "changing text on the index page"
[main c963f8f] changing text on the index page
 1 file changed, 1 insertion(+), 1 deletion(-)

TheGym@DESKTOP-NLLQJTO MINGW64 ~/Desktop/git-cafe-exercise (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Delyc/git-cafe-exercise.git
   d1d3f9c..c963f8f  main -> main


