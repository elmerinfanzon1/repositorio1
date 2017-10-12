# Doc1

elmer@sa3ubuntu:~/repositori2$ git remove -v
git: 'remove' is not a git command. See 'git --help'.

Did you mean this?
	remote
elmer@sa3ubuntu:~/repositori2$ git remote add upstream https://github.com/elmerinfanzon/repositorio
elmer@sa3ubuntu:~/repositori2$ git remote add upstream https://github.com/elmerinfanzon1/repositorio
fatal: remote upstream already exists.
elmer@sa3ubuntu:~/repositori2$ git remote -v
origin	https://github.com/elmerinfanzon1/repositori2.git (fetch)
origin	https://github.com/elmerinfanzon1/repositori2.git (push)
upstream	https://github.com/elmerinfanzon/repositorio (fetch)
upstream	https://github.com/elmerinfanzon/repositorio (push)
elmer@sa3ubuntu:~/repositori2$ git checkout -b feature-Thirdpar-rama
Switched to a new branch 'feature-Thirdpar-rama'
elmer@sa3ubuntu:~/repositori2$ git push origen feature-Thirdpar
error: src refspec feature-Thirdpar does not match any.
error: failed to push some refs to 'origen'
elmer@sa3ubuntu:~/repositori2$ git push orig1n feature-Thirdpar
error: src refspec feature-Thirdpar does not match any.
error: failed to push some refs to 'orig1n'
elmer@sa3ubuntu:~/repositori2$ git push origin feature-Thirdpar
error: src refspec feature-Thirdpar does not match any.
error: failed to push some refs to 'https://github.com/elmerinfanzon1/repositori2.git'
elmer@sa3ubuntu:~/repositori2$ git pull -r upstream master
Username for 'https://github.com': elmerinfanzon1
Password for 'https://elmerinfanzon1@github.com': 
remote: Repository not found.
fatal: repository 'https://github.com/elmerinfanzon/repositorio/' not found
elmer@sa3ubuntu:~/repositori2$ git checkout -b feature-Thirdpar-rama
Switched to a new branch 'feature-Thirdpar-rama'
elmer@sa3ubuntu:~/repositori2$ git push origin feature-Thirdpar
error: src refspec feature-Thirdpar does not match any.
error: failed to push some refs to 'https://github.com/elmerinfanzon1/repositori2.git'
elmer@sa3ubuntu:~/repositori2$ git clone https://github.com/ricardojauregui/ShareDocuments
Cloning into 'ShareDocuments'...
remote: Counting objects: 6, done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 3 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
Checking connectivity... done.
elmer@sa3ubuntu:~/repositori2$ ls
ShareDocuments
elmer@sa3ubuntu:~/repositori2$ cd ShareDocuments
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git checkout -b Thard
Switched to a new branch 'Thard'
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git status
On branch Thard
nothing to commit, working directory clean
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git status
On branch Thard
nothing to commit, working directory clean
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> Thard

elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git checkout RJDOC
Branch RJDOC set up to track remote branch RJDOC from origin.
Switched to a new branch 'RJDOC'
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git remote -v
origin	https://github.com/ricardojauregui/ShareDocuments (fetch)
origin	https://github.com/ricardojauregui/ShareDocuments (push)
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git branch
* RJDOC
  Thard
  master
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git remote add upstream https://github.com/ricardojauregui/ShareDocuments
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git remote -v
origin	https://github.com/ricardojauregui/ShareDocuments (fetch)
origin	https://github.com/ricardojauregui/ShareDocuments (push)
upstream	https://github.com/ricardojauregui/ShareDocuments (fetch)
upstream	https://github.com/ricardojauregui/ShareDocuments (push)
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git checkout RJDOC
Already on 'RJDOC'
Your branch is up-to-date with 'origin/RJDOC'.
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git pull origin RJDOC
From https://github.com/ricardojauregui/ShareDocuments
 * branch            RJDOC      -> FETCH_HEAD
Already up-to-date.
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ git pull origin RJDOC
From https://github.com/ricardojauregui/ShareDocuments
 * branch            RJDOC      -> FETCH_HEAD
Already up-to-date.
elmer@sa3ubuntu:~/repositori2/ShareDocuments$ cd ..
elmer@sa3ubuntu:~/repositori2$ 
elmer@sa3ubuntu:~/repositori2$ cd..
cd..: command not found
elmer@sa3ubuntu:~/repositori2$ cd ..
elmer@sa3ubuntu:~$ cd repositorio1
elmer@sa3ubuntu:~/repositorio1$ ls
Untitled Document
elmer@sa3ubuntu:~/repositorio1$ git clone https://github.com/elmerinfanzon1/Doc1.git
Cloning into 'Doc1'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Checking connectivity... done.
elmer@sa3ubuntu:~/repositorio1$ 

