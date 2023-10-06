# Reading Questions

## Project workflows; Bryan (2017)

What problems can setwd() cause in your scripts and how do RStudio projects address them?

1. Primarily, setwd() doesn't do well when you try to run your code elsewhere, or later on when you are working on a new computer. 
2. The second issue is that it can open the door to accidentally mixing work from multiple projects that you may be working on at one time. 

When you call rm(list=ls()), what is removed from your environment? What’s left over that restarting your R session would remove? What’s the keyboard shortcut for restarting your R session?

- The only thing removed from your environment is user-created objects. Things like packages, working directory, and non-default options will remain.
- Session > Restart R or Command+Shift+F10 for Macs

## Version control; Braga et al. (2023)

Imagine you’re working with a few collaborators on an analysis. Come up with two examples of Issues you might open. How would using Issues differ from communicating over email?

- I might suggest some code changes to something a collaborator wrote, or propose an additional analysis that I would like included. 
- By using *Issues* I will be able to assign these tasks to specific team members and give the individual tasks specific labels. Additionally, GitHub issues can only be closed by repo admins, which reduces the chances of an edit or suggestion getting lost in a morass of emails between collaborators. 

What are three ways GitHub features can promote open science practices?

1. Publishing your workflow (given that it is reproducible) provides readers with important details important in discussions of results and analytical methods.
2. GitHub allows *all* collaborators to have input on the analysis, rather than just one of many people having eyes on it. Thus making mistakes more readily identified (before publication). 
3. GitHub repos can easily be made private/public. This allows for easy sharing once there is no longer a need for privacy. 



