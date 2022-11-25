## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a language or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
Git is an open source program that tracks changes in text files. Written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.

2. What is the difference between Git and GitHub? 
GitHub is a repository cloud storage host for version control and collaboration and Git is an open source program for tracking changes in text files, or essentially the commands we run in the Terminal.

3. Why do we create a branch? 
To maintain stability while isolated changes are made to code.

4. What is the purpose of a Pull Request?
It lets others know about changes that were pushed to a branch in a repository on GitHub. Once a pull request is opened, potential changes can be discussed and reviewed with collaborators and have follow-up commits added before any changes are merged into the main branch.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main. 
git checkout main

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
'git fetch' Download objects and refs from another repository. 
'git merge' updates local branch with its remote version.
'git pull' merges into the current branch.

7. What is a merge conflict?
When multiple changes are made to the same line of a file, and the system can't decide on which one to incorporate in the final merge.

8. How do you resolve a merge conflict?
Through GitHub, by using the conflict editor. OR through Git, by using a command line and a texteditor.