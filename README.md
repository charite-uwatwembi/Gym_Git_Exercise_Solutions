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

```bash

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        service.html

no changes added to commit (use "git add" and/or "git commit -a")

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/bundle-2)
$ git add .

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)       
        modified:   README.md
        new file:   service.html


Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/bundle-2)
$ git commit -m "Add services page"
[ft/bundle-2 1e65b75] Add services page
 2 files changed, 149 insertions(+), 1 deletion(-)        
 create mode 100644 service.html

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/bundle-2)
$ git push -u origin ft/bundle-2
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.96 KiB | 1002.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0      
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/bundle-2)
$```

## Exercise 2

```bash

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git pull
Already up to date.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.      

    git pull <remote> <branch>    

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> ft/service-redesign


Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign)
$ git add service.html

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign)
$ git commit -m "Redesign service page"
[ft/service-redesign 479b56b] Redesign service page
 1 file changed, 12 insertions(+) 
 create mode 100644 service.html  

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign)
$ git push -u origin ft/service-redesign
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 470 bytes | 156.00 KiB/s, done.        
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign     
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ ls
README.md

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git pull
Already up to date.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git add service.html

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git commit -m "Update service page in main"
[main 64afbf4] Update service page in main
 1 file changed, 12 insertions(+) 
 create mode 100644 service.html  

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 479 bytes | 239.00 KiB/s, done.        
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
igin/ft/service-redesign'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign)
$ git merge main
Auto-merging service.html
CONFLICT (add/add): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign|MERGING)
$ git add .

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign|MERGING)
$ git commit -m "Resolved conflicts with main"
[ft/service-redesign 6e7d9ae] Resolved conflicts with main

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign)
$ git push
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 231 bytes | 231.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/charite-uwatwembi/Gym_Git_Exercise_Solutions.git
   479b56b..6e7d9ae  ft/service-redesign -> ft/service-redesign

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign)
$ ls
README.md  service.html

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Hp@DESKTOP-1JCVV8Q MINGW64 /d/Study/Studies/the_gym/GIT-EXERCISES (main)
$
```

# Bundle 3

## Exercise 1
```bash
git checkout -b ft/team-page
touch team.html
git add team.html
git commit -m "Add team.html page"
git push origin ft/team-page

git checkout main
git checkout -b ft/contact-page
git checkout ft/team-page
git log  # Copy the commit hash
git checkout ft/contact-page
git cherry-pick <commit_hash>
touch contact.html
git add contact.html
git commit -m "Add contact.html page"
git push origin ft/contact-page

git checkout -b ft/faq-page
touch faq.html
git add faq.html
git commit -m "Add faq.html page"
git push origin ft/faq-page

git checkout ft/team-page
git revert <commit_hash>
git push origin ft/team-page
```