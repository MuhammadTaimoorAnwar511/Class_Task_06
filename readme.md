git add .
git commit -m "Your commit message here"
git push origin master
=
git rm -r --cached data.csv
git commit -m "Stop tracking data.csv with Git"
dvc add data.csv
git add data.csv.dvc .gitignore
git commit -m "Track data.csv with DVC"
dvc status
