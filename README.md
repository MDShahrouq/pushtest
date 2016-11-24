# pushtest

veena@veena-PC:~$ ls
Android                Desktop    env               Pictures  Templates
android-studio         Documents  examples.desktop  Public    tutorial
AndroidStudioProjects  Downloads  Music             snippets  Videos
veena@veena-PC:~$ mkdir github
veena@veena-PC:~$ cd github/
veena@veena-PC:~/github$ git clone git@github.com:MDShahrouq/helloworld.git
The program 'git' is currently not installed. You can install it by typing:
sudo apt-get install git
veena@veena-PC:~/github$ sudo apt-get install git
[sudo] password for veena: 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  account-plugin-windows-live libntdb1 libupstart1 python-ntdb
Use 'apt-get autoremove' to remove them.
The following extra packages will be installed:
  git-man liberror-perl
Suggested packages:
  git-daemon-run git-daemon-sysvinit git-doc git-el git-email git-gui gitk
  gitweb git-arch git-bzr git-cvs git-mediawiki git-svn
The following NEW packages will be installed:
  git git-man liberror-perl
0 upgraded, 3 newly installed, 0 to remove and 26 not upgraded.
Need to get 3,306 kB of archives.
After this operation, 21.9 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Err http://in.archive.ubuntu.com/ubuntu/ trusty/main liberror-perl all 0.17-1.1
  Could not resolve 'in.archive.ubuntu.com'
Err http://in.archive.ubuntu.com/ubuntu/ trusty-updates/main git-man all 1:1.9.1-1ubuntu0.3
  Could not resolve 'in.archive.ubuntu.com'
Err http://security.ubuntu.com/ubuntu/ trusty-security/main git-man all 1:1.9.1-1ubuntu0.3
  Could not resolve 'security.ubuntu.com'
Err http://security.ubuntu.com/ubuntu/ trusty-security/main git amd64 1:1.9.1-1ubuntu0.3
  Could not resolve 'security.ubuntu.com'
E: Failed to fetch http://in.archive.ubuntu.com/ubuntu/pool/main/libe/liberror-perl/liberror-perl_0.17-1.1_all.deb  Could not resolve 'in.archive.ubuntu.com'

E: Failed to fetch http://security.ubuntu.com/ubuntu/pool/main/g/git/git-man_1.9.1-1ubuntu0.3_all.deb  Could not resolve 'security.ubuntu.com'

E: Failed to fetch http://security.ubuntu.com/ubuntu/pool/main/g/git/git_1.9.1-1ubuntu0.3_amd64.deb  Could not resolve 'security.ubuntu.com'

E: Unable to fetch some archives, maybe run apt-get update or try with --fix-missing?
veena@veena-PC:~/github$ sudo apt-get install git
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  account-plugin-windows-live libntdb1 libupstart1 python-ntdb
Use 'apt-get autoremove' to remove them.
The following extra packages will be installed:
  git-man liberror-perl
Suggested packages:
  git-daemon-run git-daemon-sysvinit git-doc git-el git-email git-gui gitk
  gitweb git-arch git-bzr git-cvs git-mediawiki git-svn
The following NEW packages will be installed:
  git git-man liberror-perl
