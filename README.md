#Lab2 Solution:

###Create a new project on your local machine,then push it your remote repo:
	
	1-create a remote repo called "lab2-project" on github 
	2-on my git run : git clone git@github.com:El-Zedy/lab2-project-.git
	
● Create two branches (dev & test) then create onefile on each branch, and push this changes to the remote repo.
	
	- git branch test
	- git branch dev
	
	- git checkout dev
	- touch devFile
	- git add *
	- git commit -m "adding dev file to dev branch"
	- git push origin dev
	
	- git checkout test
	- touch dtestFile
	- git add *
	- git commit -m "adding test file to test branch"
	- git push origin test
	
	
● Merge this changes on Master branch and then push it to yourremote master branch.

	- git checkout main
	- git merge dev -m"merging into main"
	- git merge test -m"merging into main"
	- git push orgin main
	
● Tell me how to remove them locally and remotely.

	- To delete a remote branch :
	
		∘ git push origin :dev
		∘ git push origin :test
		
	- To delete a local branch
	
		∘ git branch -d dev
		∘ git branch -d test	
	
● Send an invitation to me (shimaakhallaf507@gmail.com).

	- please open this link:
	
		 https://drive.google.com/file/d/1N7VijSYafm5Nw852kdo9Rh7Zd9W1VKlu/view?usp=share_link

● Create an annotated tag with tagname (v1.7) .
	
	- git tag -a v1.7 -m "version 1.7"
	
● Push it to the remote repository.

	- git push origin v1.7 
	- git push --tags
	
● Tell me how to list tags.
	
	- git tag 
	
● Tell me how to delete tag locally and remotely.

	- To delete remote tag:
	
		∘ git push origin --delete v1.7
		
	- To delete local tags:
	
		∘ git tag -d v1.7
	
● Add an image in the README.md file
