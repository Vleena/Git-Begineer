#install a git
yum install git -y

#git initialization to convert directory to git
git init



ls -a  ## will give the hidden directory .git

#git commands
git add .
git commit -m "message"
git log
git log -p
git restore --staged <filename>

git log --oneline
