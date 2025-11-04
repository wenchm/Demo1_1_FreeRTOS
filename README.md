# Demo1_1_FreeRTOS

# create a new repository on the command line
$ echo "# Demo1_1_FreeRTOS" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M master
$ git remote add origin https://github.com/wenchm/Demo1_1_FreeRTOS.git

$ git remote -v
origin  https://github.com/wenchm/Demo1_1_FreeRTOS.git (fetch)
origin  https://github.com/wenchm/Demo1_1_FreeRTOS.git (push)

$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 424 bytes | 212.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/wenchm/Demo1_1_FreeRTOS.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

# push an existing repository from the command line
$ git remote add origin https://github.com/wenchm/Demo1_1_FreeRTOS.git
$ git branch -M master
$ git push -u origin master

# push all files and dir.
$ git status
$ git add .
$ git commit -m "origin"
$ git push origin master
Enumerating objects: 334, done.
Counting objects: 100% (334/334), done.
Delta compression using up to 8 threads
Compressing objects: 100% (311/311), done.
Writing objects: 100% (333/333), 5.21 MiB | 1.76 MiB/s, done.
Total 333 (delta 98), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (98/98), done.
To https://github.com/wenchm/Demo1_1_FreeRTOS.git
   6e5bb15..f2c4333  master -> master
