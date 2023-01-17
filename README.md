# Terminal and Git commands
## Terminal commands
- cd -changes the current directory
    - ~ goes to the user's root directory
    - / goes to the root directory
    - - goes to the previous directory
    - .. goes up one directory
- pwd -tells you the current working directory
- mkdir -makes a directory
- rm -removes a file
    - -r (recursive) allows you to remove folders
- touch -makes a new file
- echo -adds onto a file
- cat -tells us what's in a file
- mv -used to change a file name in the directory you are in or move a file
- open -will open a file in a text editor (better than vi and vim) (the text editor in Linux is Pluma)

## GIT commands
- ssh-keygen -t ed25519 -C "your email" - makes a ssh key ed25519 is the encryption type
- add -puts a file to the stagging area for commits
- commit -commits the files in the stagging area
- status -shows the status at the moment
- push -pushes the commits to the online repository
- remote add <name> <url> links a local repository to an online one
