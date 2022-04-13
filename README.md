# Test-git-2 repository

1. git remote -v
2. git remote add origin https://github.com/Baker-B/testGit-2.git
3. git remote -v
4. git config
5. git config user.name
6. git config user.email
7. git config user.email "akalishuk@gmail.com"
8. git status
9. git add [files] // git add . // git add \* - adding files to stage
10. git commit -m "comment"
11. git log [--oneline]
12. git push [repo_name] [branch_name]
13.
14.

# …or create a new repository on the command line

echo "# testGit-2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Baker-B/testGit-2.git
git push -u origin main

# …or push an existing repository from the command line

git remote add origin https://github.com/Baker-B/testGit-2.git
git branch -M main
git push -u origin main

# …or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
