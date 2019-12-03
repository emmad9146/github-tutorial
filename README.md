# GitHub Tutorial

_by <Emma Doherty>_

---
## Git vs. GitHub

GitHub is a resource that allows you to collaborate effectively with partners. It also allows people to make their work availible to anyone studying that topic. They can use one anothers work to teach themselves, or to simply find something to use as a starter code to improve upon or elaborate on someone else's work. You can track your changes visually with GitHub and see exactly what you did to get to one place or what mistake you made and how it got you stuck in one spot. GitHub also helps to manage the repositories that you create using Git.

Git is a system that allows you to keep track of and look back at your older work and coding history. Git is used in the projects that GitHub oversees and directs where these projects get posted on to by the user. Git doesn't require GitHub and keeps a "snapshot" or picture of your code. 

---
## Initial Setup

For Github Initial Setup, you need to first do "mkdir *insert name*".
This makes the directory. You then have to cd into this directory. You do so by entering "cd *insert name*". Now you're inside this directory. Then you need to put "git init" to initialize this code. 

---
## Repository Setup

To set up a repository you must complete all of the Github Initial Setup steps, and additionally enter "git remote add origin <git@github.com:YOURACCOUNT/YOURREPO.git>". Doing so will identify what repository you are uploading your work to. 
 After which you must enter "git pull origin master". Doing this will allow you to pull from your own repository, or the repository that you forked the code from. Also known as the "Master". Then you enter "git add ." to log what changes or addons you applied to the code. Finally you enter "git commit -m "YOUR COMMENTS" and "git push origin master" to finalize and push your changes to your GitHub. 

---
## Workflow & Commands

The GitHub Commands are the lines of text that you add to your code to prompt a result.For example, in order to inform my local repository of my most recent commit, I would enter "git pull".
 
 On GitHub, Workflows are processes that you can set up in your repository. Workflows are most commonly used to test, release, or pull from any project on GitHub.
---
## Rolling Back Changes
    On GitHub, "Rolling Back Changes" essentially just means to undo or revert a commit tha you didn't intend on committing. There are a few different ways to do so. The first option you have is to right click the commit and then click revert commit. Then click history, followed by the commit that you would like to revert. Another option you have is to use the command "git revert". You will find either of these method to be equally effective. 
    
    
    
    