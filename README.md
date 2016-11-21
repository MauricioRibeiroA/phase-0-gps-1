# phase-0-gps-1
GPS 1.1 Version Control and Git


Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1
$ cd ..

Mauricio@MAURICIORIBEIRO /c/Sites
$ mkdir gps1.1

Mauricio@MAURICIORIBEIRO /c/Sites
$ cd gps1.1

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1
$ git clone https://github.com/MauricioRibeiroA/phase-0-gps-1.git
Cloning into 'phase-0-gps-1'...
remote: Counting objects: 4, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), done.
Checking connectivity... done.

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1
$ ls
phase-0-gps-1

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1
$ cd phase-0-gps-1/

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (master)
$ ls -la
total 4
drwxr-xr-x    5 Mauricio Administ        0 Nov 21 09:28 .
drwxr-xr-x    3 Mauricio Administ        0 Nov 21 09:28 ..
drwxr-xr-x   13 Mauricio Administ     4096 Nov 21 09:28 .git
-rw-r--r--    1 Mauricio Administ     1073 Nov 21 09:28 LICENSE
-rw-r--r--    1 Mauricio Administ       48 Nov 21 09:28 README.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (master)
$ git checkout -b feature-branch-website
Switched to a new branch 'feature-branch-website'

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (feature-branch-website)
$ touch awesome_page.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (feature-branch-website)
$ subl awesome_page.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (feature-branch-website)
$ git add awesome_page.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (feature-branch-website)
$ git status
On branch feature-branch-website
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   awesome_page.md


Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (feature-branch-website)
$ git commit -m "Adding the md file for the html week"
[feature-branch-website 33abddf] Adding the md file for the html week
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 awesome_page.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (feature-branch-website)
$ git push origin feature-branch-website
Username for 'https://github.com': MauricioRibeiroA
Password for 'https://MauricioRibeiroA@github.com':
Counting objects: 4, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 339 bytes | 0 bytes/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/MauricioRibeiroA/phase-0-gps-1.git
 * [new branch]      feature-branch-website -> feature-branch-website


Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (feature-branch-website)
$ cd ..

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1
$ ls
phase-0-gps-1

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1
$ cd phase-0-gps-1/

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (feature-branch-website)
$ cd ..

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1
$ cd phase-0-gps-1/

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (feature-branch-website)
$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (master)
$ git checkout -b add-command-log
Switched to a new branch 'add-command-log'

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (add-command-log)
$ git push origin add-command-log
Username for 'https://github.com': MauricioRibeiroA
Password for 'https://MauricioRibeiroA@github.com':
Total 0 (delta 0), reused 0 (delta 0)
To https://github.com/MauricioRibeiroA/phase-0-gps-1.git
 * [new branch]      add-command-log -> add-command-log

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (add-command-log)
$ touch command-log.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (add-command-log)
$ git add command-log.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (add-command-log)
$ git commit -m "Adding command log feature branch"
[add-command-log 282d4b5] Adding command log feature branch
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 command-log.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (add-command-log)
$ git push origin add-command-log
Username for 'https://github.com': MauricioRibeiroA
Password for 'https://MauricioRibeiroA@github.com':
Counting objects: 4, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 326 bytes | 0 bytes/s, done.
Total 2 (delta 0), reused 0 (delta 0)
To https://github.com/MauricioRibeiroA/phase-0-gps-1.git
   f3543e2..282d4b5  add-command-log -> add-command-log


Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (add-command-log)
$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (master)
$ ls
LICENSE  README.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (master)
$ git checkout add-command-log
Switched to branch 'add-command-log'

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (add-command-log)
$ ls
LICENSE  README.md  command-log.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (add-command-log)
$ subl readme.md

Mauricio@MAURICIORIBEIRO /c/Sites/gps1.1/phase-0-gps-1 (add-command-log)
$