0 upgraded, 3 newly installed, 0 to remove and 26 not upgraded.
Need to get 3,306 kB of archives.
After this operation, 21.9 MB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://in.archive.ubuntu.com/ubuntu/ trusty/main liberror-perl all 0.17-1.1 [21.1 kB]
Get:2 http://in.archive.ubuntu.com/ubuntu/ trusty-updates/main git-man all 1:1.9.1-1ubuntu0.3 [699 kB]
Get:3 http://in.archive.ubuntu.com/ubuntu/ trusty-updates/main git amd64 1:1.9.1-1ubuntu0.3 [2,586 kB]
Fetched 3,306 kB in 18s (175 kB/s)                                             
Selecting previously unselected package liberror-perl.
(Reading database ... 165938 files and directories currently installed.)
Preparing to unpack .../liberror-perl_0.17-1.1_all.deb ...
Unpacking liberror-perl (0.17-1.1) ...
Selecting previously unselected package git-man.
Preparing to unpack .../git-man_1%3a1.9.1-1ubuntu0.3_all.deb ...
Unpacking git-man (1:1.9.1-1ubuntu0.3) ...
Selecting previously unselected package git.
Preparing to unpack .../git_1%3a1.9.1-1ubuntu0.3_amd64.deb ...
Unpacking git (1:1.9.1-1ubuntu0.3) ...
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
Setting up liberror-perl (0.17-1.1) ...
Setting up git-man (1:1.9.1-1ubuntu0.3) ...
Setting up git (1:1.9.1-1ubuntu0.3) ...
veena@veena-PC:~/github$ git clone git@github.com:MDShahrouq/helloworld.git
Cloning into 'helloworld'...
The authenticity of host 'github.com (192.30.253.112)' can't be established.
RSA key fingerprint is 16:27:ac:a5:76:28:2d:36:63:1b:56:4d:eb:df:a6:48.
Are you sure you want to continue connecting (yes/no)? yes
Warning: Permanently added 'github.com,192.30.253.112' (RSA) to the list of known hosts.
Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
veena@veena-PC:~/github$  sudo apt-get install xclip
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages were automatically installed and are no longer required:
  account-plugin-windows-live libntdb1 libupstart1 python-ntdb
Use 'apt-get autoremove' to remove them.
The following NEW packages will be installed:
  xclip
0 upgraded, 1 newly installed, 0 to remove and 26 not upgraded.
Need to get 17.0 kB of archives.
After this operation, 72.7 kB of additional disk space will be used.
Get:1 http://in.archive.ubuntu.com/ubuntu/ trusty/universe xclip amd64 0.12+svn84-4 [17.0 kB]
Fetched 17.0 kB in 8s (2,018 B/s)
Selecting previously unselected package xclip.
(Reading database ... 166686 files and directories currently installed.)
Preparing to unpack .../xclip_0.12+svn84-4_amd64.deb ...
Unpacking xclip (0.12+svn84-4) ...
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
Setting up xclip (0.12+svn84-4) ...
veena@veena-PC:~/github$ xclip -sel clip < root123.pub
bash: root123.pub: No such file or directory
veena@veena-PC:~/github$ clear

veena@veena-PC:~/github$ xclip -sel clip < root123.pub
bash: root123.pub: No such file or directory
veena@veena-PC:~/github$ git config --global user.name mdshahrouq
veena@veena-PC:~/github$ git config --global user.email mdshah1994@gmail.com
veena@veena-PC:~/github$ git clone git@github.com:MDShahrouq/helloworld.git
Cloning into 'helloworld'...
Warning: Permanently added the RSA host key for IP address '192.30.253.113' to the list of known hosts.
Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
veena@veena-PC:~/github$ git clone https://github.com/Aiffin/PROJECT.gi
Cloning into 'PROJECT.gi'...
Username for 'https://github.com': mdshahrouq
Password for 'https://mdshahrouq@github.com': 
remote: Repository not found.
fatal: repository 'https://github.com/Aiffin/PROJECT.gi/' not found
veena@veena-PC:~/github$ git clone https://github.com/MDShahrouq/helloworld.git
Cloning into 'helloworld'...
remote: Counting objects: 103, done.
remote: Total 103 (delta 0), reused 0 (delta 0), pack-reused 103
Receiving objects: 100% (103/103), 13.01 KiB | 0 bytes/s, done.
Resolving deltas: 100% (39/39), done.
Checking connectivity... done.
veena@veena-PC:~/github$ clear

veena@veena-PC:~/github$ ssh-keygen -t rsa -b 4096 -C mdshah1994@gmail.com
Generating public/private rsa key pair.
Enter file in which to save the key (/home/veena/.ssh/id_rsa): 
Enter passphrase (empty for no passphrase): 
Enter same passphrase again: 
Your identification has been saved in /home/veena/.ssh/id_rsa.
Your public key has been saved in /home/veena/.ssh/id_rsa.pub.
The key fingerprint is:
ec:fd:3f:19:ac:b0:d0:8b:14:bf:4f:79:52:d6:d8:1f mdshah1994@gmail.com
The key's randomart image is:
+--[ RSA 4096]----+
|                 |
|                 |
|                 |
|       ..      + |
|        S+   .+Eo|
|       .o.+  +o o|
|       ..o.=+..o.|
|        . +o.oo  |
|           .o... |
+-----------------+
veena@veena-PC:~/github$ eval "$(ssh-agent -s)"
Agent pid 7017
veena@veena-PC:~/github$ ssh-add ~/.ssh/id_rsa
Enter passphrase for /home/veena/.ssh/id_rsa: 
Identity added: /home/veena/.ssh/id_rsa (/home/veena/.ssh/id_rsa)
veena@veena-PC:~/github$  sudo apt-get install xclip
Reading package lists... Done
Building dependency tree       
Reading state information... Done
xclip is already the newest version.
The following packages were automatically installed and are no longer required:
  account-plugin-windows-live libntdb1 libupstart1 python-ntdb
