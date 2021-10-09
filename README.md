# GIT Useful Commands
To set your global username/email configuration:

    git config --global user.name "ADD USERNAME HERE"
    git config --global user.email "ADD EMAIL ADDRESS HERE"

Create New Branch

    git checkout -b

Check Current Branch

    git branch

Move one branch to another branch

    git checkout
    git branch

Check status of current branch

    git status

Save new or updated files

    git status
    git add -A
    git commit -m "Write your message"
    git pull origin
    git push origin

Merge Branch from one to another, Suppose you want to merge staging branch into master follow the below steps

    git branch // Will shown you your current branch
    git checkout master // you must have to move into master branch
    git pull origin master // Must have to take pull
    git merge staging // staging branch will merge with master branch
    git push origin master // We have to push updated changes on master branch
