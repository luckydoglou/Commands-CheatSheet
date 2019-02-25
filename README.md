# **Commands-CheatSheet**
All the commands I need so far.

# Vim Command

| Keys/Command | Description |
|:---:|:---:|
| shift + q | prompt exit vim command line |
| shift + : | prompt command line |
| q! | quit without saving |
| x | delete the character |
| i | insert |
| wq | quit with saving |
| dw | delete the word |
| d$/dd | delete line |
| 2w | two word forward (change 2 to the number you want) |
| 0 | move to start of line |
| d2w | delete 2 words |
| u | undo previous action |
| U(upper case) | undo all changes on a line |
| ctrl + r | undo the undo's |

# Git Command

| Keys/Command | Description |
|:---:|:---:|
| git | prompt all the commands |
| git clone url | clone repository to local folder |
| git pull original master | update a local repository from a Github repository |
| git init | initialize empty git repository |
| git status | get the status |
| git add filename | add to a file(step 1) |
| git add -A | add all file |
| git commit -m "write something" | commit the change, locking it in!(step 2) |
| git commit | multi-line commit, quit with shift + : wq |
| git push | push to the Github repository (step 3) |
| git pull | pull the github repository to local |
| git config --global user.name "your name" | set a name that is identifiable for credit when review version history |
| git config --global user.email emailAdress | set an email address that will be associated with each history marker |
| git config --global color.ui auto | set automatic command line coloring for Git for easy reviewing |
| git branch -a | show all branches |
| git branch -d branchName | delete the branch from local repo |
| git push remoteName --delete branchName | delete the branch from remote repo |
| git reset --hard <old-commitID> | commit id in local(can use commit id from github), step1 |
| git push -f remoteName branchName | reset github repo, e.g. git push -f origin branchName, setp 2 |
| git log | view commit history |
| git merge branchName | merge brancName into current branch |

# C/C++ Compile Flags

| Keys/Command | Description |
|:---:|:---:|
| gcc -pedantic -Wall -ansi filename.c | C Compile for C99 |
| gcc -std=c11 -Wall -pthread filename.c | C11 with pthread flag |
| g++ --std=c++14 -pedantic -Wall filename.cpp | C++ Compile |

# MAC Terminal/Shortcut

| Keys/Command | Description |
|:---:|:---:|
| ls | short list |
| cd / cd .. / cd - | home directory / parent directory / previous directory |
| ctrl + c | quit the running program |
| command + K / clear | clears the screen |
| touch [filename] | create a new file |
| mv [file] [new filename] | move / rename file |
| [command-a] && [command-b] | run command b if command a succeeded |
| [command-a]; [command-b] | run command a then command b, regardless of success of a |
| how to cd to a directory with a name containing spaces in bash? | put \ (backslash) before the space |
| Shift + Command + . | Show or hide hidden file in Finder |

# Windows Terminal
| Keys/Command | Description |
|:---:|:---:|
| dir | directory |
| cd | home directory |

# Homebrew
| Keys/Command | Description |
|:---:|:---:|
| | To Slove the "Error: Another active Homebrew process is already in progress" when using "brew update" |
| rm -rf /usr/local/var/homebrew/locks | step 1, remove the lock |
| sudo chown -R "$USER":admin /usr/local | step 2, change ownership to give permission |
| brew cleanup | step 3, not sure what this do, maybe not important |
| | Now we are in "Error: Fetching /usr/local/Homebrew/Library/Taps/homebrew/homebrew-cor failed" or "error: cannot open .git/FETCH_HEAD: Permission denied" |
| brew update-reset | setp 4, reset! |
| brew update | step 5 |

# Bash Commands
| Keys/Command | Description |
|:---:|:---:|




