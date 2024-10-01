# CLI (Command Line Interface) commands

- how to tell our computer what to do
- Commands
  - ls - lists out the files and folders of your current directory
  - cd [directory name] - change directory
    - .. -> goes up one directory
    - / -> separate navigating multiple directories
  - mkdir [directory name] - makes a new directory
  - touch [file name] - makes a new file
  - mv and rm -> moving and removing a file (I recommend doing this in the explorer bar)
  - code [directory name] -> opens VS Code at the directory
    - . -> refers to the current directory
  - && -> do one command after another finishes
- Flags
  - extension of the command
  - Example: ls -a (shows all files and directories in the current directory)

# Git vs GitHub

- Git -> version control system using git commands that keeps track of the history of files and folders
- GitHub -> place to store projects

- git commands
  - git init - allows us to use git commands
  - git status - shows what has been added/changed/deleted since the last commit
  - git add [file names] - move files/folders to the staging area
  - git commit -> takes everything from the staging area and makes it permanent
    - -m "message" -> shortcut for witing a message on your commit
  - git checkout -b [name of the branch] - make a new branch and moves to that new branch
  - git remote -> connection to another location
    - add -> add connection
    - nickname -> name of the connection (most commonly origin)
    - location -> where is the actual connection
  - git push -> send your code somewhere
    - nickname -> nickname you gave the remote connection
    - branch name -> which branch you want to push
  
- 3 stages
  - working directory (red)
  - staging area (green)
  - project

# File Naming and Structure for HTML and CSS files

- Don't use special characters (!, @, #, $, %, ^, &, *, (, ), /, + , =)
- Don't use spaces (use hyphens)
- Start the file name with a letter
- Use all lowercase letters separated by hyphens
- Keep your file names short and descriptive
- Always put a file extension on files
