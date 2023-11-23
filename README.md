 git clone https://github.com/sergeytynyanko/new-project.git
 touch README.md
 git add README.md
 git commit -m "Init"
 git push
 git checkout -b development
 git commit -am "development"
 git merge main
 git status
 git commit -m "Merge main and development"
