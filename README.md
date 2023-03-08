# GIT_WEBPAGE
This repository contain two folders :

  1. This webpage was builded using seamonkey
  ```
  UTEP_Henry_Webpage_Final_2022_seamonkey/
  ```    
  3. This webpage was builded using google site
 ```
 UTEP_Henry_Webpage_Final_2023_Google_site/
  ```
# Git Commands :      
## Check repo status 
**$ git status**
```
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	UTEP_Henry_Webpage_Final_2022_seamonkey/
	UTEP_Henry_Webpage_Final_2023_Google_site/
	UTEP_Henry_Webpage_Final_Basic_Info.txt

nothing added to commit but untracked files present (use "git add" to track)
```
## check the branch
**$ git branch -a**
```	
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
```
## Add files and folder and commit
**$ git add . && git commit -m "First Commit"**
```
[main d21fa14] First Commit
...

## Check the links	
**$ git remote -v** 
```
origin	https://github.com/hrmoncada/GIT_WEBPAGE.git (fetch)
origin	https://github.com/hrmoncada/GIT_WEBPAGE.git (push)
```
## Push commit 
**$ git push origin main**
```
Username for 'https://github.com': hrmoncada

Password for 'https://hrmoncada@github.com': 

Enumerating objects: 197, done.
Counting objects: 100% (197/197), done.
Delta compression using up to 16 threads
Compressing objects: 100% (196/196), done.
Writing objects: 100% (196/196), 56.98 MiB | 15.01 MiB/s, done.
Total 196 (delta 23), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (23/23), done.

To https://github.com/hrmoncada/GIT_WEBPAGE.git
   f801973..d21fa14  main -> main
```


### Add a file or folder/ to a Git repository

1. From your terminal, change to the root directory where do you want to store a repository.
````
$ git clone https://github.com/hrmoncada/https://github.com/hrmoncada/GAMESS_REPORT.git.git
````
````
$ cd GAMESS_REPORT
````
2. Initialize the directory under version control from the following command:
````
$ git init     
````
3. Add the existing files and folder to the repository you have initialized:
- files
````
$ git add .
````
- file
````
$ git add file
````
- folder
````
$ git add folder/     
````
4. Commit the files:
````
$ git commit -m "initial commit of full repository"     
````
omit 5 and 6, and continue in 7.

5. Verifies the new remote URL
```` 
$ git remote -v
origin	https://github.com/hrmoncada/GAMESS_REPORT.git (fetch)
origin	https://github.com/hrmoncada/GAMESS_REPORT.git (push)
````
6. Skip this step if you clone your repo. Connect your new local Git repository to the remote repository. To do so, enter git remote add origin with the remote URL:
````
$ git remote add origin <bitbucket_URL>     
````
You can find the URL next to the git clone command for the repository.

Remote origin already exists" error. The solution is to update the URL of the remote repository with the name “origin” to the URL of the remote repository you want to add, instead of trying to create a new remote repository with that name.
````
$ git remote set-url origin https://github.com/your/repository
````
7. Push all the code in your local repo to Bitbucket with the following command:
````
git push
````
or
````
$ git push  -u origin main
````

<!--
### What is this repository for? ###

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact
-->

