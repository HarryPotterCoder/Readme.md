# Readme.md
// Git Commands
gitignore
ls <- List and variations (ls -a, ls -l)
 pwd <- Present Working Directory
mkdir homework1 <- command to make a homework1 directory
rm -r homework1 <- Remove homework 1 directory (Needs -r on directories and no -r if its just one file)
cd homework1 <- Change directory to homework1 (May need to make it again if you deleted)
git init <- create a git repo
git status <-Git Status to check what is or is not tracked and what branch your on
vi .gitignore <- opens vi to edit a .gitignore file and add *.sw* to ignore swap files from vi
git add .gitignore
git commit -m "added swp files to ignore"
git checkout master