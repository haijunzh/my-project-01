# my project #01
mkdir my-project-01
cd my-project-01
git init ; initialize the folder into a git repo
echo "# my project #01" >> README.md
git add README.md ; stage the file
git commit -m "my first commit" ; commit the changes
git branch -M master ; lable as a branch
; create a repo in Github: my_project_01
git remote add origin https://github.com/haijunzh/my-project-01.git ; link the remote repo to the current local
git push origin master ; push the locol master branch to the remote
 