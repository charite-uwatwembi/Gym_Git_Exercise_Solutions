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