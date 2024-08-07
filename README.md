# GitHub-Documentation

#### Clone the repository:
   ```sh
   git clone [your repository link]
```
## Create first time code push

#### Initialize Git:
```sh
   git init
```

#### Add Remote Repository:
```sh
git remote add origin [your repository link]
```

#### Add all Files:
```sh
git add .
```

or Add specific file:
```sh
git add [your file name]
```

#### commit file:
```sh
git commit -m "[your commit name]"
```

#### code push:
```sh
git push -u origin master
```
## second time code push:
```sh
git add .
git commit -m "Describe your changes"
git push
```

## Branch commends:
#### Create a new branch
```sh
git branch new-branch-name
```

#### Switch to the new branch
```sh
git checkout new-branch-name
```

#### Create and switch to a new branch
```sh
git checkout -b new-branch-name
```

#### Push the new branch to the remote repository
```sh
git push -u origin new-branch-name
```

#### List all branches
```sh
git branch -a
```

#### Switch to an existing branch
```sh
git checkout existing-branch-name
```

#### Merge a branch into the current branch
```sh
git merge feature-branch
```

#### Delete a local branch
```sh
git branch -d branch-name
```

#### Delete a remote branch
```sh
git push origin --delete branch-name
```
## The .gitignore file:
#### Ignore a specific file:
```sh
secret.txt
```
#### Ignore all files
```sh
*.log
```

#### Ignore a specific directory:
```sh
/build/
```
### Example .gitignore File:
```sh
# Node.js dependencies
/node_modules

# Logs
logs
*.log
npm-debug.log*

# Directory for temporary files
/tmp

# OS generated files
.DS_Store
Thumbs.db

# Build directory
/build

# Environment variables
.env

# Editor-specific files
*.swp
.idea/
.vscode/

# Ignore all .txt files but include README.txt
*.txt
!README.txt
```
## Synchronize changes
#### Push Changes
```sh
git push origin main
```
#### Pull Changes:
```sh
git pull origin main
```
#### Create a New Branch:
```sh
git checkout -b feature-branch
```
## Usefull commends:
#### reset your commit or added:
```sh
git reset
```
#### Force Push if Necessary:
```sh
git push --force origin branch-name
```

## Make changes
#### Lists version history:
```sh
git log
```

#### changes of the specified commit:
```sh
git show [commit id]
```

#### differences between two branches:
```sh
git diff <first-branch id>...<second-branch id>
```

## Additional Git Commands:
#### Displays the state
```sh
git status
```

####  List all branches
```sh
git branch
````
#### Merges the specified branch’s history into the current branch
```sh
git merge <branch-name>
```
#### emporarily stores all the modified tracked files
```sh
git stash
```
#### Restores the most recently stashed files
```sh
git stash pop
```
#### Show changes introduced in a specific commit:
```sh
git show [Your commit id]
```
#### View the history of a specific file
```sh
git log --follow [your directory of filename]
```


##

## Thanks for reading github commenline commends. 🙂

