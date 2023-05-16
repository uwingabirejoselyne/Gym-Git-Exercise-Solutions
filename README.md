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

#


Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ touch services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ git add .

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ git commit -m 'creation of services.html'
[ft/bundle-2 1aae232] creation of services.html
 2 files changed, 13 insertions(+), 278 deletions(-)
 rewrite services.html (70%)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ git push -u origin t/bundle-2
error: src refspec t/bundle-2 does not match any
error: failed to push some refs to 'https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/bundle-2)
$ git push -u origin ft/bundle-2
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 556 bytes | 185.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.
