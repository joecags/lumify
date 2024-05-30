Getting Started with Git
-------------------------------
Aaron Stewart
Services Program Architect
www.github.com/a-a-ron
-------------------------------
Course Overview - 2m
-------------------------------
Why Git is the leading version control system

Code hosting servuice providers

How to bring your Git project to the next level

After this course, you'll be able to get up and running with a Git based project
-------------------------------
Get Up and Running with Git - 41m
-------------------------------
*What is Git?*
git is a Version Control System or VCS
- Software designed to record changes made to files over time
- Ability to revert back to a previous file version or project version
- Compare changes made to files from on version to another.
- Version control any plain text, not just source code.

Version control is the ultimate time travel machine and your in contorl

txt, html, jpg

Understanding how Git manages data is the most important thing to remember about Git
*Coffee Shop analogy*
Wired Brain Coffee
Steve is the coffee shop owner and changes coffee recipes often

*The Three Stages of a File*
    Staged
        Changes are Marked for Commit
    Modified
        Commit changes
    Committed

Committed has the recipes stored in his file
when he makes a change it moves to modified and is stored in the local database

Modified - is a work in progress where more changes can be made to that file

Staged - changes are Marked for commit this means Steve wants to take the changes made to the file in modified state

Committed - Marked changes have been added to the commit snapshot

*The Three States of a Git Project*
Similiar how  a file can reside in three different states
Steve's Git Project is made up of three different parts

we start with a .git directory (Repository) in Steve's case his local computer.
next we have the Checkout,this is a single copy also called the checkout and placed in the Working Directory
Staging Area (Index) - Stage fixes for next commit

When Steve is ready to commit he pushes to the .git directory (Repository)

Working Directory

Staging Area (Index)

.git directory (Repository)

*Using the Command Line*
pwd -> Print working directory
cd -> Change working directory cd .. or cd ~
        cd .. to go up
        cd folder/file to go down
        cd ~ beginning home folder
ls -> List files in a directory (dir for windows users)
touch -> create a new empty file (copy con for windows users)
mkdir -> create a new empty folder

*Install Git*
https://git-scm.com/downlad/mac

*Configure Git*
git --version
git version 2.39.3 (Apple Git-146)

<!-- Git command do you use to set your global user.name configuration? -->
git config --global user.name "username"
<!-- If need help with username on terminal type whoami -->
git config --global user.email "your_email@example.com"

git config user.name "username"
^^ to override your global settings but just in specific project

git config --list

git config user.name
*Git Help*
2 help optons

man git
git help
or
git help 'specific section of manual'

if stuck at end of man git with (END)
simply press q 
you will be returned to terminal as before :-)

*Initialize a New Git Repository*
adding Git to Steve's recipe project 
repo
cd to project folder using CMD
in project folder we did 
    git init
    to add the new repository

*Send your Code to a Code Hosting Provider*
GitHub
GitLab
Bitbucket

pushing online will make it available online so can get the git anywhere!
also can share with other developers to help with the project

*Create an Account with a Code Hosting Provider*
Creating a GitHub account

*Push a Git Repository to a Code Hosting Provider*
echo "#training-joe" >> README.md


git init
git add README.md
git commit -m "first terminal commit"
git push


echo "#training-joe" >> helpme1.md
echo "#training-joe" >> pikachoo.md

*Summary*


-------------------------------
Basic Commands of Everyday Git - 35m
-------------------------------
<!-- Git command shows you the changes you've staged that will go into your next commit? -->
git diff --staged

<!-- What are the three stages of a file? -->




-------------------------------
Extended Commands of Everyday Git - 46m
-------------------------------


<!-- Which Git commands create a new branch and checks out to it at the same time? -->
git checkout -b banch_name


git commit - m "rename README.md"

<!-- Change branches with checkout -->
git checkout master
<!-- will not be switched to branch 'master' -->

working with branches:
    git add . 
    git stash
    git stash list

<!-- create a new file -->
touch cold_brew
<!-- open ^ in text editor -->
code .

*merge commits*




*reset commits*

Three optinos of Git Reset

git reset --soft
    will commit(s) back to staging area 

git reset --mixed
    will commit(s) back to working directory 

git reset --hard
    moves change to trash, if you do not want to keep anything and start over

git log --oneline

-------------------------------
-------------------------------

*joe questions check*

Which Git command is used to move a file from the staging area to the .git directory?
git commit  'tick'

Which Git command skips the staging area when adding a change from our working directory?
git commit -a -m "commit message" 'tick'

Which command prompt command returns your current folder path location?
pwd 'tick'

Which statement is true regarding branches?
A branch is a pointer to a specific commit in your project 'tick'



*random notes*
branch.main.remote=origin

git add . 
git stash
git stash list