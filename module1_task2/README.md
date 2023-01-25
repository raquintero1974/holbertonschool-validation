# Introduction to DevOps: Automate Everything to Focus on What Really Matters

## Learning Objectives

This project aims at showing use cases where a DevOps mindset is bringing value to a software project by automating it, which decreases the amount of manual work and increases the development speed. It focuses on why automation is useful and helps speeding a development lifecycle.

After this project, you should be able to:

- Understand the value of automating tedious tasks
- Define a development lifecycle
- Automate shell-like tasks with Make, and/or shell script
- Be aware of tools dependencies and the value of reproducing environment
- Build static HTML website from Markdown code using Go-Hugo

## Prerequisites

### Concepts

You should have a basic knowledge of the following concepts:

- Shell terminal basics, using command lines:

- Navigating in a Unix file-system
- Understanding how stdin/stdout redirection and piping
- Showing and searching the content of a text files
- Defining and using Environment Variables
- Adding command lines to your terminal using the `apt-get` package manager and/or with the `PATH` variable
- Writing and executing a shell script
- Git with the command line (and also a graphical interface)

- Retrieving or creating a repository
- Manipulating changes locally with Git’s 3 steps process (workspace, staging, history)
- Distributing changes history with remotes repositories
- Make/Makefile usage:

- Executing tasks through make targets
- Default target and PHONY target
- Makefile’s variables and macro syntax

### Tooling

This project needs the following tools / services:

- An HTML5-compliant web browser (Firefox, Chrome, Opera, Safari, Edge, etc.)
- A free account on [GitHub](https://intranet.hbtn.io/rltoken/u6680ax-ghu8v-AsFSDbSA "GitHub"), referenced as `<GitHub Handle>`
- A shell terminal with `bash`, `zsh` or `ksh`, including the standard Unix toolset (`ls`, `cd`, etc.) with:
- GNU Make in version 3.81+
- Git (command line) in version 2+
- [Go Hugo](https://intranet.hbtn.io/rltoken/IBEctMMx9WYT-U-G5oIv-g "Go Hugo") v0.80+
- The student needs to be able to spawn up a clean Ubuntu 18.04 system. Therefore [Docker](https://intranet.hbtn.io/rltoken/4-LomWsN4dV31c-IwVMwgw "Docker") is recommended with NO prior knowledge.
- A text editor or IDE (Integrated Development Editor) of your convenience (Visual Code, Notepad++, Vim, Emacs, IntelliJ, etc.)

## Story

Congratulations!

It’s your first day at “Awesome Inc.” as a software engineer. This company is currently experiencing fast growth and hired you to work on their web services.

Your predecessor left to travel the world, and the expectations are high on your ability to help "Awesome Inc.” to grow a culture of collaboration with a technical mindset, while managing their existing web services. That’s exactly what DevOps is about!

## Reference Readings

- [Go Hugo Quickstart](https://intranet.hbtn.io/rltoken/jQyxwX-NaGuIDMpbklREZQ "Go Hugo Quickstart")
- [Git SCM Book](https://intranet.hbtn.io/rltoken/KVwKi4WrASyHYE3BGnsbzg "Git SCM Book")
- [GNU Make Docs](https://intranet.hbtn.io/rltoken/YUo3ljJIf8QXZHL1gXPuEQ "GNU Make Docs")`

## Prerequisites

- You must have installed hugo
- you must have installed Git
-

## Lifecycle

There are three steps on llifecycle:

### Build:

1. Create the [directory structure](https://gohugo.io/getting-started/directory-structure) for your project in the `desired` directory.
2. Add and configure the theme for the site
3. Start Hugo’s development server to view the site.
4. Add a new page to your site.
5. Add some [markdown](https://commonmark.org/help/) to the body of the post, but do not change the `draft` value.
6. Save the file, then start Hugo’s development server to view the site. You can run either of the following commands to include draft content.
7. With your editor, open the [site configuration](https://gohugo.io/getting-started/configuration/) file (`config.toml`) in the root of your project.

## clean:
Cleans the files and directories in dist directory 
## post:
Posts using environment variables
## help:
Informs about each target
