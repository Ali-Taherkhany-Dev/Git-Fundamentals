# Personal Git Fundamentals Cheat Sheet

1. Git &rarr; Free and open source version control system.
2. Version Control &rarr; The management of changes to docs, computer programs, large web sites, and other collections of information.
3. Branch &rarr; We use branches to have different versions of a project at one time
4. Pull Request (PR) &rarr; A Request to have your code pulled into another branch
5. Stashing &rarr; To stash changes somewhere (not to commit) and retrieve them later
<img src="/images/Github flow versus Local CLI flow.jpg" alt="Workflow" />
<img src="/images/Git branching.png" alt="branching" />

## Terms

- Directory &rarr; Folder
- Terminal/Command Line &rarr; Interface for text commands
- CLI &rarr; Command Line Interface (git karaken)
- CD &rarr; Change Directory
- Code Editor &rarr; Word processor for writing code
- Repository &rarr; Project, or the folder/place where your project is kept
- Github &rarr; A Website to host your repositories online

## Git Commands

- Clone &rarr; Bring a repository that is hosted somewhere like Github into a folder on your local machine
- Add &rarr; Track your files and changes in Git
- Commit &rarr; Save your files in Git
- Push &rarr; Upload Git commits to a remote repo, like Github, Gitlab and 	BitBucket
- pull &rarr; Download changes from the remote repo to your local machine, 	the opposite of push
- init &rarr; To initialize a repository from a ready project
- remote &rarr; To add a reference to the remote repository on Github (remote means somewhere out of the pc)

    ```
    git remote add origin repoLink
    git push origin master
    ```
- -v &rarr; Shows version
- checkout &rarr; To switch between branches (to create a new branch add -b)

    ```
    git checkout -b branch-name
    ```
- branch &rarr; Shows all the branches and points to the current one
- diff &rarr; Compares to versions of code and shows everything that have been changed
- merge &rarr; Not for merging branches into master but master gets updated as you go along, because maybe other people are merging to the master (it's gonna be difficult to merge later)
- ```git branch -d branch-name```

## Hints

- git add . &rarr; commits everything (both modified and created files)
- -m &rarr; means message and you need to have a message in order to commit your changes
- -m &rarr; the next means the description
- -am &rarr; adding and message (only for modified)

## Branches

- Merging Conflict Issue
    - use github
    - use terminal
    - the easiest way is to use vs code (directly)
    - old & new
