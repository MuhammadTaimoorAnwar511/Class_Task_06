
dvc add data.csv
git add data.csv.dvc readme.md .gitignore
git commit -m "Track updated data.csv with DVC"
git push origin master
python upload_to_drive.py

==

git log
git checkout <commit_hash>  
dvc pull
==
git checkout master

git pull origin master
