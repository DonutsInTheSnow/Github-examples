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
git add Readme.md
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

## Reset
Reset allows you to convert Staged changed back to Unstaged. It's for when you don't want to commit all files with the `git add .` command.
```
git add .
git reset
```
> `git reset` will revert a `git add .`

## Gitconfig file
The gitconfig file is what stores your global configurations for git such as email, name, editor and more.

Show contents of .gitconfig file
```
git config --list
```

When you first install Git on a machine you are supposed to set up your name and email
```sh
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```
