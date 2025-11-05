# my project #01
mkdir my-project-01<br>
cd my-project-01<br>
git init ; initialize the folder into a git repo<br>
echo "# my project #01" >> README.md<br>
git add README.md # stage the file<br>
git commit -m "my first commit" # commit the changes<br>
git branch -M master # lable as a branch<br>
; create a repo in Github: my_project_01<br>
git remote add origin https://github.com/haijunzh/my-project-01.git # link the remote repo to the current local<br>
git branch --set-upstream-to=origin/master # set up the local master branch to track the remote branch 'origin/master' <br>
git push origin master # push the locol master branch to the remote<br>
; create files: .gitignore and notes.txt<br>
git commit -m "commit .gitignore and notes.txt"<br>
git push origin# push to remote<br>
git log#see the history <br>



 


 