Use 'apt-get autoremove' to remove them.
0 upgraded, 0 newly installed, 0 to remove and 26 not upgraded.
veena@veena-PC:~/github$ xclip -sel clip < ~/.ssh/id_rsa.pub
veena@veena-PC:~/github$ git clone git@github.com:MDShahrouq/vanisha-honda.git
Cloning into 'vanisha-honda'...
remote: Counting objects: 418, done.
remote: Compressing objects: 100% (175/175), done.
remote: Total 418 (delta 248), reused 410 (delta 240), pack-reused 0
Receiving objects: 100% (418/418), 2.98 MiB | 166.00 KiB/s, done.
Resolving deltas: 100% (248/248), done.
Checking connectivity... done.
veena@veena-PC:~/github$ ls
helloworld  vanisha-honda
veena@veena-PC:~/github$ git clone git@github.com:MDShahrouq/pushtest.git
Cloning into 'pushtest'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.
Checking connectivity... done.
veena@veena-PC:~/github$ ls
helloworld  pushtest  vanisha-honda
veena@veena-PC:~/github$ cd pushtest/
veena@veena-PC:~/github/pushtest$ git remote add origin ^C
veena@veena-PC:~/github/pushtest$ git remote add origin git@github.com:MDShahrouq/pushtest.git
fatal: remote origin already exists.
veena@veena-PC:~/github/pushtest$ git branch
* master
veena@veena-PC:~/github/pushtest$ git commit -m "TEsting ADDED"
On branch master
Your branch is up-to-date with 'origin/master'.

Untracked files:
	.gitignore
	authtest/
	log/
	manage.py
	static/
	templates/

nothing added to commit but untracked files present
veena@veena-PC:~/github/pushtest$ git add .
veena@veena-PC:~/github/pushtest$ git commit -m "TEsting ADDED"
[master 9f9e1f8] TEsting ADDED
 21 files changed, 382 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 authtest/__init__.py
 create mode 100644 authtest/settings.py
 create mode 100644 authtest/urls.py
 create mode 100644 authtest/wsgi.py
 create mode 100644 log/__init__.py
 create mode 100644 log/admin.py
 create mode 100644 log/apps.py
 create mode 100644 log/forms.py
 create mode 100644 log/migrations/__init__.py
 create mode 100644 log/models.py
 create mode 100644 log/tests.py
 create mode 100644 log/urls.py
 create mode 100644 log/views.py
 create mode 100755 manage.py
 create mode 100644 static/css/bootstrap.min.css
 create mode 100644 static/js/bootstrap.min.js
 create mode 100644 static/js/jquery.min.js
 create mode 100644 templates/base.html
 create mode 100644 templates/home.html
 create mode 100644 templates/login.html
veena@veena-PC:~/github/pushtest$ git push origin
warning: push.default is unset; its implicit value is changing in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the current behavior after the default changes, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

When push.default is set to 'matching', git will push local branches
to the remote branches that already exist with the same name.

In Git 2.0, Git will default to the more conservative 'simple'
behavior, which only pushes the current branch to the corresponding
remote branch that 'git pull' uses to update the current branch.

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Counting objects: 29, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (25/25), done.
Writing objects: 100% (28/28), 66.16 KiB | 0 bytes/s, done.
Total 28 (delta 0), reused 0 (delta 0)
^[[ATo git@github.com:MDShahrouq/pushtest.git
   d4bd9c3..9f9e1f8  master -> master
veena@veena-PC:~/github/pushtest$ git push origin master 
	Everything up-to-date
veena@veena-PC:~/github/pushtest$ 

