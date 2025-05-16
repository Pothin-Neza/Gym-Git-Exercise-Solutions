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

