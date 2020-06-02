# Git Commands Guide
# INSTALLATIONS & GUIS
With platform specific installers for Git, Github also provides the ease of staying up to date with the latest release of the command line tool while providing a graphical user interface for day to day interaction, review and repository synchronizations.

## GitHub for Linux
```
sudo apt install git
```

## GitHub for Windows
https://windows.github.com

## GitHub for Mac
https://mac.github.com

## Git for all Platforms 
https://git-scm.com

# SETUP
use here your GitHub Credentials

```
git config --global user.name "your github user name"

git config  --global  user.email "your linked email"
```


# GO FOR INIT - operations for repositories

__to initialize an existing directory as your Github repository.__
```
git init
```
>Make sure to first reach your desired Directory before initialising.

__retrieve an entire repository from  a hosted location vai given URL.__
```
git clone  [url]
```
#
#
# STAGING ENVIRONMENT – adding to stage env and making commit

```
git status
```
>shows the current status of modified files in he working directory, which are staged for your next commit.
```
git add [file]
```
>add a file to the staging environment as it looks now to your next commit.
```
git reset [file]
```
>unstage a file while retaining the changes in working directory.
```
git diff 
```
>diff of what is changed but not staged
```
git diff --staged 
```
>diff of what is staged but not yet commited.
```
git commit -m "descriptive message in relation to your commit"
```
>commits your staged content.
#
#
#

# BRANCH & MERGE
```
git branch
```
>list your branches. A "*" will appear over your currently active branch.
```
git branch [branch-name]
```
>create a new branch at the current commit.
```
git checkout
```
>switch to another branch and check it out into your working directory.
```
git merge [branch]
```
>merge the specified branch's history into the current one.
```
git log
```
>show all commits in the current branch's history.
