# Git Command Basics Sheet 

## To customize Git and let it know who you are:

- git config --global user.name "My Name" << this is your handle on GitHub>>
- t config --global user.mail "abc@xyz.com" << this is your email associated with the GitHub account

## To initialize a new Git repository locally 
- git init "directory" 

## To fork a repository (i.e. create a working copy for yourself in your Git account)
- use the fork button on the remote repository. Git does not have a native command for forks. There's third party commands that can be installed to do the same, however. 

## To copy a git repository locally
- git clone "git respository link"

# *Note: You need to be in your local Git repository to perform these actions!*

## To see how the local repository differs from the remote repository:
- git status 

## To stage files 
- git add [file]
- Options: add *: stages all files; add [filename]  only stages specific ones. 

## To unstage files without editing the changes made 
- git reset [file]

## To save changes made to the local repository 
- git commit -m "message to describe a change made"

## To finalize these changes in the remote respository 
- git push

## To update the local repository with new changes in the remote repository
- git pull 

## For more Git commands, click [here](https://education.github.com/git-cheat-sheet-education.pdf).

~END~

