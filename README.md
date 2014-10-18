GitHub Dorkshop
===============

For learning GitHub and Git!

## Resources:
- [**GitHub App for Mac Help**](https://mac.github.com/help.html)

- The [**dtbootcamp**](https://github.com/dtbootcamp/getting-started-with-git-and-github) GitHub organization has a more in-depth Git tutorial then this.

- The [**Mou App**](http://25.io/mou/) is handy for editing markdown files. 

- You can use [**Github pages**](https://pages.github.com/) for hosting a pre-built website.  

- [**Jekyll**](http://jekyllrb.com/) a CMS free blogging platform you can use with a `gh-pages` branch.

- [**Git - the Simple Guide**](http://rogerdudler.github.io/git-guide/) for using Terminal with Git.



## Using Git on the Terminal

*These are the most common commands you will use when working with Git and GitHub  
with the Terminal App on Mac OS X.*

- to copy a remote repository: 
  
  `git clone https://github.com/username/repository_name.git`
  
  - then do `cd repository_name` and do the following:

- to check what changes Git is aware of:

  `git status`
  
  - you can do this whenever

- to push your changes to GitHub do these 3 commands in this order:
  1. add the file to the index:  
	`git add file.name`  or `git add *` to add all untracked files.
	
  2. commit the file with a message:  
	`git commit -m ‘describe what you did’`  
	
  3. push the commit to Github:  
	`git push origin branch-name`

- to grab any changes to your repository on GitHub that were made by someone else  
  (do this before pushing):

	`git pull`

- to merge your changes with someone elses:
	
	`git merge origin branch_name`

- For free web hosting: create a gh-pages branch:  

	`git checkout -b gh-pages`
	
	- this will also switch you from your current branch to the gh-pages branch.  
	- to go back to another branch do: `git checkout branch-name`
	
- To delete a branch:

	`git branch -d branch-name`





