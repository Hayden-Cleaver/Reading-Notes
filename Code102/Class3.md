# Git

1. What is Version Control?

- A Version Control System (VCS) allows you to track changes to a file and saves different versions of said file.  This allows you to easily view changes between versions and to revert to a different version if need be.

  #### Local Version Control

  - A database on a hard disk that stores changes to files.

  #### Centralized Version Control
  
  - A single server storing changes and file versions which can be accessed by multiple clients.This eliminated the need for storage on all local databases and allowed for a much easier collaboration process / divvying up of tasks.

  #### Distributed Version Control
  
  - Similar to a CVCS except that it uses mirrored repositories, which allows for back up data.  This improves upon the CVCS by eliminating the server as a single point of failure.  This also allows for even more flexibility in working on simultaneous tasks (as long as it's correctly cooordinated).

  #### What is Git?

  - Git is a DCVS that creates a snapshot of a file and stores a reference to it everytime that you commit (save) it.  If no changes have been made to the file, Git will just store a reference to the previous version.
  - Git utilizes local operations since most info will be found on your local resources.  This means that there isn't lag time searching/fetching information from a server and that you can work on a project offline.

  #### Git Stash

  - `git stash` temporarily removes changes and stores them, giving a clean slate on your working directory
    - If you want to work on those changes again, use `git stash apply` to retrieve the changes.

2. What is cloning in Git?

   - Cloning creates a copy of a Git repository from a server.  This copies all versions of all files for a project and creates a new directory.

3. What is the command to track and stage files?

    - Add: Tracks a file so it can be staged and then committed.

4. What is the command to take a snapshot of your changed files?

    - Commit: Saves the changes made to the file.

5. What is the command to send your changed files to Github?

    - Push: Sends changes on the local to the remote repository.
    - Also puts the file back in the 'unmodified' state, ready to track any new changes made to the files.

[Source](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_2)

***
[Return to Table of Contents](https://hayden-cleaver.github.io/Reading-Notes/)