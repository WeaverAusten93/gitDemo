# Cmds

...
git init                                                # turn this folder into a repo (initializes)
git add<filename>                                       # adds one file to the stage
git add -A                                              # Add all changed, created, and deleted files to the stage
git commit -m '<msg>'                                   # commit once staged
git branch                                              # list of branches and ehats chekckout with a *
git checkout -b <branchname>                            # Creates new local branch (if not there)

git merge <branchname>                                  # merges other branch to the one currently checked out
git checkout <branchname>                               # Change to the branch

git log                                                 # Show commit history
clear                                                   #clean up ui of terminal

git remote add <origin> <url>                           # Add a new remote, connect to github
git push origin <branchname>                            # Sync up to github, any branch
git pull origin <branchname>                            # Sync down from github to local and merging

git reset --hard <id or tag version>                    # Go back in time to id/tag number
git tag -a '<version>' -m '<msg>'                       # Tag the current commit of the current branch
git push origin -- tags                                 # Tags push seperate
...