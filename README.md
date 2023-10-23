- [Git Commands](#git-commands)
- [Linux Commands](#linux-commands)
- [SSH Key to PEM](#ssh-key-to-pem)

# Git Commands

- `git init`  
  create new Git repository.

- `git status`  
  display state of the working directory and staging area.

- `git clone [remote-repo-link]`  
  clone repository from Github to local.

- `git add [file]`  
  add files to staging.

- `git commit -m "[message]" -m "[description]"`  
  create snapshots of the project along the timeline of a Git project.

- `git commit -am "[message]"`  
  git shortcut for add all and commit changes.

- `git push`  
  upload files from locat repository to remote.

- `git push origin [branch-name]`  
  push files to a specific branch.

- `git push -u origin [branch-name]`  
  push files to a specific branch and set the branch as default push location.

- `git remote add origin [remote-repo-link]`  
  centralises local to remote repository.

- `git remote -v`  
  shows remote repositories that is connected to the local repository.

- `git branch`  
  identify branches and current branch.

- `git checkout [branch-name]`  
  change current branch.

- `git checkout -b [branch-name]`  
  create and move to newly created branch.

- `git branch -D [branch-name]`  
  delete branch locally. (if not merged)

- `git branch -d [branch-name]`  
  delete branch locally.

- `git push origin --delete [branch-name]`  
  delete branch remotely.

- `git diff`  
  shows all of the changes made in the files.

- `git diff [branch-name]`  
  shows all changes made between 2 branches.

- `git pull`  
  pull latest changes from github.

# Linux Commands

- `cd [directory-name]`  
  change directory.

- `cd ..`  
  change to previous directory.

- `mkdir [directory-name]`  
  create new directory.

- `rmdir [directory-name]`  
  delete empty directory.

- `rm -r [directory-name]`  
  delete directory and all contents.

- `rm -rf [directory-name]`  
  delete directory and all contents (yes to all prompts).

- `ls`  
  list all files.

- `ls -a`  
  list all files (including hidden).

- `touch [file-name]`  
  create file.

# SSH Key to PEM

1. You need to generate an SSH Key from the server.
2. after generation an SSH Key, you need to install [PUTTY](https://formulae.brew.sh/formula/putty) (See link for homebrew installation) or using the terminal, enter `brew install putty` (if you have homebrew installed).
3. after installing, you need to convert your SSH key to a PPK file. go to the directory where the key is located and enter command: `puttygen [keyname] -o keyname.ppk`. It will now generate a PPK file.
4. 