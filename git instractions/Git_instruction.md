![Logo](gitt.png)

# Work with Git and GitHub


## 1. Check git install
Write down command in terminal **git --version**. If git download correct you will see information about current git version. Otherwise you see error.

## 2. Download git
Download last version app from site.

Applay defoult settings

## 3. Git settings
For the first use git. You shoud enter your name and e-mail adress in terminal

``` git config --global user.name```

``` git config --global email.name```
## 4. Start work with Git
First of all you need to create folder on your workspace. For the next step you need to open your folder via ``` VS Code``` by using ``` explorer```. By the next step you need to create a new fail. For this use icon ``` create new fail ``` . After that you need to initialize your folder. You should write down command in terminal ``` git init ```.
## 5. Commands you need to know at the start
After you initialize folder you can begin your project with git. There are some commands you can use
*  ```git status ``` check your curant status on working tree
* ``` git add ``` use to update what will be committed
* ``` git commit ``` use for commit your currant version
* ``` git commit -a -m "" ``` combined command. first command will be ``` git add ``` second command will be ``` git commit ```. Adds all saves it the repository.
* ``` git log / git log --oneline ``` with this command you can see yours all commits
* ``` git checkout / git switch ``` use for switching between branches
* ``` git diff ``` diffrance between current version and commited version

## 6. Fail ignore
To ignore the fail or folder you need to create a new fail ***.git ignore*** and write down to this fail name of folder you want to ignore.

## 7. Create a new branch in Git
For create branch in git you need to write down command ``` git branch branch_name ``` in terminal.

For checking list of branch 
```
use command git branch
```
The current branch will be highlighted **\*master**

## Merging branches in Git

To merrrge the draft brafgnch with the masaster branch you need to switch on the master branch by using command

 ```git checkout / switch master```

 After you switch on master branch you should use command

 ``` 
 git merge branch_name
 ```