## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
    Git is a version control system for software development. 
2. What is the difference between Git and GitHub?
    GitHub is a web based tool to share and manage git repositories (repos).
3. Why do we create a branch?
    We create a branch to edit, add, or remove code from our project while preserving a previously saved state to which we can return should the need arise. 
4. What is the purpose of a Pull Request?
    The pull request tells that manager of the project that there are changes ready to be added into the main body (branch) of the code. 
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
    git checkout New_Branch, or in this example
    git checkout FIRSTNAME-LASTNAME
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    'git fetch' shows if there have been changes to the remote repo without making changes to the local one. It creates a local record of remote changes.

    'git merge' brings changes that have been fetched from the remote repo into the local repo. 

    'git pull' merges changes from the remote repo directly into the local repo without fetching them first. 
7. What is a merge conflict?
    A merge conflict occurs when changes have been made to both repos in the same place. In this situation, git can't determine which change should remain in the merged repo. This can also occur when a file has been changed in one branch and deleted in the other.
8. How do you resolve a merge conflict?
    The procedure is somewhat different depending on whether the conflict emerges from two files being changed on the same lines or a file being changed in one branch and deleted in the other. However, in both cases the developer needs to determine what the final outcome of the merge should be, make appropriate edits to the files/file structure, and commit the changes to the new merged branch. 