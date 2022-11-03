#test Repo

git init   //initialize git in folder

git remote add origin https://github.com/MykhailoKutsyk/testRepo.git

git status

git add README.md  //specific file
git add -A   //all files 

git status

git commit -m "first commit"

git push origin master

git clone https://github.com/MykhailoKutsyk/testRepo.git   //add to local folder 

new Branch

git branch // check in which branch You are

git fetch   // download all branches to local

git checkout nameOfBranch // change branch

git checkout -b fix2   //create locally new branch "fix2" and switch to it

git branch  fix3   // create locally new branch "fix3"

git pull origin master   //update local file from remote