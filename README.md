# Lab11

## Objective:
The objective of this Lab is to understand the basics for SCM

## Task
1. Make a repo on github (you need to make an account)
1. clone the repo to linux working env
1. Copy into the repo with some code (just grab any lab, or even my starter code).
1. Add the code to the repo 
  1. git add .
  1. git commit -a
  1. git push
NOTE for the push you will need to setup github token (classic)

Ok now we have a simulate developement ENV, and have show how to push to main branch.  THis is not typical in industry.

1. git checkout -b "some cool name you come up with here"
1. modify any of the source file with any change
1. git add <file you modified>
1. git commit -a
1. git push --set-upstream origin "some cool name you come up with here"
  
OK now we have to go make a pull request on the website
  
1. goto your repo on github
1. Make pull request
  
No normally there is some protections on randos trashing your repo, but let's assume it passed
  
1. Close your merge reqeust
  
Almost done now let's mimic an active branch with mulitple cooks 
  
1. git checkout -b "another  cool name you come up with here"
1. Make a change to source file
1. Now using the web view, from main branch edit that source file with a different change (a comment change) but on the same line
1. git add .
1. git commit -a
1. git push
1. Make the merge reqeust and see we have a merges
1. Resolve merges (see the advice on merge request page)
1. Get your code to the repo
  


## Alt Task

If you have already submitted to a repo and have done a pull request that has been merged.  You can post the link the repo, your user name, and the pull request showing me that it was meged.
