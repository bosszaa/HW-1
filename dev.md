# New Commands 26/01/2018
-----------
### File Undo 
``````
$ git checkout test.txt
``````
### การ undo ไฟล์ ถ้าไฟล์นั้นได้ add ไปแล้ว --> จะได้สถานะ untrack
``````
$ git reset HEAD test.txt
``````
## การยกเลิกการ Commit
``````
$ git reset --soft "HEAD^"
``````
### การดูรายละเอียด
``````
$ git log --oneline
``````
### Delete file,After committed
``````
$ git rm test.txt
``````
+ Recovery
``````
$ git add file
$ git stash
$ git pull
$ git stash pop (recovery data)
$ git add > commit > push

### Branch
``````
$ git branch yourbranch 		(Create Branch)
$ git checkour yourbranch		(Move to branch yourbranch)
$ git checkout -b yourbranch 		(Create branch and move to new branch)
$ git branch -a 			(Status branch)
$ git branch -d yourbranch 		(Delete branch | Move to master first.)
$ git push -u origin yourbranch	
-- Upload branch to master -- 
$ git checkout master
$ git merge --no-ff dev 		(merge dev to master | --no-ff) 
``````