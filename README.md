# ryans-notes-

Development workflow
clone and install
git clone https://github.com/Peeas/brownco.git After repo is cloned and installed locally (be sure to run npm i in the root and then in the client directory) npm i cd client npm i
workflow
on master branch
in root directory
git checkout master
git checkout pull origin master
git checkout -b BRANCHNAME i.e. git checkout -b PHASE2-22 now you should be on PHASE2-22 branch
on active development branch
git pull --rebase origin master --> make changes <--
git add .
git commit -m"YOUR COMMIT" --> example: git commit -m"PHASE2-22: make hero div same size done"
git pull --rebase origin master
git push origin BRANCHNAME --> example git push origin PHASE2-22
in github
go to pushed branch
create a new pull request into master (feel free to ask me to review any code by adding me as a reviewer)
review changes and merge into master
