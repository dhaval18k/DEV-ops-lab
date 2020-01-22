# DEV-ops-lab
sem-8 IT
user@user-H81M-S:~$ pwd
/home/user
user@user-H81M-S:~$ mkdir Dhaval-DEVOPS-28
user@user-H81M-S:~$ cd Dhaval-DEVOPS-28
user@user-H81M-S:~/Dhaval-DEVOPS-28$ ls
user@user-H81M-S:~/Dhaval-DEVOPS-28$ ls -a
.  ..
user@user-H81M-S:~/Dhaval-DEVOPS-28$ git config --global user.email "dhavalshree.khedkar@gmail.com"
user@user-H81M-S:~/Dhaval-DEVOPS-28$ git config --global --list 
user.name=dhaval
user.email=dhavalshree.khedkar@gmail.com
user@user-H81M-S:~/Dhaval-DEVOPS-28$ mkdir devops-git-demo
user@user-H81M-S:~/Dhaval-DEVOPS-28$ cd devops-git-demo/
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ ls
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ ls -a
.  ..
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ git init
Initialized empty Git repository in /home/user/Dhaval-DEVOPS-28/devops-git-demo/.git/
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ ls -a
.  ..  .git
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ nano dhaval.py
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ gedit abc.c
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ ls
dhaval.py
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ git add .
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ ls
dhaval.py
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ git status
On branch master

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   dhaval.py

user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ ls -a
.  ..  dhaval.py  .git
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ git commit -m "version-1"
[master (root-commit) f0ec7f1] version-1
 1 file changed, 1 insertion(+)
 create mode 100644 dhaval.py
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ git status
On branch master
nothing to commit, working directory clean
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ nano index.html
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ ls
dhaval.py  index.html
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	index.html

nothing added to commit but untracked files present (use "git add" to track)
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ git commit -m "version-2"
On branch master
Untracked files:
	index.html

nothing added to commit but untracked files present
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	index.html

nothing added to commit but untracked files present (use "git add" to track)
user@user-H81M-S:~/Dhaval-DEVOPS-28/devops-git-demo$ 
