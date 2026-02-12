# 1st-real-life-project
This is my first real life project.<br>
Suaib Hassan is the author<br><br><br>
github to vs code using git basg<br> 
1st install <br>2nd git config(connect to your git hub account) <br>3rd auto connect with vs code <br>4th clone(git clone link) repository file and copy to vs code (ls -a)for hidden file (remote to local) <br>   + status (git status) show diff in remote and local file (untracked  modified  staged  unmodified)
<br>
5th add (git add file_name or git add .(for all file)) add new or changed file to staging area <br>   + commit (git commit -m "some message")<br>
6th push(git push origin main) upload local repo to remote repo


<br><br><br>now vs code to github using git<br>
1st init command (git init) to make normal file into fit file<br>
2nd now create new repo in github<br>
3rd add gir remote(git trmote add origin link)<br>
4th check or verify remote origin (git remote -v)<br>
5th to check branch (git branch).......one branch to other (git checkout branchname)......to create new branch(git checkout -b new_branch_name).....to dlt branch(git branch -d branch_name).....merge branch to main 1st check diff(git diff nranch_name) 2nd merge (git merge branch_name)....or PR -pull request, now in this case to sync with local we write pull command(git pull origin main)........merge conflict <br>
6th rename the master branch to main (git branch -M main)<br>
7th push the origin main to repo (git push origin main/ git push-u origin main)<br><br><br>


undo changes<br>
case 1 staged change (git reset file_name) or for all file (git reset)<br>
case 2 commited change for one commit (git reset HEAD~1)
case 3 commited changesfor many commits (git reset commit_hash) then (git reset --hard commit_hash)
