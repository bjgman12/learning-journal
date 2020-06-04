## Git vs Github notes

## Version Control

< Version control is a system that logs versions of a file or set fo files and allows you to revert to previous states.

< Centralized Version Control systems entailed a single server storing all changes and file version allowing all versions to to be accesed by multiple clients

< Distributed Version Control systems allows clients to create mirrored repositories to circumvent a single server side point of failure

< **Git** is a **DVCS** that stores data in a file system made up of **Snapshots**. Git created a snapshot of the file and stores a reference to it.

- Local Git repositories have three components

1. Workign directory: the actual files are here
1. Index: The area used for staging
1. Head: points to the most recent commit

## Staging Files

- **git add*** to track all files
  - **git add filename** to tracka specific file.
- **git status** tos ee information regarding changes
- **git commit -m "insert comment on change"** to commit changes
- **git commit -a** to commit all changes to tracked files

## Remotes

- **git remote** will show short names of all specified remote handles
- **git remote -v** will display all remote URLs next to their short names
- **git remote add shortname url** will create a new remote repository

## Pushing Changes

- **git push [remote-name] branchname**
- **git push origin master** will push changes to a remote repository.
- **git fetch [remote-name]** will fetch changes so if you fetch from origin it will pull any updates pushed since last fetch.
- **git pull origin master** pulls changes.

## Renaming and removign remotes



### Change stashing

- **git stash** will remove changes and hide them until **git stash apply** is used.

### Repository cloning

- "origin" is given to server cloned from by default "master" to local branch
## Vocabulary
- VCS Version Control Systems
- Git vs GitHub
- local vs remote
- clone
- commit Git creats a snapshot of the file and stores a reference to it.
- ACP
- Deployment
