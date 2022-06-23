# VC-Bash-Version-Control

Author: Finlay Kerr

Module: Software Development Environments

Task: Create a local version control system in Bash with five commands: add, list, commit, display and help

Usage: vc [COMMAND] [OPTION]
	Description: Version control your files with vc

Command: vc add
	Description: Add files to staging area
	Usage:
		vc add -f FILE (add a specific file)
		vc add -a (add all files in directory)

Command: vc list
	Description: List all files in relevant folders
	Usage:
		vc list 	(user is given an interactive display)
		vc list -s 	(list all files in staging)
		vc list -l 	(list all files in the last commit)
		vc list -c 	(choose which commit to view)
	
Command: vc commit
	Description: Add all files in staging to a commit. If there are
		differences between files, a merge procedure will be initiated.
	Usage:
		vc commit -m MESSAGE (Commit all files with a commit message)

Command: vc display
	Description: Display paginated contents of staged and committed files 
		in the repository
	Usage:
		vc display -s 	(choose a file to view from staging)
		vc display -l 	(choose a file to view from the last commit)
		vc display -c 	(choose a file to view from any commit)


To run:
1) Download and cd to folder
2) run ./vc in bash
