# 1. Install GIT:
The first step is to download the GIT client onto your machine:  https://git-scm.com/download/win
   This will make the GIT client commands available to you.

Set a global user name and password in GIT.  This will let GIT Hub know who you are when you check in/out.
$ git config --global user.name "Keith Bohm"
$ git config --global user.email "test.test@gmail.com"


# 2. Initialize Setup w/ GIT
The initial set up in GIT is to associate a folder w/ a repository GIT.  The following are the common GIT commands to get you started:

git config:
    --list : show existing configuration items.  User/Email should be in the list.

# 3. Clone a Branch: This will be the most common way of doing things in a company, but learn step #4 as well.
git clone:
    The git clone command is used to create a copy of a remote Git repository on your local machine. This command not only copies the files from the remote repository but also establishes a connection between your local copy and the original repository

    example: git clone [url] .
    
git config

git remote -v : lists info about the repo.

git branch -a : lists all the branches locally and remotely.


# Git Init: This is how you'd initialize a repo locally, then push it up for the first time to GIT. This is more for Ground up Dev.
git init: (this is for local use. see git clone for more common use.)
    The git init command is used to initialize a new Git repository. 
    
    note: The hidden .git folder that contains the data structors.
    note: To initialize an existing repo, the git clone is often preferred.

    example: git init

.gitignore:
    The git ignore file will exclude 
