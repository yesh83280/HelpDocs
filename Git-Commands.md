# Git Commands

### GIT SSH Setup:
1. ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
2. eval "$(ssh-agent -s)"
3. ssh-add ~/.ssh/id_ed25519

### Config Setup
1. git config --global user.email "Ponnuri.Yeswanth.@ibm.com"
2. git config --global user.name “Ponnuri Yeswanth”

### To get new remote branches into local
1. git fetch origin
2. git checkout -t origin/uat 

### Remote push for first time
1. git push -u origin branchname

### Empty Commit
1. git commit --allow-empty -m "Empty-Commit"

### Remote Revert Back 
1. git reset --hard <commit-hash>
2. git push -f origin <remote-branch>

### Reset latest commit in local 
1. git reset HEAD~1

### Remove all tags 
1. git fetch origin
2. git push origin --delete $(git tag -l) 
3. git tag -d $(git tag -l)

### Delete specific tag 
1. git push --delete origin 0.0.7 

### Branch Rename
1. git branch -M development - Force mode - If branch already exists, it gets override
2. git push origin --delete development - Delete older branch in remote
3. git push -u origin development - Push newer branch to remote

### Git Delete remote branch
1. git push -d <remote_name> <branchname>
2. git branch -d <branchname>
