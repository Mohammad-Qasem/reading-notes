# Git Intro.

In order to explain Git, we have to first explain various aspects of Version Control.

## Version Control.

Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

it is like controling and modifies files in site from your (local) PC.

1-Local Version Control.

2-Centralized Version Control.

3-Distributed Version Control (DVCS).

## what is Git?

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it. actually Git creates a snapshot of the file and stores a reference to it.

examble of commit 
                   

                  git commit -m 'any massege' 

Which tell that we are raedy to push it into the site like (GitHub).

Files in Git can reside in three main states: committed, modified and staged.

*Committed:Data is securely stored in a local database

*Modified:File has been changed but not committed to the database

*Staged:Flagged a file’s changed version to be committed in the next snapshot

you can see this picture where how your projects and modification and addition into your reposity.

![Git](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

## Setting up a Git Repository.

-Importing:

you can track a lociation in your local where you want to save your reposity to clone in it.

To start tracking these repository files, perform an initial commit by typing the following:

* $ git add *.c

* $ git add LICENSE

* $ git commit -m “any message here”

Note : $ cd test (cd = change directory).

## Tracking and Staging a New File.

-Single File

Track one file only by using the following format:

                 git add filename
-All Files

                 Track all files in a repository by using the following command:

                 $ git add *


*After using these commands, files are tracked and staged for committing.





