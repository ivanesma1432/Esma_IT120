
acer@DESKTOP-5STK8MT MINGW64 ~
$ cd Desktop

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop
$ mkdir Esma_IT120_Act1

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop
$ cd Esma_IT120_Act1

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1
$ git init
Initialized empty Git repository in C:/Users/acer/Desktop/Esma_IT120_Act1/.git/

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git remote add origin https://github.com/ivanesma1432/Esma_IT120.git

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ touch Profile.txt Education.txt Background.txt Readme.txt Test.py

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git add .

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git commit -m "Initial commit with all files"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'acer@DESKTOP-5STK8MT.(none)')

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git config --global user.name "Ivan Adrian France E.
> git config --global user.name "ivanesma1432"
> git cinfig --global user.name "Ivan Esma"
> q
> ^C

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git config --global user.email "ivanadrianfrance.esma@csucc.edu.ph"

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git config --global user.name "Ivan E."

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=schannel
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=ivanadrianfrance.esma@csucc.edu.ph
user.name=Ivan E.
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/ivanesma1432/Esma_IT120.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git commit -m "Initial commit with all files"
[master (root-commit) 4c14369] Initial commit with all files
 5 files changed, 15 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$  git remote -v
origin  https://github.com/ivanesma1432/Esma_IT120.git (fetch)
origin  https://github.com/ivanesma1432/Esma_IT120.git (push)

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git push origin master


acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 673 bytes | 84.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ivanesma1432/Esma_IT120.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git checkout -b Esma_B1
Switched to a new branch 'Esma_B1'

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B1)
$ git branch
* Esma_B1
  master

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B1)
$ git add Profile.txt

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B1)
$  git commit -m "Amend: added Birth of Place, Religion, Father's Occupation, Mother's Name, Occupation"
[Esma_B1 f1a13b9] Amend: added Birth of Place, Religion, Father's Occupation, Moth
er's Name, Occupation
 1 file changed, 7 insertions(+)

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B1)
$ git push origin Esma_B1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 522 bytes | 104.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Esma_B1' on GitHub by visiting:
remote:      https://github.com/ivanesma1432/Esma_IT120/pull/new/Esma_B1
remote:
To https://github.com/ivanesma1432/Esma_IT120.git
 * [new branch]      Esma_B1 -> Esma_B1

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B1)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git checkout -b Esma_B2
Switched to a new branch 'Esma_B2'

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$ git add Background.txt

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$ git commit -m "Amend: updated Education.txt with details"
On branch Esma_B2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Education.txt

no changes added to commit (use "git add" and/or "git commit -a")

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$ git push origin Esma_B2
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'Esma_B2' on GitHub by visiting:
remote:      https://github.com/ivanesma1432/Esma_IT120/pull/new/Esma_B2
remote:
To https://github.com/ivanesma1432/Esma_IT120.git
 * [new branch]      Esma_B2 -> Esma_B2

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$ git add Background.txt

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$  git commit -m "Amend: updated Education.txt with details"
On branch Esma_B2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Education.txt

no changes added to commit (use "git add" and/or "git commit -a")

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$  git commit -m "Amend: updated Education.txt with details"
On branch Esma_B2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Education.txt

no changes added to commit (use "git add" and/or "git commit -a")

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$ git add Education.txt

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$  git commit -m "Amend: updated Education.txt with details"
[Esma_B2 4e1c599] Amend: updated Education.txt with details
 1 file changed, 4 insertions(+)

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$ git push origin Esma_B2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 464 bytes | 154.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/ivanesma1432/Esma_IT120.git
   4c14369..4e1c599  Esma_B2 -> Esma_B2

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B2)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git checkout -b Esma_B3
Switched to a new branch 'Esma_B3'

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B3)
$ git add Background.txt

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B3)
$ git rm Test.py
rm 'Test.py'

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B3)
$ git commit -m "Amend: updated Background.txt and removed Test.py"
[Esma_B3 4debe14] Amend: updated Background.txt and removed Test.py
 2 files changed, 4 insertions(+), 4 deletions(-)
 delete mode 100644 Test.py

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B3)
$ git push origin Esma_B3
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 384 bytes | 192.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Esma_B3' on GitHub by visiting:
remote:      https://github.com/ivanesma1432/Esma_IT120/pull/new/Esma_B3
remote:
To https://github.com/ivanesma1432/Esma_IT120.git
 * [new branch]      Esma_B3 -> Esma_B3

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B3)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (master)
$ git checkout -b Esma_B4
Switched to a new branch 'Esma_B4'

acer@DESKTOP-5STK8MT MINGW64 ~/Desktop/Esma_IT120_Act1 (Esma_B4)
$
