# Tutorial & gitFlow

## Repository
* A repository is a file location where you store all the files that relate to your project.
* - **Local Repository:** Local repository is a folder on your machine which contails files, folders and code that you used for your project.
* - **Remote Repository:** A remote repository is located in a remote location ie the web. A good example of remote repository is Github.

------------
## Clone
* Git clone is a git command which created a copy of a targeted repository in your local machine
![Before](/images/BeforeGitClone.png)
![After](/images/AfterGitClone.png)
------------
## Fork
* Fork is similar to clone. A fork is a copy of repository on which we can make changes without changing the original repository. Unlike clone, a forked repository does not exist on your local machine, it would exist on webserver like Githubs webserver.
------------
## Branch
* In git you can create different branches. It can be thought of as a parallel version of the project where you can safely make changes without interfering in other people codebase. Once the development is completed in the diverged branch is can be merged back with the original or master branch.
![After](/images/Branch.png)
* As you can see in the image, B2 is a different branch and master is different.
------------
## Commit
* A commit is a change in a file or set of files. Git detects the change through a unique id or a hash. Commit keeps track of what changed and by who along with a message that summarizes the changes.

![Before](/images/BeforeCommit.png)

**git commit -m "Feature 2 added"**

![After](/images/AfterCommit.png)
------------
## Merge
* In git, the merge command lets you combine 2 branches and integrate them into a single branch, applying changes from both branches.

![Merge](/images/Merge.png)

* While merging, conflicts can occure caused by change in same line or in the same content of a file in both branches. You can resolve this issue by either making changes in your local repository or picking one of the two conflicting version and apply the changes.
------------
## Checkout
* The command git checkout lets you switch and select different branches, created by git branch, for commits or merges.
------------
## Push
* The push command is used to upload contents of your local repository to a remote repository along with the commits. using the git push command your commit and changes are uploaded to Github

![Before](/images/BeforePush.png)
![After](/images/AfterPush.png)
