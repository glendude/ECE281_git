# Git Nibbles 

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
	- I can work and commit changes while disconnected from the network 
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

Before you can create your own open-source repository you must create an account
on [github](www.github.com).

Now we can continue to follow [Todd's amazing Git tutorial](http://ece382.com/datasheets/git_tutorial.html) starting with adding a remote.
- This portion of the tutorial will guide you through:
	- Configuring git to ```push``` data to your remote
	- Cloning your repositories on different machines
	- Forking repos that aren't your own 

Welcome to the open-source community!!

## Open Source

*Forked from ECE382.com* git and Github put you in a great position to use open
source work in your project or make contributions to open source yourself.

Before you re-invent the wheel, a great first step for most projects is to see
if there is open source work available you can use or build on - Github has
great search features for this. *fin*

The open source community gives you access to vast amounts of software to
include arguably [the most influential](http://readwrite.com/2011/08/25/as-steve-jobs-steps-down-linux#awesm=~oDw0XRaN4ItIYV) and [most powerful repo of our age](https://github.com/torvalds).
Open source contributors are, in general, people who like building cool things. 
The community is also wonderfully results-oriented, evidenced by the ubiquitous
and apt retort to any non-constructive criticisms: "where's your pull request?".
