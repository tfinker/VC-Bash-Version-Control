# VC-Bash-Version-Control

Author: Finlay Kerr

Module: Software Development Environments

Task: Create a local version control system in Bash with five commands: add, list, commit, display and help

<strong>Usage:</strong> vc [COMMAND] [OPTION]<br/>
	Description:</strong> Version control your files with vc<br/>

<strong>Command:</strong> vc add<br/>
	<strong>Description:</strong> Add files to staging area<br/>
	<strong>Usage:</strong><br/>
	-	vc add -f FILE (add a specific file)<br/>
	-	vc add -a (add all files in directory)<br/>

<strong>Command:</strong> vc list<br/>
	<strong>Description:</strong> List all files in relevant folders<br/>
	<strong>Usage:</strong><br/>
	-	vc list 	(user is given an interactive display)<br/>
	-	vc list -s 	(list all files in staging)<br/>
	-	vc list -l 	(list all files in the last commit)<br/>
	-	vc list -c 	(choose which commit to view)<br/>
	
<strong>Command:</strong> vc commit<br/>
	<strong>Description:</strong> Add all files in staging to a commit. If there are
		differences between files, a merge procedure will be initiated.<br/>
	<strong>Usage:</strong><br/>
	-	vc commit -m MESSAGE (Commit all files with a commit message)<br/>

<strong>Command:</strong> vc display <br/>
	<strong>Description:</strong> Display paginated contents of staged and committed files 
		in the repository<br/>
	<strong>Usage:</strong><br/>
	-	vc display -s 	(choose a file to view from staging)<br/>
	-	vc display -l 	(choose a file to view from the last commit) <br/>
	-	vc display -c 	(choose a file to view from any commit) <br/>



To run:
1) Download and cd to folder
2) run ./vc in bash
