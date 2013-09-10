$ mkdir ~/is-206
# Creates a directory for your project called "IS-206" in your user directory

$ cd ~/is-206
# Changes the current working directory to your newly created directory

$ git init
# Sets up the necessary Git files
# Initialized empty Git repository in /Users/jensh11/is-206/.git/

$ touch README
# Creates a file called "README" in your Hello-World directory

$ git add README
# Stages your README file, adding it to the list of files to be committed

$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"

$ git remote add origin https://github.com/jensh11/is-206.git
# Creates a remote named "origin" pointing at your GitHub repository

$ git push origin master
# Sends your commits in the "master" branch to GitHub
