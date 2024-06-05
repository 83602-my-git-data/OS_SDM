
 git init
git status
git status -s
git add <file(s)>
git add .
git commit -m <message>
git diff
git log
git log --oneline --graph --color
git checkout <file name>
git reset
git reset --hard
git branch
git branch <new branch name>
git checkout -b <new branch name>
git checkout <branch name>
git merge <another branch>
git branch -d <branch name>



git init
vim file4.txt
    git add file4.txt
    git commit -m "added by $(git rev-parse --abbrev-ref HEAD)"
git checkout -b branch1
    vim file5.txt
    git add file5.txt
    git commit -m "added by $(git rev-parse --abbrev-ref HEAD)"
    git checkout master
    git checkout -b branch2
    vim file6.txt
    git add file6.txt
    git commit -m "added by $(git rev-parse --abbrev-ref HEAD)"
    git checkout master
    git merge branch1
    git merge branch2
    git log --graph --oneline --all
    git branch -d branch1
    git branch -d branch2
    git log --graph --oneline --all
    git branch -m master main
    git log -2
    git diff <commit1> <commit2>
