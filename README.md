# Terminal and Git commands
## Terminal commands
- cd -changes the current directory
    - ~ goes to the user's root directory
    - / goes to the root directory
    - \- goes to the previous directory
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
- init -makes a local directory into a git repository

## Markdown syntax

# Big Title (#)
## This is some text for a subtitle (##)
### This is some text for a smaller header (###)
There is no formatting for normal paragraphs

Putting a new line will make it a new paragraph
**this is bold(\*\*)**
*this is italic(\*)*
***this is bold italic text(\*\*\*)***
- This is a bullet point (-)
    - this is a different bullet point( \-)
* *also makes a bullet point(\*)

![picture of a bear bathing - this is the alt text](https://placebear.com/300/100)
(\![alt text](image url)

>This is a "Quote" thing (\>)

>> This is a doubley deep quote (\>\>)

1. First item (only the first item matters for numbering) (1.)
4. Second item (4.)
1. Third item (1.)
5. Fourth item (5.)
7. Fifth item (7.)
