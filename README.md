# git-cafe-exercise

** Exercise 1

```

walte@Walter MINGW64 /d/git-cafe-exercise (main)
$ git checkout feature1
error: pathspec 'feature1' did not match any file(s) known to git

walte@Walter MINGW64 /d/git-cafe-exercise (main)
$ git checkout -b feature1
Switched to a new branch 'feature1'

walte@Walter MINGW64 /d/git-cafe-exercise (feature1)
$ ls
README.md  css/     index-1.html  index-3.html  index.html
bat/       images/  index-2.html  index-4.html  js/

walte@Walter MINGW64 /d/git-cafe-exercise (feature1)
$ touch Menu.html

walte@Walter MINGW64 /d/git-cafe-exercise (feature1)
$ vi README.md


```


** Exercise 2

```

walte@Walter MINGW64 /d/git-cafe-exercise (feature1)
$ git checkout -b feature2
Switched to a new branch 'feature2'

walte@Walter MINGW64 /d/git-cafe-exercise (feature2)
$ mv index
index-1.html  index-2.html  index-3.html  index-4.html  index.html

walte@Walter MINGW64 /d/git-cafe-exercise (feature2)
$ mv index
index-1.html  index-2.html  index-3.html  index-4.html  index.html

walte@Walter MINGW64 /d/git-cafe-exercise (feature2)
$ mv index-4.html
mv: missing destination file operand after 'index-4.html'
Try 'mv --help' for more information.

walte@Walter MINGW64 /d/git-cafe-exercise (feature2)
$ mv index-4.html contact.html

walte@Walter MINGW64 /d/git-cafe-exercise (feature2)
$

```

