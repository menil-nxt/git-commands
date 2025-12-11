# git-commands

# Here we learn Git and GitHub basic to Advance

# what is Git

- Git is a distributed version control system that helps you track and manage changes to files, especially source code, over time.
- Saving diffrent virsion
  - save snapshots of your project at various stages.
  - making it easy to revert to older versions if needed.
- Collaboration
  - Multiple people can work on the same project simultaneously without overwriting each other's changes, facilitating teamwork.
- Tracking changes
  - Git records who made what changes and when, providing a clear history of the project's evolution.

# how to set config values (create username and email-id)

- git config --global user.name "Your Name"
- git config --global user.email "Your Email-id "

- check for created your global username and email-id
  - git config --list

# if you know or need help for any command

- git help command_name(ex :- config)
- git add --help

- if you don't know any command how that command work for that help is guide you how that command is work and what you do with that command and how to write that command

# cloning a remote repository

- git clone <repository url>
- git clone <link of that repository>

- clone you repository with your project

# viewing informatin about the remote repository

- git remote -v

- give you information about how many repositorys are there in one project

# see list of files and repository

- ls -la

- show all files of inside that repository

# initialize repository from existing code

- git init

- if you want to go inside any repository at that time write

# NOTE :- first get list of all repository that go inside which repository you want to go.

1. ls -la
2. git init

# remove .git (inside folder)

- rm -rf .git

- it's remove all .git extensions files from your folder

# get status about your file

- git status

- it's show you modified, untracked file status or those files are not commited yet.

# add file to staging area

- git add -A -> add all branching files

- git add. -> add particular branch inside all file

- git add file_name.extension -> add particular file or with file extension

  - git add xyz.html -> only this file add
  - git add .html -> only .html extention files are added

# removing file into stahe area

- git reset file_name
- git reset

# how to commit your file (local system)

- git commit -m "message"

# how to push into github (remote system)

- first time
- git push origin "message" OR
- git push origin main

# how to push into another branch

    - git push origin branch_name

# second time

    - git push

# full example of how your commit your code into github.

- step - 1 :- git intit
- step - 2 :- git add .
- step - 3 :- git commit -m "message"
- step - 4 :- git push origin main
- step - 5 :- git push

- if you have branch than
  - git push origin branch_name -> every time write for push your code into remote repository (github)
