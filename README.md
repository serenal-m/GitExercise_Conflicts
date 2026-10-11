MERGED EX1

# GitExercise_Conflicts


## Purpose
To teach you to deal with git merge conflicts in 
- Jupyter Notebooks
- on Datahub using graphical notebook based tools

The instructions here are specific to the COGS 108 Datahub setup. 

Note that this is different than your previous exercises... they were on GitHub (not on Datahub) and there were no graphical diff tools in use



## Problem overview

This repo contains two branches: main and ex1. There is a single line text conflict in one cell between the two branches, as well as other line differences that do not conflict.

Below is a graph of the commit situation in the repo right now... each * indicates a commit and the lines show the evolution of the repo over time


Another common project workflow is if there's a red dot on pull (down arrow) that means someone else made changes to the remote that you don't have.  Pull operations need to be done before push operations... so if someone changed the remote after your clone but before your push you will have to pull first, merge, and resolve any conflicts before you are allowed to push your changes to remote.  We didn't have to do that here, but its a very normal workflow for your projects.
