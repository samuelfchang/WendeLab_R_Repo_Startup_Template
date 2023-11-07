# Repo_Startup_Template
 Template for new repositories in the Wende Lab
 
Instructions: 
 1. Create a repository via Github Desktop: Set local path to your WD for the analysis, initialize with a README file, Git Ignore setting for R. Note: add "input" "output" and "results" folder to git ignore (see gitignore file in this repo for more details).
 2. Create a R project in the repo.
 3. Create .rmd for R code (with template header-see included .rmd template)
 
Tips: 
1. to show hidden files on Mac: cmd + shift + period key
2. cmd + shift + c = quick comment/uncomment chunks
 
Git/sync/code knitting workflow: push to Git at end of day, knit at end of an analysis question. After knit, save as new .rmd file with new data. Clear environment and delete output folders before knit to make sure there isn't a missing variable in code.
