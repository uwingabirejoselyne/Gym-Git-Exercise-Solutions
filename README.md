# Git exercise
# bundle 01
# exercise 01

```bash
Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises
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
```

# Git exercise
# bundle 01
# exercise 02

```bash
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
```

# Git exercise
# bundle 02
# exercise 01

```bash
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
```
# Git exercise
# bundle 02
# exercise 02

```bash

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git add services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git commit -m 'changed'
[main e100cc3] changed
 1 file changed, 1 insertion(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 453 bytes | 151.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
   924743e..e100cc3  main -> main

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git diff main..ft/service-redesign
diff --git a/services.html b/services.html
index 8aa50a0..e96d5d2 100644
--- a/services.html
+++ b/services.html
@@ -10,6 +10,6 @@
     <h1> Service Page</h1>
     <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Provident ipsa voluptatibus quia quidem perferendis vitae culpa dolorem officiis quam molestias modi nulla commodi i
Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign|MERGING)
$ git add services.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign|MERGING)
$ git commit -m "Resolve conflicts between main and ft/service-redesign"
[ft/service-redesign 5d7f58f] Resolve conflicts between main and ft/service-redesign

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git push -u ft/service-redesign
fatal: 'ft/service-redesign' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 253 bytes | 84.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
   da8726c..5d7f58f  ft/service-redesign -> ft/service-redesign

Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 253 bytes | 84.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
   da8726c..5d7f58f  ft/service-redesign -> ft/service-redesign

```
# Git exercise
# bundle 03
# exercise 01

```bash
Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/team-page)
$ touch team.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/team-page)
$ git add team.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/team-page)
$ git commit -m 'team page'
[ft/team-page a0468ee] team page
 1 file changed, 1 insertion(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 589 bytes | 28.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions/pull/new/ft/team-page
remote:
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/contact-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/team-page)
$ git log
commit a0468ee09f79e15caaebc1b197d01c434f0b7684 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Joselyne Uwingabire <uwingajoselyne@gmail.com>
Date:   Wed May 17 09:53:03 2023 +0200

    team page

commit afbfeb18904fc9e206bedb5ab65c27a2b88c67d5 (origin/main, main, ft/contact-page)
Author: Joselyne Uwingabire <uwingajoselyne@gmail.com>
Date:   Tue May 16 21:49:36 2023 +0200

    Updated README

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/contact-page)
$ git cherry-pick a0468ee09f79e15caaebc1b197d01c434f0b7684
[ft/contact-page 06a87df] team page
 Date: Wed May 17 09:53:03 2023 +0200
 1 file changed, 1 insertion(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/contact-page)
$ touch contact.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/contact-page)
$ git add contact.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/contact-page)
$ git commit -m 'creation contact page'
[ft/contact-page a84d8bc] creation contact page
 1 file changed, 1 insertion(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.02 KiB | 148.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions/pull/new/ft/contact-page
remote:
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ touch faq.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ git add faq.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ git commit -m 'creation of faq page'
[ft/faq-page f7d03b9] creation of faq page
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 478 bytes | 159.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions/pull/new/ft/faq-page
remote:
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ git log
commit f7d03b9667557c8cb3ca2c725cd4e5c494e107d8 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Joselyne Uwingabire <uwingajoselyne@gmail.com>
Date:   Wed May 17 10:08:08 2023 +0200

    creation of faq page

commit a84d8bc3f20715c0051daa4f7cb7b218078719f0 (origin/ft/contact-page, ft/contact-page)
Author: Joselyne Uwingabire <uwingajoselyne@gmail.com>
Date:   Wed May 17 10:03:54 2023 +0200

    creation contact page

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ git revert f7d03b9667557c8cb3ca2c725cd4e5c494e107d8
[ft/faq-page a4e0f82] Revert "creation of faq page"
 1 file changed, 12 deletions(-)
 delete mode 100644 faq.html

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ git revert f7d03b9667557c8cb3ca2c725cd4e5c494e107d8
On branch ft/faq-page
nothing to commit, working tree clean

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ git status
On branch ft/faq-page
nothing to commit, working tree clean

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 265 bytes | 66.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
   f7d03b9..a4e0f82  ft/faq-page -> ft/faq-page
```
# Git exercise
# bundle 03
# exercise 02
```bash
Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git add .

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git commit -m 'Adding paragraph'
[main 869d29a] Adding paragraph
 1 file changed, 1 insertion(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 582 bytes | 145.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
   83e2ace..869d29a  main -> main

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout ft/home-page-redesign branch
error: pathspec 'branch' did not match any file(s) known to git

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/home-page-redesign)
$ git status
On branch ft/home-page-redesign
nothing to commit, working tree clean

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/home-page-redesign)
$ git add .

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/home-page-redesign)
$ git commit -m 'Adding footer'
[ft/home-page-redesign ce8516f] Adding footer
 1 file changed, 3 insertions(+)

Joselyne@DESKTOP-7C7CM9M MINGW64 /d/Ojemba_exercises (ft/home-page-redesign)
$ git push origin ft/home-page-redesign
Enumerating objects: 17, done.
Counting objects: 100% (17/17), done.
Delta compression using up to 2 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (13/13), 1.73 KiB | 443.00 KiB/s, done.
Total 13 (delta 8), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (8/8), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote:
To https://github.com/uwingabirejoselyne/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
```



# Git exercise
# bundle 04
# exercise 01

```bash
```






# Git exercise
# bundle 04
# exercise 02
```bash
```



# Git exercise
# bundle 05
# exercise 01
```bash
```


# Git exercise
# bundle 05
# exercise 02
```bash

```


# Git exercise
# bundle 04
# exercise 01
```bash
```


# Git exercise
# bundle 06
# exercise 02
```bash
```