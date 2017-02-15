# GitHub Workflow Activity


## Form teams

Work with your Project 3 team. If you are in a team of 4, form two 2-person teams.

Assign the following roles to the members of your team. If you are in a team
of 2, then each team member will play the role of maintainer for the other's contributions.

Roles:

- Maintainer: Creates and maintains a GitHub repository.
- Contributor-1: Contributes to the GitHub repository created by the maintainer.
- Contributor-2: Contributes to the GitHub repository created by the maintainer.

## Overview

In this activity your team will play out several scenarios of concurrent development with GitHub.

## Setup the project

- Help the maintainer to create a new team and repository through GitHub Classroom. Do not join my TEST team.
https://classroom.github.com/group-assignment-invitations/e592a0be645631543daeb5262a857163

## Contributor-1 setup

- Help Contributor-1 to [clone](https://netbeans.org/kb/docs/ide/git.html#clone) the repository in NetBeans. It is pre-populated with a basic NetBeans project named Favorites.

## First contribution

Help contributor-1 to follow the [GitHub flow](https://guides.github.com/introduction/flow/):
- [Create a new development branch.](https://netbeans.org/kb/docs/ide/git.html#branchCreate)
- Edit Main.java to make the main method print out a few favorite foods.
- [Commit](https://netbeans.org/kb/docs/ide/git.html#committing) the changes.
- [Push](https://netbeans.org/kb/docs/ide/git.html#push) the new branch to GitHub.
- On GitHub, [make a pull request](https://help.github.com/articles/creating-a-pull-request/) to pull the new branch into the master branch.

Good GitHub practice: *Never merge your own pull request.* Another team member should review your code.

Help the maintainer to [merge contributor-1's pull request](https://help.github.com/articles/merging-a-pull-request/) on GitHub and then [delete the branch](https://help.github.com/articles/deleting-unused-branches/) on GitHub.  

Help contributor-1 to switch to their local master branch and [pull changes](https://netbeans.org/kb/docs/ide/git.html#pull) from the remote master. Use the **Team > Remote > Pull...** dialog, click **Enable Deletes**, and allow it to delete the local clone of the remote development branch.

Then, clean up by [deleting the local development branch](https://netbeans.org/kb/docs/ide/git.html#branchDelete).

Congratulations, your team has made its first contribution! Celebrate.


## Contributor-2 setup and second contribution

- Repeat the steps above to have contributor-2 add a few of their favorite foods to the main method of the Main class.
- Make sure that the maintainer has accepted contributor-2's pull request and contributor-2 has updated their master and cleaned up.

Celebrate again.

## First synchronization

- Contributor-1's clone is out of synch. Help contributor-1 pull changes from the remote master into their local master branch.

Celebrate. But keep it small. Don't worry, there will be bigger celebrations later.


## Contribute conflicting changes

- Have contributor-1 and contributor-2 independently follow the contribution
  workflow to add one more favorite food to the end of the main method.
- Have the maintainer accept maintainer-1's pull request. Try to accept contributor-2's pull request. You
  won't be able to because changes in the pull request conflict with the other
  that you already accepted.
- Help contributor-2 switch to their local master branch,
  pull changes from GitHub, switch to their development branch, and rebase it relative to the master branch. 
  *I have been having a difficult time figuring out how to do this in NetBeans.  Call me over when you get here.*
  Once the development branch is rebased, commit the changes and push to GitHub.
- Maintainer, note that the conflicted pull request is automatically updated and
  should be acceptable. Accept the pull request.
- Have contributors clean up their extra branches.

Celebrate enthusiastically. That was challenging.


## Refactoring

- Have contributor-1 and contributor-2 independently follow the contribution workflow to make the following changes:
    - Have contributor-1 add another food to the main method.
    - Have contributor-2 make a new static method, movies(), that prints favorite movies. Also move the code to print favorite foods from the main method into a new static method, foods(). Modify the main function to call both methods (and do nothing else).
- Have the maintainer accept maintainer-2's pull request. Try to accept contributor-1's pull request. You
  won't be able to because changes in the pull request *really, really* conflict with the other that you already accepted.
- Have contributor-1 pull changes from GitHub into their master branch and rebase their development branch as described above. Then revise the code to put the new favorite food into the new foods() method with the others.  Commit and push the changes.
- Have the maintainer accept contributor-2's updated pull request.

Celebrate wildly. That was even more challenging.


## Multi-round contribution

- Have contributor-1 add another food to the foods() method.
- Have contributor-2 add another movie to the movies() method.
- Have the maintainer ask for a modification through the pull-request
  (e.g., "Please pick another flavor. I don't like chocolate.").
- Have contributors make, commit, and push the new changes.
- If the maintainer is satisfied, accept the pull requests.
- Contributors, don't forget to clean up.

Notice how pull-requests provide a way for team members to
communicate about a proposed change. Also notice how the pull-request updates
automatically as new changes are pushed to the same branch.

## Squash

- Repeat the multi-round contribution until both contributors have made multiple
  commits.
- Maintainer, through the pull-request, ask contributors to squash their work
  into a single commit.
- Help contributors to [squash their commits](http://gitready.com/advanced/2009/02/10/squashing-commits-with-rebase.html) into a single   commit and push it. (Note you will have to use the command line.  NetBeans does not yet provide support for squashing commits.)
- Maintainer, accept the pull-requests once it contains the same work, but only
  a single commit.
- Contributors, don't forget to clean up.

This is another moment for an enthusiastic celebration. Well done!  

## Your sandbox

Troubles with Git?  The repository you created today is a safe place for trying new things.  Let me know if you have a scenario you want help figuring out.

## Copyright and Licensing

Copyright 2016 Darci Burdge and Stoney Jackson; 2017 Janet Davis SOME RIGHTS RESERVED

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ .
