# git-tasks
AGV introductory tasks: [Software Tasks ](https://docs.google.com/document/d/16Qf7ExDJJXtkyY7mXiqrvizdUl02AX06gCXuiGcpu0Q/edit?usp=sharing)
# Git - Resources and Tasks

- Resources:
  - [Interactive Git Learning Platform](https://learngitbranching.js.org) No need for doing the advance topics in both remote/main.
  - [Git Cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet/)
- Extra Resources 
  - [Reference + Extra Reading](http://gitimmersion.com/index.html)
  - Book on Git- [Pro Git](http://git-scm.com/book/en/v2)
  - [Version Control (Git)](https://missing.csail.mit.edu/2020/version-control/)

This file is written in the [Markdown format](https://guides.github.com/features/mastering-markdown/).

## Task 1

Add your name to this list below 'Entries'.

- **Fork the repo, create a new branch (called Task1), make changes and send a pull request**
  - [This article](https://help.github.com/articles/using-pull-requests/) should give you a good idea of what pull requests are how to use them.

Your entry should maintain alphabetic order and it should be in the format:
   * ` your name [username](http://github.com/username)`.  


- Your Pull Request must have only one commit (if there are multiple commits, you should squash them). 
- Only one file should be there in the diff of your Pull Request.

### Entries
Gayathri Anant [Gayathri2004Anant](https://github.com/Gayathri2004Anant)\
Khushboo Nayak [khushboo-nayak](http://github.com/khushboo-nayak)\
K. Tharun Selvam [tharun-selvam](https://github.com/tharun-selvam)\
Sachish Singla [sachishs-15](https://github.com/sachishs-15)\
Devodita Chakravarty [devodita](https://github.com/devodita)\
Pranaya Chowdary [pransverse](https://github.com/pransverse)\
Swaminathan S K [SwaminathanSK](https://github.com/SwaminathanSK)\
Ayush Kumar [meush](https://github.com/dsawebappayush)\
Anjali S Vallakudath [Anjali-sv](https://github.com/Anjali-sv)\
Ahwaban Mukherjee [ahwaban](http://github.com/ahwaban)
Raj Aryan [Raj06aryan](https://github.com/Raj06aryan) // change


## Task 2

After all of you send a Pull Request, I'll add my name to 'Entries'. 

- Configure a remote that points to the upstream repository in Git to sync changes you make in a fork with the original repository. 
- Try to merge upstream changes into your downstream repository. You'll get 'merge conflicts'. 
- [Remove the merge conflicts](https://help.github.com/en/articles/resolving-a-merge-conflict-using-the-command-line) and create another pull request.


## Task 3

- Create a new branch (called Task3) in your fork. Add a dummy piece of code and push it to the current branch. 
- You've now realized that you pushed something wrong. Instead of removing the commit altogether, **push another commit that will undo the changes made**. 
- Create a pull request.

Why not remove the commit altogether? \
This prevents Git from losing history, which is important for the integrity of your revision history and for reliable collaboration.

##  Task 4

- Create a new branch (called Task4) in your fork. Add a dummy piece of code and push it to the current branch. 
- You've now realized that you've pushed something that is not only wrong but also stupid. You regret it so much that you want the commit to vanish altogether. 
Use reset to **remove this commit**. 

## Task 5

- Create a new branch (called Task5) in your fork. Add a dummy piece of code and commit it to this branch. Do this 5 more times. 
- Now you want to **remove some intermediate commits**. Remove commit no. 2 and 4 using rebase.
- Push all the commits into Task5 and create a Pull Request.
  

Some guidelines for the tasks:

* Your Pull Request must be rebased on the latest master.  
* This commit must have a message that is explanatory. For eg. for Task 1: `Add name to README (Name here)`.
* Name of the PR must be informative. For eg. for Task 1: `(Task1) Add my name to the README (Name here)`.
