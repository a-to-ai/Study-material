# How to setup github and work on repository from the desktop
This is just a basic tutorial enough to start working on a project.
If you want to understand how git works please watch some youtube video

1. Install git
	- for linux users there is no need to install git comes out of the box
	- for windows users download and install git bash
	
2. configure git
setup username and email id and remote repository where you wanna work.
	- `git init`
	- `git config user.name 'your git username'`
	- `git config user.email 'your git email id'`
	- `git config --global core.editor 'vim'` # other options 'nano', 'emacs'
3. add remote origin
	- `git remote add origin https://github.com/a-to-ai/Study-material.git`

4. pull request
always pull origin first before start working on your local system
	- `git pull origin master`

5. checking stats, Adding file to staging area, committing file and push to remote
	- `git status`
	- `git add 'file_name/folder_name or *'`
	- or use this `git add -A`
	
	- `git commit -m "message about what changes you made"`
	- `git push origin master`
	
