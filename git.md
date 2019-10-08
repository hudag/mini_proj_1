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
------------
## Pull
* The git pull command downloaded content from the remote repository and updates the local repository and also merges them. The pull command is a combination of git fetch(download data from remote repository) and git merge.

![Before](/images/BeforePull.png)
![After](/images/AfterPull.png)
------------
## Remote Add
* The remote add command creates a new remote repositoy so you dont have to clone before you start commiting and pushing. Example: You start in your local machine, create a new repository (on Github) using remote add, commit and push.
------------
## Remote Remove
* The git remote rm command removes the remote repository and its references from your local repository. It does not delete the remote repository from the server.
------------
## Remote Show
* Remote Show command shows information about the remote repository and its branches. It can show you which branch you would automatically push to while your on a certain branch as well as show you which branch is removed in remote repository or which branch you do not currently have. It can also show you which local branches would merge if you perform a git pull.
------------
## Status
* The command git status shows which files had their contents changes and which of those files are added to stage for the next commit.
------------
## Master Branch
* Master branch in a permanent main working branch. Every time you commit, the master branch pointer moves forward automatically. All other branches such as Delopment and/or bug fix branch eventually end up merging with the master branch as the project comes to an end is ready to be deployed and released.
------------
#####Now that we are familiar with all the terms, lets see how gitFlow works :)
------------

#gitFlow

#Benefits
## Parallel Development
* One of the great things about GitFlow is that it makes parallel development very easy, by isolating new development from finished work. New development (such as features and non-emergency bug fixes) is done in feature branches, and is only merged back into main body of code when we are sure all the features are good and tested that the code is ready for release. You can work on different tasks by creating multiple branches.

## Collaboration
* Feature branches make it easier for multiple developers to work on the same feature. Developers commit the changes which are necessary to make the feature functional. This makes it very easy for the developers to see and follow each others changes hence collaboration.

## Release Staging Area
* As new developments in the branch are completed, it gets merged back into the develop branch. So when the next release is branched off of develop, it will automatically contain all of the new feature that have been finished.

## Emergency Fixes
* GitFlow supports hotfix branches, branches made from a tagged release. You can use these to make an emergency change, safe in the knowledge that the hotfix will only contain your emergency fix. There is no risk that you will accidentally merge in new development at the same time.

------------

# Procedure
1. New development (new features, non-emergency bug fixes) are built in feature branches.

![Step1](/images/GitFlowFeatureBranches1.png) 

2. Feature branches are branched off of the develop branch, and finished features and fixes are merged back into the develop branch when they’re ready for release.

![Step2](/images/GitFlowDevelopBranch2.png) 

3. When it is time to make a release, a release branch is created off of develop.

![Step3](/images/GitFlowReleaseBranch3.png) 

4. When the release is finished, the release branch is merged into master and into develop too, to make sure that any changes made in the release branch aren’t accidentally lost by new development. The only commits to master are merges from release branches and hotfix branches.

![Step4](/images/GitFlowMasterBranch4.png) 

5. Hotfix branches are used to create emergency fixes.

![Step4](/images/GitFlowHotfixBranch5.png) 

------------

**Summary:** Multiple branches are created off of the Master branch, some for features and some for bug fix and such. These other branches are also split into multiple branches such as, planned feature and future features have different branches. As we get closer to the release the branches start to merge, features are tested and released, and bug fixes are implemented. In the end these Branches merge with the Master branch for the final release.
