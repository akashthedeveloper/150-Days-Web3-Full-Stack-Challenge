# Git and GitHub

## Git - It is a Version Control System(VCS) which allows us to maintain history of the project and different versions of it

## GitHub - It is a platfrom which allow us to host our local projects in our system to a cloud of it

## Repository - It is a project folder which contain different files and folders in it

## README.md - It is an about me section of the github repository where the project is been described using the markdown language

## Branch - It is the parallel version of your repository and by default it is a "main" branch . There is another branch called master which is for pushing code or file to the production level

## Commit - It is the set of changes made to the file or repository. A commit is visible in the branch

## Pull Request - People collaborate on pull request. The pull request shows changes of your file to the other person. The pull request will propose the changes you made in the file and show it in main repository

## Fork - It is process to copy others repo in our folder or repo is called forking so that we can start contributing to the projects without affecting the original projects

## Clone - It is the process to copy the repo from github to our local system which pull downs a copy of that repo in our system

## HEAD - It is reference to most recent commit in current branch

```sh
   git -- version  : To get version of the git
```

```sh
   git config --global username "your name here"  : To enter your name globally
```

```sh
   git config --global user.email "your email id here" : To enter your email globally
```

```sh
   git config --global--edit : To change name and email id
```

```sh
   mkdir "folder name"  : To create a folder with name eg: full-stack
```

```sh
   cd "folder name" / "file name" : To change the directory path to any specific file or folder
```

```sh
   touch "file name.extension" or copy con "file name" : To create a new file
```

```sh
   ls or dir : To list all the files and folders
```

```sh
   ls - a  : To show all the hidden files in the repository
```

```sh
   git clone "repo url" : For cloning remote repository to our local system
```

```sh
   git init : To initialize the git
```

```sh
   git add "file name"  : To add the single file
```

```sh
   git add .  : To add all the files and folders of the projects
```

```sh
   git status : To show the status of your files and folders
```

```sh
   git commit -m "write message here" - To commit the changes of the files
```

```sh
   clear : To clear all the commands
```

```sh
   git log : It will show history of all the commit made to the repository
```

```sh
   git branch "new branch name" : To create new branch 
```

```sh
   git checkout "new branch name" : To make new branch active from the previous branch
```

```sh
   git checkout --"file name" : To discard the changes in single file
```

```sh
   git checkout -- .  : To discard all the changes made in all files or repo
```

```sh
   git checkout main : To upload the files and folders to main branch
```

```sh
   git branch -d "branch name" : To delete the branch 
```

```sh
   vim "file name" : To go in Vim editor to change the file
```

```sh
   cat "file name" : It displays whatever is there in file
```

```sh
   rm -rf "file name" : To delete the file
```

```sh
   git restore --staged "file name" : To discard the changes when file is added to stagging area i.e commit stage
```

```sh
   git reset "log id code" : It is basically used to if by mistaken some file or folder is deleted or 
   any file is commited and we do not want to commit that than it is used to get back to previous 
   where it was
```

```sh
   git revert "log id code" : It is used to undo the commited file
```

```sh
   git stash : It is used to save the files and folders in backup whenver required and is not saved in present file
```

```sh
   git stash pop : It is used to bring the files and folders back into stagging area
```

```sh
   git difftool <HEAD> : It shows the difference between your local changes and previous version of file
```

```sh
   touch .gitignore : To ignore the file and create the .gitignore file
```

```sh
   git merge "branch name" : To merge the file from one branch to other
```

```sh
   git remote -v : To push the code to github
```

```sh
   git push : To push code to master branch
```

```sh
   git push -u origin "branch name" : To push code to other branches than master
```

```sh
   git remote remove origin : To remove the origin branch
```

```sh
   git remote add origin "repo url" : To connect local repository to the remote git repo. Here origin  refers to original repo of that project
```

```sh
   git pull remote main or "other branch name" : The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content
```

```sh
   git push -f origin main : To push code to main branch 
```

## To upload or push your personal projects to git

### Step 1 : Create a repository on github

### Step 2 : Copy the repository link

### Step 3 : git remote add origin "repo url"

### Step 4 : git push origin master

## To contribute to any projects or open-source software

### Step 1 : Fork the repository

### Step 2 : git clone "repo url"

### Step 3 : Start contributing to the projects
