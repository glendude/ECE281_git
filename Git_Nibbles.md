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
- How to get started using Git
- How to get started using Github 

## Why?

Because: version control 

## Version Control

- Lots of Version Control Software
   - CVN
   - SVN
   - Git
   - Mercurial
- We'll focus on Git because: 
   - DVCS
   - [Snapshots, not differences](http://git-scm.com/book/en/Getting-Started-Git-Basics)
   - Github

### Version Control is good for backing up data right?

1. [Have you googled it?](http://blog.codekills.net/2009/12/08/using-git-for-backup-is-asking-for-pain/)
2. Not necessarily
	- Git is designed to track code
	- Git will not preserve file ownership

## How did we get here?

- [Linus Torvalds used
  Bitkeeper](http://www.infoworld.com/t/platforms/linus-torvalds-bitkeeper-blunder-905) (first DVCS) when developing Linux
- Bitkeeper worked great! Linus = :)
- Bitkeeper was proprietary. [Richard Stallman (GNU/FSF) = :(](http://developers.slashdot.org/comments.pl?sid=145174&cid=12154255)
- Linus wrote git and released it as free and open in 2005 

## Git vs Github

Git = Version Control Software (creates repos)

Github = Free hosting service for repos created by Git

## Your first local repository!

Software you will need:
- Running Linux? Chances are you already have everything you need!
	1. git
	2. Text editor
- OSX?
    1. You'll probably need to [download git](http://sourceforge.net/projects/git-osx-installer/) unless you have xtools...
    2. You probably already have a good text editor
- Windows?
    1. You'll definitely have to [download git](http://msysgit.googlecode.com/files/Git-1.8.4-preview20130916.exe)
    2. A text editor like gvim or Notepad++

Time to follow [Todd's amazing Git tutorial](http://ece382.com/datasheets/git_tutorial.html)
- This tutorial will walk you through how to:
	- Configure git
	- Create a repository
	- Create a file to track
	- Add the file to the repository
	- Commit changes
	- Revert to prior versions
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

