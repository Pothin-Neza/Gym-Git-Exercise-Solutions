# Gym-Git-Exercise-Solutions

#Bundle
## Exercise 1
``` 
$ mkdir git-exercises

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git branch
* main

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git branch -m main master

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (master)
$ git add .

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (master)
$ git commit -m "created project folder and renamed main to master"
On branch master
 in what will be committed
        git-exercises/

nothing added to commit but untracked files present (use "git add" to track)     

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (master)
$ cd git-exercises/

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (master)
$ git add .

er and renamed branch from main to master
 1 file changed, 11 insertions(+)
 create mode 100644 git-exercises/index.html

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (master)
$ git add remote origin https://github.com/Pothin-Neza/Gym-Git-Exercise-Solutions.git
fatal: pathspec 'remote' did not match any files

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (master)
$ git remote add origin $ git add remote origin https://github.com/Pothin-Neza/Gym-Git-Exercise-Solutions.git
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching   
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (master)
$ fatal: pathspec 'remote' did not match any files^C

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (master)
                                                                                 .git
One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (master)
$ git remote -v                                                                  )
origin  https://github.com/Pothin-Neza/Gym-Git-Exercise-Solutions.git (fetch)    
origin  https://github.com/Pothin-Neza/Gym-Git-Exercise-Solutions.git (push)     

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (master)                                                                                )
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 521 bytes | 173.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Pothin-Neza/Gym-Git-Exercise-Solutions/pull/new/m/master
remote:
To https://github.com/Pothin-Neza/Gym-Git-Exercise-Solutions.git
 * [new branch]      master -> master

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (masterer)
$ git branch dev

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (master)
$ git branch
  dev
* master

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (master)
$ git checkout dev
Switched to branch 'dev'

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (dev)$ git checkout -b test
Switched to a new branch 'test'

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (test)
$ git checkout dev
Switched to branch 'dev'

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (dev)$ git branch
* dev
  master
  test

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (dev)$ git checkout -d test
HEAD is now at ddb8448 created project folder and renamed branch from main to master

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises ((ddb8448...))
$ git branch
* (HEAD detached at refs/heads/test)
  dev
  master
  test

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises ((ddb8448...))
$ git checkout dev
Switched to branch 'dev'

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (dev)$ git checkout -d test
HEAD is now at ddb8448 created project folder and renamed branch from main to master

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises ((ddb8448...))
$ git branch
* (HEAD detached at refs/heads/test)
  dev
  master
  test

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises ((ddbSwitched to branch 'dev'

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions/git-exercises (dev)$ git branch -d test
Deleted branch test (was ddb8448).
```

## Exercise 2

```
$ git status
On branch dev
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        git-exercises/home.html

nothing added to commit but untracked files present (use "git add" to track)

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash
No local changes to save

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git add .

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git commit -m "init commit"
[dev 674fa4a] init commit
 1 file changed, 11 insertions(+)
 create mode 100644 git-exercises/home.html

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git status
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
                                      .html
One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)           dd" and/or "git commit -a")
$ git stash
Saved working directory and index statit-Exercise-Solutions (dev)e WIP on dev: 674fa4a init commit     
                                      e WIP on dev: 674fa4a init commit
One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)           it-Exercise-Solutions (dev)
$ git add .

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git commit -m "init commit in about 
file"
[dev f0e06b5] init commit in about file
 1 file changed, 12 insertions(+)     
 create mode 100644 git-exercises/about.html

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git status
On branch dev
Changes not staged for commit:        
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)     
        modified:   git-exercises/about.html

no changes added to commit (use "git add" and/or "git commit -a")

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash
Saved working directory and index state WIP on dev: f0e06b5 init commit in about file

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git add .

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git commit -m "init commit in teac=m file"
[dev 3e0bbdb] init commit in teac=m file
 1 file changed, 12 insertions(+)     
 create mode 100644 git-exercises/team.html

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git status
On branch dev
Changes not staged for commit:        
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)     
        modified:   git-exercises/team.html

no changes added to commit (use "git add" and/or "git commit -a")

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash
Saved working directory and index state WIP on dev: 3e0bbdb init commit in teac=m file

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash pop
On branch dev
Changes not staged for commit:        
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)     
        modified:   git-exercises/team.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped refs/stash@{0} (50c1ef7585b94d2ced648e0e4e11c31b52a8051a)

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash list
stash@{0}: WIP on dev: f0e06b5 init commit in about file
stash@{1}: WIP on dev: 674fa4a init commit
stash@{2}: WIP on dev: ddb8448 created project folder and renamed branch from m

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash pop stash@{0}
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   git-exercises/about.html
        modified:   git-exercises/team.html

$ git stash list
$ git stash list                    commit
stash@{0}: WIP on dev: 674fa4a initted project folder and renamed branch from m commit
stash@{1}: WIP on dev: ddb8448 crea$ git stash list
stash@{0}: WIP on dev: 674fa4a init commit
stash@{1}: WIP on dev: ddb8448 created project folder and renamed branch from main to master

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash pop stash@{0}
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)        
        modified:   git-exercises/about.html
        modified:   git-exercises/home.html
        modified:   git-exercises/team.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{0} (ae3332d441db8ac775fae52cb26ceaaf43bdd2f5)

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash list
stash@{0}: WIP on dev: ddb8448 created project folder and renamed branch from main to master

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash pop stash@{0}
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   git-exercises/about.html
        modified:   git-exercises/home.html
        modified:   git-exercises/team.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{0} (269ec5060bb3cfaa887290c97e1b5228fa4f96ee)

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git add .

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git commit -m "about to push exercise 2 bundle 1"
[dev 0a7fcb4] about to push exercise 2 bundle 1
 4 files changed, 140 insertions(+), 3 deletions(-)

One plus Ltd@PothinN23 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git push origin dev
Enumerating objects: 22, done.
Counting objects: 100% (22/22), done.
Delta compression using up to 4 threads
Compressing objects: 100% (19/19), done.
Writing objects: 100% (19/19), 2.79 KiB | 317.00 KiB/s, done.
Total 19 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (6/6), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Pothin-Neza/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/Pothin-Neza/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
```

## Bundle 2

## exercise 1
