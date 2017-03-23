
To push the local project to github 

1. Create an empty project from GitHub, here empty means empty, not even a README.md file, then follow the steps below:

2. From the local project
…or create a new repository on the command line

- echo "# porjectTwo" >> README.me
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin https://github.com/richardtow/porjectTwo.git
- git push -u origin master

---------------------------------------
To pull the chagnes from github to local project

- git pull origin master

--------------------------------------
To push individual file to github

- vi README.md
- git add README.md
- git commit -m "add more to README.md"
- git push origin master

--------------------------------------
To push dir to github

- It is similar to push individual file

--------------------------------------
To delete a repository

- Manually enter the URL for your repository's Settings page in your browser:
  Ex: https://github.com/YOUR-USERNAME/YOUR-REPOSITORY/settings  
- Under Danger Zone, click Delete this repository.
- Read the warnings.
- Deletion labelingTo verify that you're deleting the correct repository, type the name of the repository you want to delete.
- Click I understand the consequences, delete this repository.

