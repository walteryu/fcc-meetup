# Free Code Camp Meetup - Software Engineering Basics

## Unix, Bash and Github

### Homework 1

The purpose of this assignment is to reinforce learning and practice from the FCC workshop. Collaboration is definitely encouraged, so please partner with fellow FCC members to complete this assignment! Learning to code also means learning about how to communicate and collaborate with other programmers.

Learning objectives are as follows:

1. Basic understanding of Unix, Bash and Git; their applications and importance
2. Complete recommended reading and bookmark for future reference
3. Create your Github account, link to your machine and deploy first repository

## Exercise 1 - Review Presentation

Review workshop [presentation](https://docs.google.com/presentation/d/17yxFELnl686uBH327VTvB-uP9B7j0MqmxSHly0eIdLA/edit?usp=sharing), review tutorials and try out the tools/resources (e.g. Glitch, Kaggle and Google Colab)

## Exercise 2 - Complete Installations

If not already completed, then finish installing the command line and Git:

Command Line - Verify installation by executing some Unix utilities, e.g. `cd`, `ls`, etc.
1. [Windows 10](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/)
2. [Windows Cygwin](https://www.cygwin.com/)
3. [Cmder](http://cmder.net/)
4. Mac and Linux - Open Terminal App

Git - Verify installation by typing `git` into command line; output should return help page.
1. [Git SCM](https://git-scm.com/downloads)
2. [Git for Windows](https://gitforwindows.org/)
3. [RailsBridge](http://installfest.railsbridge.org/installfest/)

## Exercise 3 - Command Line Practice

1. Read and complete exercises in Chapter 1 of Learn Enough Command Line to be Dangerous [ebook](https://www.learnenough.com/command-line-tutorial/basics); browse remaining chapters and bookmark for future reference.
2. Refresh on the concept of the home and root directories; navigate to them from the command line:
  * Home directory: `cd`, `pwd`
  * Root directory: `cd /`, `pwd`
3. List contents of each directory: `ls -al`

## Exercise 4 - Github and SSH Keys

Login to your Github account and add your SSH key:
1. If not already completed, then create an [account](https://github.com/join)
2. Follow [instructions](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/) to add your SSH key - it will link your account with your machine
3. Briefly review the [Github Guides](https://guides.github.com/activities/hello-world/) and [YouTube Channel](https://www.youtube.com/GitHub).

## Exercise 5 - Git Practice

1. Read and complete exercises in Chapter 1 and 2 of Git SCM [ebook](https://git-scm.com/book/en/v2); browse remaining chapters and bookmark for future reference.
2. From home directory, create your source code (src) directory:
  * Home directory: `cd`, `pwd`
  * Make directory: `mkdir src`
  * Enter directory: `cd src`
  * Show contents: `ls -al`
  * What does `ls -al` return?
3. From src directory, clone this directory using `git clone https://github.com/walteryu/fcc-meetup.git`
  * Enter directory: `cd fcc-meetup`
  * Show contents: `ls -al`
  * Show path: `pwd`
  * What does `pwd` return?
4. Make a change to the README.md file, then commit changes:
  * Show changes: `git status`
  * Stage changes: `git add README.md`
  * Commit changes: `git commit -m "update readme"`
  * Sync with repository: `git pull origin master`
  * Push changes: `git pull origin master`
5. Refresh your repository on Github to see change

## Exercise 6 - More Git Practice

1. Add your src folder to your text editor; for Atom, select "Add Project Folder" from the file menu
2. Within src folder, create a new directory named, "fcc-hw1"
3. Within src/fcc-hw1 folder, add new README.md file
4. Use the text editor to create the files
5. Enter text into file, then save it
6. Follow changes in Exercise 5 to show, add and commit your file
7. Make sure you have added your SSH key to Github
8. Log into Github and create a new repository using this [tutorial](https://help.github.com/articles/create-a-repo/) also named "fcc-hw1"; follow tutorial instructions to "push from existing repository"
9. Navigate to your src/fcc-hw1 folder, then follow Exercise 5 to push this repository into your Github Account
10. Verify that the push was successful by visiting the repository in your Github account

## Exercise 7 - FCC Guides
Review and complete several topics from the Free Code Camp [Guides](https://guide.freecodecamp.org/).
