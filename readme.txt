Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.
Creating a new branch is quick and simple.
Add something.
<<<<<<< HEAD
Creating a new branch is quickd & simple.

==$ git merge --no-ff -m"merge with no-ff" dev
Auto-merging readme.txt
CONFLICT (content): Merge conflict in readme.txt
Automatic merge failed; fix cGit is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.
<<<<<<< HEAD
Creating a new branch is quickd & simple.

==$ git merge --no-ff -m"merge with no-ff" dev
Auto-merging readme.txt
CONFLICT (content): Merge conflict in readme.txt
Automatic merge failed; fix conflicts and then commit the result.=====
Creating a new branch is quick.
Add something.
>>>>>>> devonflicts and then commit the result.=====
Creating a new branch is quick.
Add something.
>>>>>>> dev
