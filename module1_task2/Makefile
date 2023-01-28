MAKEFILE_LIST= "build, clean, post, help"

build:	## Creates a Website using hugo
	hugo

clean:	## Cleans the files and directories in dist directory 
	rm -rf dist/*
	

post:	## Posts using environment variables
	hugo new posts/$(POST_NAME).md
	sed -i 's+title.*+title: "$(POST_TITLE)"+g' content/posts/$(POST_NAME).md

help:	## Show the help for every target
	@fgrep -h "##" $(MAKEFILE_LIST) | fgrep -v fgrep | sed -e 's/\\$$//' | sed -e 's/##//'