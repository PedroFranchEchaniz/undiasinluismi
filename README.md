# undiasinluismi



git clone https://github.com/PedroFranchEchaniz/undiasinluismi.git

$ git add .

git commit -m "first commit"

git push

touch .gitignore

git tag -a v0.1 -m "Version 0.1"

git push --tags

git add .

git commit -m "segundo commit"

git push

git checkout -b v0.2

touch 2.txt

git add .

git commit -m "cambios repo"

git push --set-upstream origin v0.2

git checkout main

git merge v0.2

