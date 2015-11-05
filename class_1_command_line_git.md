#Unix/Linux/MacOSX Commands
* `~` : This symbol means "home" on the UNIX command line.
* `/` : This symbol means "root", the ultimate parent directory.
* `whoami` : This makes the terminal output the current user name.
* `pwd` : shows your path (where you are in your directory tree)
* `cd` : change directory (for navigation)
* `ls` :  list the contents of a directory
* `cd ..` : go backwards one directory
* `mkdir` : create a new FILE!  MUAHAHAHAHA
* `touch` : create a new empty file
* `cat` : concatenate the contents of a file, either directly to the terminal or actually concatenate multiple files together
* `.` : your current directory (append this to commands to say 'do the thing to this directory/everything in this directory')
* `rm` : remove; delete
* `rm -rf` : for deleting directories and their contents; f is for force (no prompts) and r is for recursive (keep deleting until everything in the directory is gone) 
* `man` : stick it in front of any command to print the manual for that command to the terminal

# Basic Git commands
* `git init` : creates a hidden git repository in your directory
* `git add .` : adds all contents to your directory to the staging area
* `git add hello.txt` : adds a specific file to the staging area
* `git status` : displays the status of git in the terminal (anything to stage, anything to commit, etc.)
* `git commit -m 'created hello.txt` : moves staged content to the repository, along with whatever message you type
* `git push origin master` : pushes your repository to the server