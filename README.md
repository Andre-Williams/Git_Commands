# Git Commands



## Connect to online repository

1) Create a new project in PyCharm

2) Initialise the repository in Pycharm by going to the terminal and entering the following commands

```
> git init

> git git remote add origin <Repository_Location> e.g https://github.com/Pegasys-Resilience/WBGIT.git
```

3) Retrieve remote repository files and setup local repository

```
> git fetch

> git pull
```
Repository should now be locally setup.

4) Add or create python files in the the local repository

5) Once changes are made, save changes by uploading them to the remote repository using the following commands

```
> git add .

> git commit -m "commit message"

> git push
```

## Ad-hoc git commands

To check if any changes have been made to files in the local repository use the following command:

```
> git status
```

To check the specific changes made with in the files use the following command:

```
> git diff
```
