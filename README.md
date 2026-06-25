# Gym-Git-Exercise-Solutions
```bash
Exercie 1-Bundle 1
Nettie King@Nettie-Win MINGW64 ~
$ mkdir Farida

Nettie King@Nettie-Win MINGW64 ~
$ cd Farida

Nettie King@Nettie-Win MINGW64 ~/Farida
$ git init
Initialized empty Git repository in C:/Users/user/Farida/.git/

Nettie King@Nettie-Win MINGW64 ~/Farida (master)
$ touch index.html

Nettie King@Nettie-Win MINGW64 ~/Farida (master)
$ touch doc.css

Nettie King@Nettie-Win MINGW64 ~/Farida (master)
$ echo "Hello World" > file.txt

Nettie King@Nettie-Win MINGW64 ~/Farida (master)
$ git branch

Nettie King@Nettie-Win MINGW64 ~/Farida (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        doc.css
        file.txt
        index.html

nothing added to commit but untracked files present (use "git add" to track)

Nettie King@Nettie-Win MINGW64 ~/Farida (master)
$ git branch -m main

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git add --all
warning: in the working copy of 'file.txt', LF will be replaced by CRLF the next time Git touches it

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git commit -m "First commit"
[main (root-commit) 19077f1] First commit
 3 files changed, 1 insertion(+)
 create mode 100644 doc.css
 create mode 100644 file.txt
 create mode 100644 index.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git remote add origin https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git remote -v
origin  https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git (push)

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git push -u origin main
fatal: unable to access 'https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git/': Recv failure: Connection was reset

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git push -u origin main
To https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git pull origin main --rebase
fatal: unable to access 'https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git/': Recv failure: Connection was reset

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git pull origin main --rebase
fatal: unable to access 'https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git/': Recv failure: Connection was reset

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git pull origin main --rebase
fatal: unable to access 'https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git/': Recv failure: Connection was reset

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git ls-remote origin
fatal: unable to access 'https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git/': Recv failure: Connection was reset

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git pull origin main --rebase
fatal: unable to access 'https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git/': Recv failure: Connection was reset

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git pull origin main --rebase
fatal: unable to access 'https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git/': Recv failure: Connection was reset
Nettie King@Nettie-Win MINGW64 ~
$ cd ~/Farida

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git status
On branch main
nothing to commit, working tree clean

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git pull origin main --rebase
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (6/6), 2.58 KiB | 125.00 KiB/s, done.
From https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
Successfully rebased and updated refs/heads/main.

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git status
On branch main
nothing to commit, working tree clean

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git branch dev

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git branch
  dev
* main

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git switch dev
Switched to branch 'dev'

Nettie King@Nettie-Win MINGW64 ~/Farida (dev)
$ git branch test

Nettie King@Nettie-Win MINGW64 ~/Farida (dev)
$ git branch -d test
Deleted branch test (was d32d6fd).

Nettie King@Nettie-Win MINGW64 ~/Farida (dev)
$ git branch
* dev
  main

  
Exercise 2-Bundle 1
Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ ls
doc.css  file.txt  home.hmtl  index.html  README.md

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ rm home.hmtl

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ touch home.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git stash
No local changes to save

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git stash -u
Saved working directory and index state WIP on main: d32d6fd First commit

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ touch about.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git stash -u
Saved working directory and index state WIP on main: d32d6fd First commit

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ touch team.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git stash -u
Saved working directory and index state WIP on main: d32d6fd First commit

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git stash list
stash@{0}: WIP on main: d32d6fd First commit
stash@{1}: WIP on main: d32d6fd First commit
stash@{2}: WIP on main: d32d6fd First commit

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git stash pop
Already up to date.
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)
Dropped refs/stash@{0} (e72ff63c44f4cb3dab93de77e66372411ce4384a)

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git stash list
stash@{0}: WIP on main: d32d6fd First commit
stash@{1}: WIP on main: d32d6fd First commit

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git reset --hard HEAD~1
HEAD is now at 892ae14 Changes


Exercise1-Bundle2
Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git remote -v
origin  https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git (push)

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git log --onelin e
fatal: ambiguous argument 'e': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git log --oneline
892ae14 (HEAD -> main, origin/main, origin/HEAD) Changes
3a6153d First commit
91b2e48 Update README.md
400e0d0 Update README.md
c208118 Update README.md
ca49b53 Initial commit

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git branch ft/bundle-2

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ touch service.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git add service.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git commit -m "Updated with a new file"
[main 8601b6e] Updated with a new file
 1 file changed, 11 insertions(+)
 create mode 100644 service.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git branch
  dev
  ft/bundle-2
* main

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git push
Enumerating objects: 4, done.
Counting objects:  Counting objects:  Counting objects:  Counting objects: 1Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objectsCompressing objectsCompressing objectsCompressing objects: 100% (3/3), done.
Writing objects:  3Writing objects:  6Writing objects: 10Writing objects: 100% (3/3), 439 bytes | 439.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving dremote: Resolving dremote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
   892ae14..8601b6e  main -> main

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git push origin
Everything up-to-date
Nettie King@Nettie-Win MINGW64 ~/Farida (ft/bundle-2)
$ touch services.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/bundle-2)
$ code services.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/bundle-2)
$ git add services.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/bundle-2)
$ git commit -m "Add services"
[ft/bundle-2 fa45bf3] Add services
 1 file changed, 11 insertions(+)
 create mode 100644 services.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/bundle-2)
$ git push -u origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 435 bytes | 435.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
   892ae14..fa45bf3  ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

Exercise2-Bundle 2
Nettie King@Nettie-Win MINGW64 ~/Farida (ft/bundle-2)
$ git switch main
Switched to branch 'main'
Your branch is behind 'origin/main' by 1 commit, and can be fast-forwarded.
  (use "git pull" to update your local branch)

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git pull origin main
remote: Enumerating objects: 18, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (14/14), done.
remote: Total 14 (delta 9), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (14/14), 5.42 KiB | 75.00 KiB/s, done.
From github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
   8601b6e..56bfa7d  main       -> origin/main
Updating 892ae14..56bfa7d
Fast-forward
 README.md     | 96 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++--
 service.html  | 11 +++++++
 services.html | 11 +++++++
 3 files changed, 116 insertions(+), 2 deletions(-)
 create mode 100644 service.html
 create mode 100644 services.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign)
$ git add service.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign)
$ git commit -m "Update in services"
On branch ft/service-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign)
$ git add services.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign)
$ git commit -m "Update in services"
[ft/service-redesign 09c7a55] Update in services
 1 file changed, 1 insertion(+)

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign)
$ git push -u origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 346 bytes | 346.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: 
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote: 
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git add services.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git commit -m "Update on main branch"
[main fa570b5] Update on main branch
 1 file changed, 1 insertion(+)

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
   56bfa7d..fa570b5  main -> main

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign)
$ git diff main
diff --git a/services.html b/services.html
index 281e44d..507aa7f 100644
--- a/services.html
+++ b/services.html
@@ -7,6 +7,6 @@
 </head>
 <body>
     <p>Some content added</p>
-    <h1>Update in main</h1>
+    <h1>Our services are available.</h1>
 </body>
 </html>
\ No newline at end of file
(END)
diff --git a/services.html b/services.html
index 281e44d..507aa7f 100644
--- a/services.html
+++ b/services.html
@@ -7,6 +7,6 @@
 </head>
 <body>
     <p>Some content added</p>
-    <h1>Update in main</h1>
+    <h1>Our services are available.</h1>
 </body>
 </html>
\ No newline at end of file
(END)
+++ b/services.html
@@ -7,6 +7,6 @@
 </head>
 <body>
     <p>Some content added</p>
-    <h1>Update in main</h1>
+    <h1>Our services are available.</h1>
 </body>
 </html>
\ No newline at end of file

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign)
$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign|MERGING)
$ git add services.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign|MERGING)
$ git commit -m "Resolve conflicts"
[ft/service-redesign a0ed3cf] Resolve conflicts

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 356 bytes | 356.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
   09c7a55..a0ed3cf  ft/service-redesign -> ft/service-redesign

Exercise 2
Nettie King@Nettie-Win MINGW64 ~/Farida (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/faq-page)
$ touch faq.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/faq-page)
$ code faq.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/faq-page)
$ git add faq.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/faq-page)
$ git push -u origin ft/faq-page
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions/pull/new/ft/faq-page
remote: 
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/faq-page)
$ git commit -m "Add fq page"
[ft/faq-page 7dfe739] Add fq page
 2 files changed, 22 insertions(+)
 create mode 100644 contact.html
 create mode 100644 faq.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/faq-page)
$ git push -u origin ft/faq-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 516 bytes | 516.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
   a97ec60..7dfe739  ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/faq-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/team-page)
$ git revert 7163c89
hint: Waiting for your editor to close
[ft/team-page a500efc] Revert "Create my team"
 1 file changed, 11 deletions(-)
 delete mode 100644 team2.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 3, done.
Counting objects:  Counting objects:  Counting objects: 1Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objectsCompressing objectsCompressing objects: 100% (2/2), done.
Writing objects:  5Writing objects: 10Writing objects: 100% (2/2), 256 bytes | 256.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving dremote: Resolving dremote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
   7163c89..a500efc  ft/team-page -> ft/team-page

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/team-page)
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'
Your branch is up to date with 'origin/ft/faq-page'.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/faq-page)
$ git branch ft/home-page-redesign

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/faq-page)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ ls
doc.css
file.txt
home.html
index.html
README.md
service.html
services.html
team.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ code index.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git add index.html

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git commit -m "Update on main"
[main 36bb776] Update on main
 1 file changed, 11 insertions(+)

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git push
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/team-page)
$ git pull --rebase origin ft/team-page
From github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions
 * branch            ft/team-page -> FETCH_HEAD
Already up to date.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/team-page)
$ git switch main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git pull origin main
remote: Enumerating objects: 5, done.
remote: Counting obremote: Counting obremote: Counting obremote: Counting obremote: Counting obremote: Counting objects: 100% (5/5), done.
remote: Compressing objects:  33% (1/3remote: Compressing objects:  66% (2/3remote: Compressing objects: 100% (3/3remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: Unpacking objects: Unpacking objects: Unpacking objects: 100% (3/3), 2.19 KiB | 77.00 KiB/s, done.
From github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
   fa570b5..f98afce  main       -> origin/main
hint: Waiting for your editor to close
Merge made by the 'ort' strategy.
 README.md | 164 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 1 file changed, 164 insertions(+)

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git push origin main
Enumerating objects: 9, done.
Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects: 1Counting objects: 100% (8/8), done.
Delta compression using up to 12 threads
Compressing objectsCompressing objectsCompressing objectsCompressing objectsCompressing objectsCompressing objects: 100% (5/5), done.
Writing objects:  2Writing objects:  4Writing objects:  6Writing objects:  8Writing objects: 10Writing objects: 100% (5/5), 734 bytes | 183.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving dremote: Resolving dremote: Resolving dremote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
   f98afce..ee06483  main -> main

Nettie King@Nettie-Win MINGW64 ~/Farida (main)
$ git switch ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/home-page-redesign)
$ ls
contact.html
doc.css
faq.html
file.txt
home.html
index.html
README.md
service.html
services.html
team.html
team2.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/home-page-redesign)
$ touch home2.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/home-page-redesign)
$ code home2.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/home-page-redesign)
$ git add home2.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/home-page-redesign)
$ git commit -m "Up
date home page"
[ft/home-page-redesign 3315f1b] Update home page
 1 file changed, 11 insertions(+)
 create mode 100644 home2.html

Nettie King@Nettie-Win MINGW64 ~/Farida (ft/home-page-redesign)
$ git push
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Nettie King@Nettie-Win MINGW64 ~/Farida (ft/home-page-redesign)
$ git push origin ft/home-page-redesign
Enumerating objects: 11, done.
Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects:  Counting objects: 1Counting objects: 100% (11/11), done.
Delta compression using up to 12 threads
Compressing objectsCompressing objectsCompressing objectsCompressing objectsCompressing objectsCompressing objectsCompressing objectsCompressing objectsCompressing objectsCompressing objectsCompressing objects: 100% (10/10), done.
Writing objects:  1Writing objects:  2Writing objects:  3Writing objects:  4Writing objects:  5Writing objects:  6Writing objects:  7Writing objects:  8Writing objects:  9Writing objects: 10Writing objects: 100% (10/10), 1.04 KiB | 118.00 KiB/s, done.
Total 10 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving dremote: Resolving dremote: Resolving dremote: Resolving dremote: Resolving dremote: Resolving dremote: Resolving dremote: Resolving deltas: 100% (6/6), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote: 
To github.com:FaridaKINGUELEOUA/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
```
