# vtulab
program hai bhai....!


cd c                               # move to C drive
mkdir Hi                           # create folder Hi
cd Hi                              # enter Hi folder
git init                           # initialize git repository
touch pk.txt                       # create empty file
vi pk.txt                          # edit pk.txt file
git add .                          # stage all files
git commit -m "file created"       # commit changes
git status                         # check status
git log                            # show commit history

git branch feature-branch          # create new branch
git branch                         # list branches
git checkout feature-branch        # switch to feature branch
vi pk.txt                          # edit file in feature branch
git add .                          # stage all changes
git commit -m "edited file in feature branch"   # commit changes
git checkout master                # switch to master branch
git merge feature-branch           # merge feature branch
git log                            # show commit history

git checkout feature-branch        # switch to feature branch
vi pk.txt                          # modify file
git stash                          # stash uncommitted changes
git checkout master                # switch to master
git stash apply                    # apply stashed changes
git status                         # check status
git add .                          # stage all files
git commit -m "stash changed"      # commit stashed changes
git log                            # show commit history

cd c                               # move to C drive
mkdir clone                        # create clone folder
cd clone                           # enter clone folder
git clone https://github.com/Hemanthbk2105/HEMANTH-.git   # clone repository

cd HEMANTH-                        # enter cloned repo
git fetch origin                   # fetch latest changes
git rebase origin                  # rebase local branch
git log                            # show commit history

git checkout feature-branch        # switch to feature branch
vi pk.txt                          # edit file
git add .                          # stage changes
git commit -m "edited a file"      # commit changes
git checkout master                # switch to master
git merge feature-branch -m "Merged feature branch"   # merge with message
git log                            # show commit history

git tag v1.0                       # create lightweight tag
git tag                            # list tags
git show v1.0                      # show tag details

git branch source-branch           # create source branch
git checkout source-branch         # switch to source branch
vi pk.txt                          # edit file
git add .                          # stage changes
git commit -m "first commit in source branch"   # first commit
vi pk.txt                          # edit again
git add .                          # stage again
git commit -m "second commit in source branch"  # second commit
git checkout master                # switch to master
git cherry-pick <commit-id>        # cherry-pick commit

git show <commit-id>               # view specific commit details
git log --author="JohnDoe" --since="2024-11-17" --until="2024-11-19"   # filter commits
git log -n 5                       # show last 5 commits
git revert abc123                  # undo specific commit
