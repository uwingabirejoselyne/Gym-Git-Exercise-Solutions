# Git exercise
# bundle 01
# exercise 01

''' Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises
$ git init
Initialized empty Git repository in D:/Ojemba_exercises/.git/

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (master)
$ git branch -m main

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git remote add origin https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git add .

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git commit -m "my first exercises"
[main (root-commit) 342f54b] my first exercises
 2 files changed, 12 insertions(+)
 create mode 100644 README.md
 create mode 100644 index.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ ls
index.html  README.md

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ echo "the saint" > index2.txt

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git add .
warning: LF will be replaced by CRLF in index2.txt.
The file will have its original line endings in your working directory

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git commit -m "second commit"
[main 00e4fad] second commit
 1 file changed, 1 insertion(+)
 create mode 100644 index2.txt

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git remote add origin https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git push -u origin
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main


Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git push --set-upstream origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 912 bytes | 152.00 KiB/s, done.
Total 7 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git branch dev

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout -b test
Switched to a new branch 'test'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (test)
$ git checkout dev
Switched to branch 'dev'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git branch -d test
Deleted branch test (was 00e4fad).
'''

# Git exercise
# bundle 01
# exercise 02

'''
Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ touch home.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git add home.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 00e4fad second commit

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 00e4fad second commit
stash@{1}: WIP on dev: 00e4fad second commit
stash@{2}: WIP on dev: 00e4fad second commit
stash@{3}: WIP on dev: 00e4fad second commit
stash@{4}: WIP on dev: 00e4fad second commit

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ touch about.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git add about.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 00e4fad second commit

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 00e4fad second commit
stash@{1}: WIP on dev: 00e4fad second commit
stash@{2}: WIP on dev: 00e4fad second commit
stash@{3}: WIP on dev: 00e4fad second commit
stash@{4}: WIP on dev: 00e4fad second commit
stash@{5}: WIP on dev: 00e4fad second commit

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ touch team.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git add team.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 00e4fad second commit

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 00e4fad second commit
stash@{1}: WIP on dev: 00e4fad second commit
stash@{2}: WIP on dev: 00e4fad second commit
stash@{3}: WIP on dev: 00e4fad second commit
stash@{4}: WIP on dev: 00e4fad second commit
stash@{5}: WIP on dev: 00e4fad second commit
stash@{6}: WIP on dev: 00e4fad second commit
(END)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
git stash list
bash: ggit: command not found

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 00e4fad second commit
stash@{1}: WIP on dev: 00e4fad second commit
stash@{2}: WIP on dev: 00e4fad second commit
stash@{3}: WIP on dev: 00e4fad second commit
stash@{4}: WIP on dev: 00e4fad second commit
stash@{5}: WIP on dev: 00e4fad second commit
stash@{6}: WIP on dev: 00e4fad second commit
:

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (fd750d9834ac80bad36ea27c2253824efe99c1c3)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash pop stash@{2}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{2} (7a4041152f4b423b3d68ed05a28c31e1edfa9830)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git add .

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git commit -m 'save change'
[dev f018416] save change
 2 files changed, 24 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev


Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$  git push --set-upstream origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 597 bytes | 119.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (4a0497b2c89ee4c841dc1b89e0e3c5f9c9bc98a0)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git log
commit f0184163b2ccfc6a18560caff78abeb7e8ef1bd5 (HEAD -> dev, origin/dev)
Author: Joselyne Uwingabire <uwingajoselyne@gmail.com>
Date:   Sun May 14 17:30:46 2023 +0200

    save change

commit 00e4fad81f0a89725f5f5a3583798a05ec17b3c9 (origin/main, main)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git reset --hard f0184163b2ccfc6a18560caff78abeb7e8ef1bd5
'''

# Git exercise
# bundle 02
# exercise 01

'''
Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git branch ft/bundle-2 

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (dev)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ touch services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ git add services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ git commit -m 'some changes on services page'
[ft/bundle-2 35a02c6] some changes on services page
 1 file changed, 12 insertions(+)
 create mode 100644 services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ git push -u origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 489 bytes | 97.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

'''

# Git exercise
# bundle 02
# exercise 02

'''
Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git branch -d ft/service-redesign
Deleted branch ft/service-redesign (was 00e4fad).

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git pull origin main
remote: Enumerating objects: 2, done.
remote: Counting objects: 100% (2/2), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (2/2), 1.22 KiB | 21.00 KiB/s, done.
From https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
   00e4fad..19554e4  main       -> origin/main
Updating 00e4fad..19554e4
Fast-forward
 README.md     | 239 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 about.html    |  12 +++
 home.html     |  12 +++
 services.html |  12 +++
 4 files changed, 275 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git add sercices.html
fatal: pathspec 'sercices.html' did not match any files

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git add services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git commit -m 'Added paragraph'
[ft/service-redesign a98242f] Added paragraph
 1 file changed, 1 insertion(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git push -u origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 588 bytes | 84.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git pull origin main
remote: Enumerating objects: 1, done.
Unpacking objects: 100% (1/1), 642 bytes | 8.00 KiB/s, done.

remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
From https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
   19554e4..25b8ca9  main       -> origin/main
Updating 19554e4..25b8ca9
Fast-forward
 services.html | 1 +
 1 file changed, 1 insertion(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git add services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git commit -m 'Added header'
[main de0e16e] Added header
 1 file changed, 1 insertion(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git push -u origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 394 bytes | 131.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
   25b8ca9..de0e16e  main -> main
branch 'main' set up to track 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git add services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git commit -m 'some Change'
[ft/service-redesign 8d08239] some Change
 1 file changed, 1 insertion(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git push -u origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 460 bytes | 115.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
   a98242f..8d08239  ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git chechout ft/service-redesign
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git pull
Already up to date.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git add services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git commit -m "Added new changes to service.html"
[ft/service-redesign 8bc1ed1] Added new changes to service.html
 1 file changed, 1 insertion(+), 1 deletion(-)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git push -u  origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 330 bytes | 66.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
   8d08239..8bc1ed1  ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git  diff main..ft/service-redesign
diff --git a/services.html b/services.html
index 7dff09f..188414a 100644
--- a/services.html
+++ b/services.html
@@ -9,6 +9,6 @@
 <body>
     <h1> Service Page</h1>

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git diff --color-words main..ft/service-redesign
diff --git a/services.html b/services.html
index 7dff09f..188414a 100644
--- a/services.html
+++ b/services.html
@@ -9,6 +9,6 @@
<body>
    <h1> Service Page</h1>

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git merge ft/service-redesign
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main|MERGING)
$ git add services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main|MERGING)
$ git commit -m 'solved conflicts'
[main 752d047] solved conflicts

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git push -u origin main
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 225 bytes | 16.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
   de0e16e..752d047  main -> main
branch 'main' set up to track 'origin/main'.

'''