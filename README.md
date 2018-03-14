##Individual Assignment 4 Part 1: Git Usage

In this assignment, you will get familiar with Git and some of its main features. The assignment assumes that you are working from the command line, and we will simulate the presence of multiple users by using two terminal windows. If you are already familiar with Git and a specific Git client, feel free to use that, as long as you do what the assignment requires.

In the following, the term “REPO” is used to indicate the repository created for your assignment. Using this link, https://github.com/CMSC-355/REPO/, you can view the REPO set up for this assignment. You will not be changing this repository, so please DO NOT make any changes here.  Instead click on the Fork button at the top right of the screen.  This will allow you to copy this repository to your location on GitHub.

Please also make sure to read the whole assignment before getting started and to follow the instructions to the letter (e.g., use the exact commit messages provided in the assignment, rather than variations of them). If you don’t know how to accomplish a task, either consult Git’s help by running “git --help [command]” or leverage online resources. If you receive an error while executing a Git command, make sure to read the error message, as Git often suggests exactly the right thing to do.
  
###Individual Assignment 4 Part 1 Instructions
####Part 1 (Terminal 1)
Before you start, make sure to specify your name and email address using command “git config”, if you haven’t already. 

Also, if you have not already done so, go to this link: https://github.com/CMSC-355/REPO/.  Here you will create a copy of this repository on your account. Click on the Fork button at the top right of the screen.  This will allow you to copy this repository to your location on GitHub.


1. Open a terminal window
2. Create and go to directory Student1
3.	Clone REPO
4.	This should create a directory called REPO under directory Student1
5.	Go to directory REPO 
6.	Create and go to directory Part1 (under REPO)
7.	Create a file called myinfo.txt that contains only one line with your first and last name
8.	Commit the file to your local repo with comment “Add myinfo file”
9.	Create a branch called “dev1” and switch to it
10.	Create a file called dev1.txt (the content of the file is irrelevant)
11.	Commit the file to your local repo (it should be in branch “dev1”) with comment “Add dev1 file”
12.	Switch to the “master” branch
13.	Edit file myinfo.txt and add your zip code in a separate line (feel free to make up the code, if you don't want to use yours)
14.	Commit the file to your local repo with comment “Add zip to myinfo”
15.	Merge the “dev1” branch into the “master” branch (any commit message is fine here)
16.	Push the master to the remote repository

####Part 2 (Terminal 2)
1.	Open a second terminal window
2.	Create and go to directory Student2
3.	Clone REPO
4.	Just like before, this should create a directory called REPO under directory Student2
5.	Go to directory REPO/Part1
6.	Create and switch to the “addPhone” branch
7.	Edit the file called myinfo.txt and change your zip code to a phone number and add your eID in a separate line
8.	Commit the file to your local repo (it should be in branch “addPhone”) with comment “Add phone and eID”
9.	Push the branch, "addPhone" to the remote repository

####Part 3 (Terminal 1)
1.	Go back to the first terminal
2.	Create a branch called “addEmail” and switch to it
3.	Edit file myinfo.txt and add your email in a separate line 
4.	Commit the file to your local repo (it should be in branch “addEmail”) with comment “Add email”
5.	Update and push the master to the remote repository. To do so, you will have to suitably pull the master from the remote repository and handle conflicts. In handling conflicts, make sure not to lose any content, not to have any of the extra text added by Git to mark the conflicting parts, and to preserve the order of the information as it appears in the assignment.  You will then merge the changes made in the addEmail branch with the master. (Any commit message is fine for the merged file.)
6.	Tag the current version of the master as “Version1” and push the tag to the remote repository.

####Part 4 (Terminal 2)
1.	Go back to the second terminal
2.	Switch to the “addPhone” branch if you are not already on it
3.	You are now going to integrate the change you made to the "addPhone" branch with the remote repository's master. To do so, you will have to suitably pull the master from the remote repository and handle conflicts. In handling conflicts, make sure not to lose any content, not to have any of the extra text added by Git to mark the conflicting parts, and to preserve the order of the information as it appears in the assignment.  You will then merge the changes made in the addPhone branch with the master. (Any commit message is fine for the merged file.)
4.	Tag the current version of the master as “Version2” and push the tag to the remote repository.

To submit your assignment, post in Blackboard 
1.  The URL for your GitHub repository
2.  A screen shot of the commits in the master on the GitHub repository
