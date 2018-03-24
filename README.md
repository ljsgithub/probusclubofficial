# Probus Club Website
## Github & Git basics Reminder

### Installing Git
> Go to the [github download page](https://git-scm.com/downloads) and download the correct version for your OS

### Using Git 
If you're starting a respository for the first time, right click the folder where you wish to create it and click "Git Bash Here"

![Image of Git Bash](Screenshot_1.png "Example of Git Bash")

If you've done this correctly, you should see a terminal similar to cmd, it will look something like this:

![Image of Bash terminal](something.png "Git Terminal Example")

### Commands

#### Intializing your git repository - just don't blow it up

> git init 

* In order to intialize a git repository we must start with this command, it will create a .git folder (its hidden by default) which contains the relevent files
* If you've cloned this respository, there's no need to run this command as the repository already exists

#### Config commands - telling git all your secrets

> git config --global user.name [name]
    
* In order to push to a remote repository you must enter your name, it will be stored in a config file as shown above.

> git config --global user.email [email]

* same as above your email is required, it will also be stored in the config file

> git status

* This will show all the files that git hub has detected, if you haven't made any commits they will be highlighted in red as they are not in the staging area (ready to be committed)

![Image of Git Status](Screenshot_2.png "Example of Git Status")

#### Adding files to the staging area - woo the fun stuff

> git add [filename] or git .

* This will add files you wish to commit to the staging area, if you wish to add all of them at once you can do git .
* If you've added them correctly, you should now see the files highlighted in red are green

