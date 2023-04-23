# Introduction to Pandas (Part 1) 


Hello everyone and welcome to Learning with Jelly! This repository is used as a supplement to my 
Learning with Jelly Tutorial on an Introduction to Pandas.  [YouTube Channel](https://www.youtube.com/@learningwithjelly/videos)


## Steps to Connect to the Repo
These steps you should only need to do at set up:

1) **FORK** this repository, creating copy on your own GitHub account
In order to fork, look to the upper right of this page, between 'Watch' and 'Star'. From that drop down you should see an option to create a new fork.

 That will open a new page, and you'll be given an option to select a new owner for the fork. Select your own account. Ignore the other options.

2) Add the original version as the upstream (to pull future changes)

`git remote add upstream https://github.com/aspratle/IntrotoDataAnalytics_LearningwithJelly.git`

2) **CLONE** your fork to your local computer
To do this, navigate in your terminal to an appropriate folder. I recommend you have an overall 'Data_Analytics' folder either in your documents or on your desktop. Once you're in the right place, you'll need to input the following command, replacing '[yourusername]' with your Github account:

`git clone https://github.com/YOURUSERNAME/IntrotoDataAnalytics_LearningwithJelly.git`

3) If you want to push your changes from your local to the forked version of the repo use these steps.  *BE SURE YOU ARE PUSHING TO YOUR FORK AND NOT THE ORIGINAL*:

    - git add [filename]

    - git commit -m 'message here'

    - git push

## Whenever you want to pull new changes:
Grab the changes from the upstream repo

`git fetch upstream`

Merge new changes onto your local repo

`git merge upstream/main -m "meaningful message about what you're updating"`
