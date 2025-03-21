# DSCI 310 Lecture: Quarto
### Date Created: 2025-03-20

## Concepts covered

- Making your own website through quarto
- Helpful terminal commands
- 

## Helpful Information Learned / Notes

##### Definitions

CLI = Command Line Interface

##### Commands that you can use on the command line for information and help:

`which ...`
  * `which quarto`
  * `which python` 
  * `which make`
  * Lets you know what type of version you may be running and where

* `--version`
  * `quarto --version`
  * Lets you check the version
    * thats why docker is nice, it lets you version lock things, but that is also why you need to be careful as things may work differently than your virtual machine

* `--help`
  * `quarto --help`
    * Lists information and possible commands you can use
    * `quarto create`: helps create quarto documents, websites, manuscripts, etc.
      * gives you a base outline of all the info
    * `quarto preview`: will show what it looks like rendered


   # other

  * `git checkout --orphan gh-pages`: creates a branch that has no ties to the main branch, it works on its own
  * add a `.github/workflows/publish.yml` file so that you can make changes and it will automatically render and publish the website without even needing quarto on your computer
  * look more into quarto slides/presentation (more common in tech conferences, that way you can easily share code by just sharing the repo)
  
