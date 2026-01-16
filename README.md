hwllo 

https://l1nk.dev/love002


cd c
mkdir Hi
cd Hi
git init
touch pk.txt
vi pk.txt
git add .
git commit -m "file created"
git status
git log



git branch feature-branch
git branch
git checkout feature-branch
vi pk.txt
git add .
git commit -m "edited file in feature branch"
git checkout master
git merge feature-branch
git log




git checkout feature-branch
vi pk.txt
git stash
git checkout master
git stash apply
git status
git add .
git commit -m "stash changed"
git log




cd c
mkdir clone
cd clone
git clone https://github.com/Hemanthbk2105/HEMANTH-.git




cd HEMANTH-
git fetch origin
git rebase origin
git log




git checkout feature-branch
vi pk.txt
git add .
git commit -m "edited a file"
git checkout master
git merge feature-branch -m "Merged feature branch"
git log

git tag v1.0
git tag
git show v1.0




git branch source-branch
git checkout source-branch
vi pk.txt
git add .
git commit -m "first commit in source branch"
vi pk.txt
git add .
git commit -m "second commit in source branch"
git checkout master
git cherry-pick <commit-id>



git show <commit-id>



git log --author="JohnDoe" --since="2024-11-17" --until="2024-11-19"
notepad pk.txt      
remove <<< dhhsj>> 
git add pk.txt
git cherry-pick --continue
git log --oneline


git log -5


git revert abc123


