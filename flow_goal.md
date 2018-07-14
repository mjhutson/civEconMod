GitHub allows for multiple versions of a program to be modified by the members
of a team. The Branches are different versions. Cloning a repository creates
a copy on your machine. Pulling gets the latest version of the branch. Pushing
sends your latest to the branch. Merging combines branches.

The ideal flow for this would be that you work on a component in your local
branch, usually named after the component you're developing, and then you merge
it into the dev branch when it is complete. When a feature is complete in dev it
can be sent to testing, and if it works then to master. Once every feature has
been tested and merged into master that branch will be the completed mod.

Test