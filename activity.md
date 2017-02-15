# GitHub Workflow Activity


## Form teams

Work with your Project 3 team. If you are in a team of 4, form two 2-person teams.

Assign the following roles to the members of your team. If you are in a team
of 2, then both team members will take turns playing the role of the maintainer.

Roles:

- Maintainer: Creates and maintains a GitHub project.
- Contributor-1: Contributes to the GitHub project created by the maintainer.
- Contributor-2: Contributes to the GitHub project created by the maintainer.

## Overview

In this activity your team will play out several scenarios of concurrent development with GitHub.

## Setup the project

- Create a new team and repository through GitHub Classroom: https://classroom.github.com/group-assignment-invitations/e592a0be645631543daeb5262a857163

## Contributor-1 setup

- Help Contributor-1 to [clone](https://netbeans.org/kb/docs/ide/git.html#clone) the project in NetBeans.

## First contribution

Help contributor-1 to follow the [GitHub flow](https://guides.github.com/introduction/flow/):
- [Create a new branch.](https://netbeans.org/kb/docs/ide/git.html#branchCreate)
- Create a new file `favorite-foods.txt` that contains a couple of contributor-1's
  favorite foods.
- [Add and commit the new file.](https://netbeans.org/kb/docs/ide/git.html#add)
- [Push](https://netbeans.org/kb/docs/ide/git.html#push) the new branch to GitHub.
- On GitHub, [make a pull request](https://help.github.com/articles/creating-a-pull-request/) to pull the new branch into the master branch.

Help the maintainer to [merge contributor-1's pull request](https://help.github.com/articles/merging-a-pull-request/) on GitHub and then [delete the branch](https://help.github.com/articles/deleting-unused-branches/).

Help contributor-1 to switch to their local master branch and [pull changes](https://netbeans.org/kb/docs/ide/git.html#pull) from the remote master. Then, clean up by [deleting the local development branch](https://netbeans.org/kb/docs/ide/git.html#branchDelete).

Congratulations, your team has made its first contribution! Celebrate.


## Contributor-2 setup and second contribution

- Repeat the steps above to have contributor-2 contribute a new file
  `favorite-movies.txt` with a couple of his/her favorite movies.
- Make sure that the maintainer has accepted contributor-2's pull request 
  and contributor-2 has updated their master and cleaned up.

Celebrate again.

## First synchronization

- Contributor-1's clone is out of synch. Help contributor-1 pull changes from the remote master into their local master branch.

Celebrate. But keep it small. Don't worry, there will be bigger celebrations later.


## Contribute conflicting changes

- Have contributor-1 and contributor-2 independently follow the contribution
  workflow to add another favorite food to the end of `favorite-foods.txt`.
- Maintainer, accept one of the pull requests. Try to accept the other. You
  won't be able to because changes in the pull request conflict with the other
  that you already accepted.
- Help the contributor with the unresolved pull request to switch to their local master branch,
  pull changes from GitHub, switch to their development branch, and rebase it relative to the master branch. 
  Then push the development branch to GitHub.
- Maintainer, note that the conflicted pull request is automatically updated and
  should be acceptable. Accept the pull request.
- Have contributors clean up.

Celebrate enthusiastically. That was challenging.


## Multi-round contribution

- Have contributor-1 add another food, and contributor-2 another movie.
- Have the maintainer ask for a modification through the pull-request
  (e.g., "Please pick another flavor. I don't like chocolate.").
- Have contributors make, commit, and push the new changes.
- If the maintainer is satisfied, accept the pull-requests.
- Contributors, don't forget to clean up.

Notice how pull-requests provide a way for a contributor and a maintainer to
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
