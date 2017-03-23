Create an empty project from GitHub, here empty means empty, not even a README.md file, then 
follow the steps below:

…or create a new repository on the command line

echo "# porjectTwo" >> README.me

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/richardtow/porjectTwo.git

git push -u origin master
