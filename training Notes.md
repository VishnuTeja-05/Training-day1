##### Git and GitHub

=====================

Git is an open-source, local version control system (VCS), while GitHub is a web-based, cloud-hosted service that provides a graphical interface and collaboration features for Git repositories. Git is the underlying technology, and GitHub is a platform that uses that technology. 



##### push files from git to GitHub \& Static Website Deployment using Github

==========================================================================================================



Microsoft Windows \[Version 10.0.26200.7171]

(c) Microsoft Corporation. All rights reserved.



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)>git init

&nbsp;                                                  ========

Initialized empty Git repository in C:/Users/vishnuteja/OneDrive/Desktop/Training(3-2)/.git/



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)>git add .

&nbsp;                                                  =======

C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)>git commit -m "my first commit"

&nbsp;                                                  ===============================

Author identity unknown



\*\*\* Please tell me who you are.



Run



&nbsp; git config --global user.email "you@example.com"

&nbsp; git config --global user.name "Your Name"



to set your account's default identity.

Omit --global to set the identity only in this repository.



fatal: unable to auto-detect email address (got 'vishnuteja@LAPTOP-EOU5V5KQ.(none)')



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)> git config --global user.email "vishnucolab1.1@gmail.com"

&nbsp;                                                  ==========================================================



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)> git config --global user.name "VishnuTeja-05"

&nbsp;                                                   =============================================



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)>git commit -m "my first commit"

&nbsp;                                                  ===============================

\[master (root-commit) 4b327d2] my first commit

&nbsp;2 files changed, 197 insertions(+)

&nbsp;create mode 100644 index.html

&nbsp;create mode 100644 styles.css



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)>git remote add origin https://github.com/VishnuTeja-05/Training-day1.git

&nbsp;                                                  ==========================================================================



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)>git branch

&nbsp;                                                  ==========

\* master



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)>git branch -M master 

&nbsp;                                                  ====================



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)>git push -u origin master

fatal: unable to access 'https://github.com/VishnuTeja-05/Training-day1.git/': Could not resolve host: github.com



C:\\Users\\vishnuteja\\OneDrive\\Desktop\\Training(3-2)>git push -u origin master

info: please complete authentication in your browser...=====================

Enumerating objects: 4, done.

Counting objects: 100% (4/4), done.

Delta compression using up to 12 threads

Compressing objects: 100% (4/4), done.

Writing objects: 100% (4/4), 1.53 KiB | 312.00 KiB/s, done.

Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)

To https://github.com/VishnuTeja-05/Training-day1.git

&nbsp;\* \[new branch]      master -> master

branch 'master' set up to track 'origin/master'.



