## hello-world
Learning git

This is project for learning git/github features

## Todo

  1. Create branch
  2. Edit branch
  3. Commit changes
  4. Clone project on desktop
  5. Create dev branch, edit and commit changes
  6. Merge changes
  
## What is done
	1. On desktop create project hello-world
			'$ git clone git://github.com/sda-1978/hello-world hello-world' - not correct, can't push into git:// 
			'$ git clone https://github.com/sda-1978/hello-world.git hello-world'
	2. Pull changes and go to branch 'readme'
			'$ git pull'
			'$ git branch --track readme origin/readme'
			'$ git checkout readme'
	3. Commit changes
			'$ git add readme.md'
			'$ git commit -m "add changes from desktop"'
	4. Merge changes and push to github repo
			'$ git push origin readme'...
	5. Integrate changes on desktop
			'$ git pull origin readme'
			'$ git commit -m 'update README''
			'$ git merge origin/readme'
			'$ git push origin readme'

			
##About

Author: Dmitry Shemyakin  
Repo: https://github.com/sda-1978/hello-world 
