
# Tips and tricks for contributing to project  "joomla-german"

following text are intended for use in a wiki and will be on different pages

joomlagerman/joomla

https://github.com/joomlagerman/joomla/


# Contributing 


## Setting up fork and upstreams

### Fork the repository

[WIP] fork image from git hub ...

short summary of following 


see https://help.github.com/en/github/getting-started-with-github/fork-a-repo

### Setup the upstream


### fetch / create the mirror branches

Master will be taken by fork action

#### Create local mirror branch

git checkout -b <new branch> upstream/<remote branch>

git checkout -b 4.0-dev upstream/4.0-dev






see https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork

## Preparing for changes

### Syncing the branches

----------------------------------------
### example update fork - master
git fetch upstream

git checkout master
git merge upstream/master

git push

---------------------------------------
### example update fork - 4.0-dev

git fetch upstream

git checkout 4.0-dev
git merge upstream/4.0-dev
git push


con tributing üsteps


## selecting an issue

? [WIP] in front ?
? [3.9] ? nur in 3.9

? [4.0]


## Creating a branch for issue

#### branch in local directory

git fetch upstream

1) checkout starting branch

Wann master, wann ... dev... branch ? 3.x dev still used

git branch <name>
git checkout <name>

oder in einem 

git checkout -b <name>

##### branch in worktree


##### remove accidental created worktree

delete worktree folder

git worktree prune


## pull requests

* naming

https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests




### remove branch after pull request is accepted

In github source repository select branches 
your branches / active branches

Use the wast basked symbol behind the pull branch to delete this branch
you may have to delete it on the PC too

? pull deletes reference
? Delete folder if on worktree

# Tip and Tricks 

## Vereinbarungen

### Wann wird welches Wort verwendet

### 


