deployment-plan
===============
Deployment Plan for Production Server

SSH into the server “Ten Titles” at  ssh root@104.130.7.30

1.	git branch (to see a list of branches that exist)
2.	you then can create a new branch:  git branch your branch name
3.	git branch (to see your new branch in list)
4.	git checkout branch (your branch name)
5.	git add –A (this adds everything new and deletes anything you may have taken out)
6.	git commit –m “add you message here” in quotes
7.	Once you are ready to merge changes into the master, git checkout master
8.	git merge (your branch name)
9.	git remote add prodServer ssh://root@104.130.7.30/var/repos/tenprojects.git
10.	git push prodSever master
