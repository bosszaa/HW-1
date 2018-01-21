## Recovery
''''
* git checkout test.txt (discard edit)
* git reset HEAD test.txt (discard add)
* git reset --soft "HEAD^" (discard commit)
''''
## Stash
* git add .
* git stash (hide your update)
* git pull
* git stash pop (recover file)
* git add .
* git commit -m "..."
* git push

## git branch
* git branch -a (list branch)
* git branch dev (create branch)
* git checkout dev (switch to branch)

* git checkout -b new (create+switch to new branch)

* git add .
... git commit -m "add dev.md"
... git push -u origin dev


## Home work
cteate 2 new branch (dev,feature)
...dev:dev.MD (list command you learnt)
...feature:feature.MD (list features in your project)

----
## Switch to branch master:
...git merge --no-ff dev
...git merge --no-ff feature
----
...git rm test.txt (delete file, after commit)