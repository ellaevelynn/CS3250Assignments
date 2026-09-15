# Overview

The goal of this assignment is to assess your understanding of basic Git commands.

For each scenario described below, write the sequence of Git commands you would use to complete each scenario. 

# Scenario 1

Jane wants to use Git to manage the versions of a paper stored in a file named **paper.txt**. She begins by creating a folder named **sc1** [1] and initializing a new Git repository in that folder [2], making sure that the initial branch is named **main**. Next, she creates **paper.txt**, makes some changes to the file, and commits those changes [3]. Jane then makes additional modifications to **paper.txt**. After discussing the paper with her advisor, she decides to restore **paper.txt** to the version stored in her initial commit [4].

```
Write the Git commands below: 
1. mkdir sc1 && cd sc1 
2. git init -b main
3. git add paper.txt
    _(...Jane makes edits before committing changes)_
3.5 git comit -m "Initial commit"
    _(...Jane makes additional edits and does not commit them)_
4.  git checout HEAD -- paper.txt
```

# Scenario 2

Joachin wants to use Git to manage the versions of a new Python package he is developing. The project files are located in a folder named **sc2**. To prevent sensitive information from being tracked by Git, he creates a **.gitignore** file and adds **.secrets** to it. Next, he initializes a new Git repository in the **sc2** folder [1], making sure the default branch is named **main**. He then stages all project files [2] and creates the initial commit with the message "project kickoff" [3]. Assume a GitHub repository already exists at "https://github.com/joachin/sc2". Joachin configures this repository as a remote named **origin** and pushes the local **main** branch to the remote **main** branch [4].

```
COPY AND PASTE .gitignore here
```

```
Write the Git commands below: 
1. 
2.
3.
4. 
```

## Scenario 3

Bob is collaborating with Sam on a project named **sc3**. Assume a GitHub repository named **sc3** already exists at "https://github.com/bob/sc3", and Sam has been added as a collaborator. Bob clones the repository to his local machine [1]. He then creates a file named **README.md** containing information about the project. After staging the file [2], Bob commits the changes with the message "Add project README" [3] and pushes the local main branch to the remote repository [4].

After cloning the repository, Sam creates and switches to a new branch named **feature/search** [5]. He creates a file named **main.py**, stages it [6], and commits the change with the message "Add search feature" [7]. Sam then switches back to the **main** branch [8] and pulls the latest changes from the remote repository [9]. After synchronizing his local copy, he merges **feature/search** into **main** [10] and pushes the updated **main** branch to the remote repository [11].

```
Write the Git commands below: 
1. 
2.
3.
4. 
5.
6.
7.
8.
9.
10.
11. 
```
