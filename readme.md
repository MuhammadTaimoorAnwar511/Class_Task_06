
dvc add data.csv
git add data.csv.dvc .gitignore
git commit -m "Track updated data.csv with DVC"
git push origin master
run upload_to_drive.py

==
hash1: 676c259cee7cfb16d6e4d24a726637af
hash2: 03f6fed0b2943736ce06f90eb2961927

==
git log
git checkout <commit_hash>  
dvc pull
==
git checkout master

git pull origin master
