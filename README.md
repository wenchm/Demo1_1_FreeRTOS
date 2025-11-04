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