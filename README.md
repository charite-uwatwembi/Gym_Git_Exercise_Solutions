# Bundle 1

## Exercise 1

```bash 

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (master)
$ git init
Initialized empty Git repository in D:/Study/Studies/the_gym/GIT-EXERCISES/.git/

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (master)
$ git branch -m main

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git add .

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git commit -m "Initial commit"  
On branch main

Initial commit

nothing to commit (create/copy files and use "git add" to track)    

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git add .

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git commit -m "Initial commit"
[main (root-commit) 37b5475] Initial commit
 1 file changed, 3 insertions(+)  
 create mode 100644 README.md     

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git remote add origin https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions.git 

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 244 bytes | 122.00 KiB/s, done.        
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions.git
 * [new branch]      main -> main 
branch 'main' set up to track 'origin/main'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git checkout -b dev
Switched to a new branch 'dev'

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git push -u origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:      
remote:      https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions/pull/new/dev
remote:
To https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions.git
 * [new branch]      dev -> dev   
branch 'dev' set up to track 'origin/dev'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git checkout -b test
Switched to a new branch 'test'

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (test)
$ git push -u origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:     
remote:      https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions/pull/new/test
remote:
To https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions.git
 * [new branch]      test -> test 
branch 'test' set up to track 'origin/test'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (test)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git branch -d test
Deleted branch test (was 37b5475).

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git push -u origin dev
Everything up-to-date
branch 'dev' set up to track 'origin/dev'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git branch -D test
error: branch 'test' not found.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git push -u origin --delete test
To https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions.git
 - [deleted]         test

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$
```

## Exercise 2

```bash

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ ls
Home.html  README.md

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash
No local changes to save

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash list

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash
Saved working directory and index state WIP on dev: 728ae20 update readme

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
y/Studies/the_gym/GIT-EXERCISES (dev)
$ git add  about.html

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash
Saved working directory and index state WIP on dev: 728ae20 update readme
Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash list
stash@{0}: WIP on dev: 728ae20 update readme
stash@{1}: WIP on dev: 728ae20 update readme

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git add  team.html

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash
Saved working directory and index state WIP on dev: 728ae20 update readme

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash list
stash@{0}: WIP on dev: 728ae20 update readme
stash@{1}: WIP on dev: 728ae20 update readme
stash@{2}: WIP on dev: 728ae20 update readme

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)       
        new file:   team.html

Dropped stash@{0} (d5cc9719e36562d64ad0aee31e8ac829e6af3963)

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash
Saved working directory and index state WIP on dev: 728ae20 update readme

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)       
        new file:   about.html

Dropped stash@{1} (4776e47a58cb5b76d85a06cd89a2f2f2ff884c8a)

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)       
        new file:   Home.html
        new file:   about.html

Dropped stash@{1} (3b1293823446ebcb3e1f2428689f8dd87cad7623)

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash list
stash@{0}: WIP on dev: 728ae20 update readme

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)       
        new file:   Home.html
        new file:   about.html
        new file:   team.html

Dropped stash@{0} (9d67667f8e89e90b40cac9f0a908f929c5913b32)

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git add .

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git commit -m "Add home and about pages"
[dev 8295846] Add home and about pages
 3 files changed, 37 insertions(+)
 create mode 100644 Home.html
 create mode 100644 about.html
 create mode 100644 team.html

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 752 bytes | 188.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0      
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions.git
   728ae20..8295846  dev -> dev

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git stash list

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git reset --hard
HEAD is now at 8295846 Add home and about pages

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$```

# Bundle 2

## Exercise 1
