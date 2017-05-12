# Linux

Developed in 1991 by Linus Trovald

Flavors of Linux are called: Distributions (Distros)
    -Examples being: Mint/Debian/Ubuntu/Arch

GUI: Graphical User Interface
CLI: Command Line Interface

Up-arrow/Down-arrow: Previous or last command entered

Tab: Autocompletes

List of Commands:

pwd: Print working directory (Tells you where you are)

ls: List (Shows contents of current directory)

    ls -la(or -ll): Who created the file, write access

clear: Clear (redundant)

cd: Change Directory (Used to navigate between directories/folders)

    Useful variations: cd ..(moves up one directory)

                       cd ../..(moves up two directories)

                       cd /*directory/*directory

                       cd / (root directory)

cp: Copy (Copies files)

    Example: cp README.md newreadme.md(New file new name, keeps old file)

mv: Moves files
    
    Example: mv README.md *folder*

    Example: mv README.md READMEMORE.md (Renames file)

rm: Remove (Deletes)

    Example: rm README.md

mkdir: Make Directory (Makes a new directory)

rmdir: Deletes *empty* folder

rm -r *folder*: deletes non-empty folders

man: MANUAL *SUPER USEFUL*

    Example: man cd

which: Searches for word in (echo $PATH)

su(sudo):Super User(To enter as root or administrator)

    Log in as su=changes user to root

    $ -> #

    exit(switches back to regular user)

date: Current date and time

cal: Current month calendar

    cal 2015 (shows calendar for entire year)

uptime: Current uptime

w: Who is online/logged in right now

whoami: Who you are logged in as

uname -a: Kernal information (What version linux you're using)

free: Memory/Swap usage

touch: Creates new file

top: Displays processes in task manager

    htop:(fancier top)

    install htop with: yum install htop

ifconfig: Shows ip address (same as ipconfig)

    ifconfig -s: (short version)

hostname: Displays hostname

wget: Downloads file from terminal

history: Command history

chmod: Set user permissions

    chmod 755 (User has read/write/execute, everyone else Read/Execute)

    chmod 700 (User has Read/Execute, no one else)

./*Script name*: Using a script

    Format for a simple script:
    
    1) #!/bin/bash(called the shebang. given tothe shell to indicate what program is used to interpret the script)

    2) # *comment*

    3)

    4)echo "Hello World!"

echo $PATH: Shows the list of directories in *your* path

export PATH=$PATH:directory(add directories to your path)

