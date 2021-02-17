# Create, Commit, Checkout Branches with Command Line

## Create a Branch
Create a local respisotry and add fileA.txt. For directions on this step, please see [insert link here]
Before we create a branch, lets check the branches that exist for our project by using the following commands:
```
git branches
git --oneline --graph
```
We should see that the only branch is the master branch. Lets create a new branch called featureX.
To create a new branch, use the following command:
```
git branch featureX
```
To checkout the new branch, run the command:
```
git checkout featurex
```
Lets check our branches, and what branch is currently hecked out. To do this lets run:
```
git branches
git --oneline --graph
```
