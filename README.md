This folder contains notes about the git class

git init tells git to track everything from here and subdirectories.
excute "git init" only once.

git config --list
Lists the global config stuff

Course website: http://chendaniely.github.io/2015-11-23-harvard/

git add .
Adds all modified files

.gitignore contains files to ignore:
*~ (ignore files ending in tilda)
directory/* (ignore everything in directory "directory")

git log
Print commit history --oneline give brief summary

git diff
gives differences like linux diff command
git diff HEAD~1 compares current committed version with penultimate

git checkout HEAD~1 someFile
CHecks out a file from penultimate repository version
git checkout 766df2 someFile
checks out from repository version with hash and name (from git log --oneline)

git reset --hard
Panic button - brings you back to previous commit.

Etherpad link: http://pad.software-carpentry.org/2015-11-23-harvard

# Header in markdown format
## Second level markdown

- bullet one, I hope
- another bullet

1. Item one
2. Item two
3. Third item
