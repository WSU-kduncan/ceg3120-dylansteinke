# Project 0 - Git Guide

## Command Line Git

- status
  - Shows status of the local repository. This status includes:
    - number of local commits that have not been synced with remote (GitHub)
    - list of files in local folder than are NOT being tracked by git
    - list of files in local folder that have changes that need to be committed
  - `git status`
- clone
    - Create a "current" local copy of a repo
    - `git clone git@github.com/WSU-kduncan/ceg3120-dylansteinke.git`
- add
    - This will allow for files to be added to an index.
    - `git add README.md`
- rm
    - Removes a file from two places, the working tree and and the index
    - `git rm README.md`
- commit
    - Will allow for recording changes made to a repo
        - `-a`: allows for all files to be commited in the working repo
        - `-m`: allows for a commit message to be added
    - `git commit -a -m "fixed bug 4"`
- push
    - Will update remote refrences with associated objects
    - `git push`
- fetch
    - Will allow for downloading objects and references from another repo
    - `git fetch --all`
- merge
    - Will allow the joining of two or more development histories together
    - `git merge branchA branchB`
- pull
    - Allows fetching of repo or branch from another source to make current branch/repo up to date
    - `git pull`
- branch
    - Allows for three different things: kist branche, create a branch, or delete a branch
    - This is commonly used for a dev and production branch for example
    - `git branch dev`
- checkout
    - Used to switch to a branch
    - `git checkout dev`

## Git Files & Folders

- .git folder
    - This is a folder that has all of the information aboout a project, including the files, remote address to a repo, commits, etc.
- .gitignore file
    - This is a file that you put other file names or relative folders in that should be ignored for upload to the repo. For example (bad practice if you do this), if you have a file with passwords, we do not want this on the internet, so we would add the file name into this file so it will not be uploaded.
## GitHub

- Pull requests
    - This allows for an individual to tell others about changes that have been made in a branch within GitHub. You can communicate with others wihin this area before you commit a change to the branch.
    - Steps to create Pull requests:
        - Go to pull requests on GitHub
        - For base, this is where you want to merge to and for compare, this is the changes you want to add/where you made changes
        - Create a title/description
        - Then click "Create Pull Request"
- SSH authentication to repositories
    - This allows for changes to be made onto GitHub from another device or location on a computer that has a secure connection with the server.
    - Steps taken to allows SSH authentication:
        - Create a new keypair from the location you want to have the connection:
            - `ssh-keygen -t ed25519 -C "email"`
        - Go to directory .ssh to find the keypair
        - Run the following commnd to view contents of public key:
            - `cat id_ed25519.pub`
        - Copy all of the contents for the file and head over to GitHub and go to the following location: Profile Picture > Settings > SSH and GPG keys > New SSH key
        - Add a title that is going to be memorable and easy to identify and paste the conents of the public key under "Key"
        - Click "Add SSH key"
        - SSH authentication is now completed and you can complete pushes from your machine after cloning for the first time and making changes.

## Resources

- None used