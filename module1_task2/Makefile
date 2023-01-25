build:	## Creates a Website using hugo
	hugo

clean:	## Cleans the files and directories in dist directory 
	rm -rf dist/*
	

post:	## Posts using environment variables
	hugo new posts/$(POST_NAME).md
	sed -i 's+title.*+title: "$(POST_TITLE)"+g' content/posts/$(POST_NAME).md

help:	## Informs about each target
	echo -e "\n build: creates a Website using hugo \n clean: Cleans the files and directories in dist directory \n Post: Posts using environment variables \nhelp: Show this help usage"
