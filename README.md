# kottans-frontend
Learning repository for Kottans-frontend courses

Hi all!
----
I try to write in English for practice, so I think you will be not strict for me if you find mistakes. In this course I learned new instruments for organize work on the future projects. This educational task gave me knowing about Git and GitHub and their power. With Git and GitHub we can make new parts of the project and don’t care about lose our progress even if my personal computer hard drive will be lost. Because all the working data stay on the remote repository, and I can continue my work on any new machine or from any place of the world (of course if I have an internet connection:)). 

Git commands:
------------
- **git init** - create a new repository with Git
- **git clone** - make an identical copy of project
- **git status** - show the state of our repository
- **git log** - command is used to display all of the commits of a repository  
  Flags:
  - **--oneline** - is used to alter how git log displays information
  - **--stat**  - display the files that have been changed in the commit
  - **--patch (-p)** - can be used to display the actual changes made to a file
- **git show** - shows a specific commit. Show only one commit
- **git add** - is used to move files from the Working Directory to the Staging Index
- **git add .** - The period . refers to the current directory and can be used as a shortcut to refer to all files and directories (including all nested files and directories!)
- **git commit** - this command takes files from the Staging Index and saves them in the repository  
  Flags: 
  - **-m** – with this flag you can write commit message directly on the command line
- **git diff** - this command can be used to see changes that have been made but haven't been committed, yet
- **git branch** - show list all branch names in the repository
- **git branch «name of new branch»** - create a new branch but stay on the master branch
- **git checkout** – this command switch the working branch
- **git merge** - this  command is used to combine branches in Git
- **git commit –amend** - can change the commit message or can add the files to last commit
- **git reset** - erase commits from the repository
- **git reflog** - Git does keep track of everything for about 30 days before it completely erases anything. This command access this content
  Flags: 
   - **--hard** - erase commits
   - **--soft** - moves committed changes to the staging index
   - **--mixed** - unstages committed changes  
   **^** - indicates the parent commit  
   **~** – indicates the first parent commit
