# VC-Bash-Version-Control

Author: Finlay Kerr

Module: Software Development Environments

Task: Create a local version control system in Bash with five commands: add, list, commit, display and help

Usage: vc [COMMAND] [OPTION]<br/>
	Description: Version control your files with vc<br/>
<br/>
Command: vc add<br/>
	Description: Add files to staging area<br/>
	Usage:<br/>
		vc add -f FILE (add a specific file)<br/>
		vc add -a (add all files in directory)<br/>
<br/>
Command: vc list<br/>
	Description: List all files in relevant folders<br/>
	Usage:<br/>
		vc list 	(user is given an interactive display)<br/>
		vc list -s 	(list all files in staging)<br/>
		vc list -l 	(list all files in the last commit)<br/>
		vc list -c 	(choose which commit to view)<br/>
	<br/>
Command: vc commit<br/>
	Description: Add all files in staging to a commit. If there are<br/>
		differences between files, a merge procedure will be initiated.<br/>
	Usage:<br/>
		vc commit -m MESSAGE (Commit all files with a commit message)<br/>
<br/>
Command: vc display<br/>
	Description: Display paginated contents of staged and committed files <br/>
		in the repository<br/>
	Usage:<br/>
		vc display -s 	(choose a file to view from staging)<br/>
		vc display -l 	(choose a file to view from the last commit)<br/>
		vc display -c 	(choose a file to view from any commit)<br/>

To run:
1) Download and cd to folder
2) run ./vc in bash
