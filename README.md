# Gym-Git-Exercise-Solutions
```bash
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

  
Exercise 2
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
```
