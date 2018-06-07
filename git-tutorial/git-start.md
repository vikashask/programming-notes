## when more than 1 person working so you have to do this
  git pull --rebase origin master
  notes : --rebase option tells Git to move all of user commits to the tip of the master branch after synchronising it with the changes from the central repository,
  
## Start with the master branch
  git checkout master
  git fetch origin 
  git reset --hard origin/master
  
## Create a new-branch
git checkout -b new-feature
