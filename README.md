#CodeTrotters Introduction to Web Design, Example

This is an example page for a fictional website
called WorldOfPuppies.com

Your task is to based on the screenshot and html
provided recreate the design as closed as posible.

##About this Repo

In this repo we will find the html of the worldofpuppies

- **index.html**     the main hml file for the website
- **screenshot.png** the desired output
- **img/**           the images used on the website
- **css/**           the folder where our css lives

##Running the embedded webserver

1. Install Node from https://nodejs.org/
2. Install Git  from https://git-scm.com/
3. Fork this repository on github
4. Download the repo to the computer

	**Windows**
	Windows users will have to run this commands
	on the git bash terminal

	**MacOs**
	MacOs users will have to run this commands
	on the Terminal.app

	1. Create a folder for the repository
		```bash
		mkdir ~/worldofpuppies
		cd ~/worldofpuppies
		```

	2. Git clone the repository, use the repository

		```bash
		git clone https://github.com/YOURUSERNAME/worldofpuppies ~/worldofpuppies
		```

5. Install BrowserSync

	```bash
	npm install -g browser-sync
	```
6. Once Browsersync is installed you can begin using it     by running

	```bash
	browser-sync start --server --files='**/*.*'
	``` 		
