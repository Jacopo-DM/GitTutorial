# Git Cheatsheet

Here is a summary of all the Git commands we will be using in this tutorial.


## One Time Setup

### Configuring Git

```bash
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
```

### Generating an SSH Key

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
cat ~/.ssh/id_ed25519.pub
```

## On a New Project

### Initializing a New Repository

```bash
git init
```

### Adding a Remote Repository

```bash
git branch -M main
git remote add origin REPOSITORY_URL
git push -u origin main
git config pull.rebase false
```


### Cloning a Repository

```bash
git clone REPOSITORY_URL
```

## On an Existing Project


### Checking the Status of Your Project

```bash
git status
```

### Adding Files to the Staging Area

```bash
git add FILENAME # Adds a single file
git add * # Adds all files (works with new files too, not recommended)
git add -u # Adds all modified files (works with deleted files too, but not new files)
git add . # Adds all files (recommended)
```

### Removing Files from the Staging Area

```bash
git rm FILENAME
```
### Restoring Files from the Staging Area

```bash
git restore --staged FILENAME # After normal removal
git restore FILENAME # After "git rm FILENAME"
```

### Committing Changes

```bash
git commit -m "Commit message"
```

### Pushing Changes

```bash
git push
```

### Pulling Changes

```bash
git pull
```
