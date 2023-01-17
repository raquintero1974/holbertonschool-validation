build:	## Creates a Website using hugo
	hugo

clean:	## Cleans the files and directories in dist directory
	rm -rf dist/*

post:	## posts using environment variables
	hugo new posts/$(POST_NAME).md
	sed -i 's+title.*+title: "$(POST_TITLE)"+g' content/posts/$(POST_NAME).md

help:	## Informs about each target
	echo build: creates a Website
	echo clean: delete files and folders fron dist directory
	echo post: Takes two environment variables and use thn for post