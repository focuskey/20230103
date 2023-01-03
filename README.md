# 20230103
the github test
create the main

drwxrwxr-x 2 focuskey focuskey 4096 Jan  3 06:19 .idea
drwxrwxr-x 2 focuskey focuskey 4096 Jan  3 06:19 odoo
-rw-rw-r-- 1 focuskey focuskey   50 Jan  3 06:19 README.md
focuskey@ubuntu:~/clone_work15/20230103$ cd .idea/
focuskey@ubuntu:~/clone_work15/20230103/.idea$ ls
vcs.xml  workspace.xml
focuskey@ubuntu:~/clone_work15/20230103/.idea$ rm workspace.xml 
focuskey@ubuntu:~/clone_work15/20230103/.idea$ ls
vcs.xml
focuskey@ubuntu:~/clone_work15/20230103/.idea$ cd ..
focuskey@ubuntu:~/clone_work15/20230103$ git pull https://github.com/focuskey/20230103.git main
From https://github.com/focuskey/20230103
 * branch            main       -> FETCH_HEAD
error: The following untracked working tree files would be overwritten by merge:
        .idea/vcs.xml
Please move or remove them before you merge.
Aborting
focuskey@ubuntu:~/clone_work15/20230103$ cd .idea/
focuskey@ubuntu:~/clone_work15/20230103/.idea$ ls
vcs.xml
focuskey@ubuntu:~/clone_work15/20230103/.idea$ rm vcs.xml 
focuskey@ubuntu:~/clone_work15/20230103/.idea$ ls
focuskey@ubuntu:~/clone_work15/20230103/.idea$ cd ..
focuskey@ubuntu:~/clone_work15/20230103$ ls
15-demo.conf  odoo  README.md
focuskey@ubuntu:~/clone_work15/20230103$ git pull https://github.com/focuskey/20230103.git main
From https://github.com/focuskey/20230103


focuskey@ubuntu:~/clone_work15/20230103$ cd odoo/
focuskey@ubuntu:~/clone_work15/20230103/odoo$ ls
focuskey@ubuntu:~/clone_work15/20230103/odoo$ git init
Initialized empty Git repository in /home/focuskey/clone_work15/20230103/odoo/.git/
focuskey@ubuntu:~/clone_work15/20230103/odoo$ git clone https://github.com/odoo/odoo.git -b 15.0 --depth=1

