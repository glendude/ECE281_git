# Git Nibbles Exercise

Do you:

1. Want to get started using git? 
2. Want to make your own open-source repository on Github? 
3. Not know what 1. or 2. even mean?

I'm here to help get you started. Along the way I'll introduce you to the world of version
control and open-source software development...exciting! 

## Overview 

During the next hour I'll present:

- The reasons these tools exist and why they make our lives easier
- A condensed history of git and Github's place within the general GNU movement 
- Git vs Github
- How to get started using git
- How to get started using Github 

## Why?

- Version Control
   - CVN
   - SVN
   - Git

## How did we get here?

## Git vs Github

## Your first local repository!

## Your first open-source repository!

## Step-by-Step Process

- Navigate to the repo: https://github.com/sivwizinbiznilva/ECE281-student-accounts 
- Now you need to **fork** the repo so you have your own copy to work on
    - Push the fork button at the top right of the screen
    - Now you have your own copy!
    - You should be redirected to a duplicate repo in your own account
- Now you need to **clone** the repo to your computer so you can make changes
    - Note the URL in your browser - this is the address of the repo
    - In Git Bash, `cd` to the directory where you want the repo stored and type `git clone REPO_URL`
        - Now you've got a copy of the repo on your local computer!
- Time to make your changes!
    - `cd` into the directory that was created - probably named `ECE281-student-accounts`
    - Open your README.md in your favorite text editor
        - Notepad
        - vim
        - Word
    - Update your name to include a link to your repo!  Format is important!
        - `- [YOUR NAME](YOUR REPO URL)`
        - `- [Capt Silva](https://github.com/sivwizinbiznilva)`
- Let's make sure git is tracking our changes
    - Type `git status`
        - We should see that README.md has been modified
- Time to commit our change!
    - Type `git commit -am "<descriptive commit message>"`
        - This tells git to add and commit all the files currently being tracked that have changes
- Let's push our changes back up to Github
    - Type `git push`, enter your username / password
    - The changes should now be reflected in your repo on Github
- Now you need to ask me to merge the changes back into my branch - this is called a **pull request**.  You want me to pull changes into my branch from you.
    - Navigate to your fork of the repo on GitHub
    - Click the Pull Request button at the right of the screen.
    - Click the New pull request button at the right.
    - Click the "Click to create a pull request from the comparison" link at the top.
        - Your commit message should be populated into the title of the request.
        - If you want, you can add more comments below.
    - Click Send Pull Request.

You're done!  I'll go in and merge your changes - assuming you didn't do anything bad...

