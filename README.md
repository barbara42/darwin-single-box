# Dar_One Backend
MITgcm and Darwin equations to power Dar_One [TODO: link] 

# Contributing 

We have three main branches
- master
- test
- dev 

All other branches are feature branches. Once a feature has been implemented, tested, and documented you can make a pull request to merge it into the `dev` branch. From there, it will be deployed (hopefully in the future). If the deploy passes, it will automatically get merged into the `test` branch. 

This branch is for people who deeply understand the code and want to beta test new features. Once apropriate testing has been created, there will be a merge planned for `master`. 

`master` is the most recent and stable version of the code. This branch will be deployed to cloud computing resources and publically available. 


## Feature Branch Descriptions
Conserve Branch: modifying default input files
to have it run fast (don't write super frequently) 
- write diagnostics every two months (5184000 secs) 
- run for one year (2880 iterations) 
