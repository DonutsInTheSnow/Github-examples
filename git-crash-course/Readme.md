## Git Hidden Folder

There is a hidden folder called `.git` which tells you that your project is a git repo.

If we wanted to create a git repo in a new project we'd create the folder and then initialize that repo using `git init`
```
mkdir /workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch Readme.md
code Readme.md
git status
# make changes to readme.md
git add .
```

## Cloning

There are 3 ways to clone: HTTPS, SSH and Github CLI

Since we're using Github Codespaces we'll create a temporary directory in our workspace
```sh
mkdir /workspace/tmp
cd /workspace/tmp
```

### HTTPS
```sh
git clone https://github.com/DonutsInTheSnow/Github-examples.git
cd Github-examples
```

## Commits

## Branches

## Remotes

## Stashing

## Merging
