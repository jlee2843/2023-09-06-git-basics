# DSCI 521: Lecture 3 

#### Git Command Basics
- `init`: turns the current folder (working directory) into a Git repository.
      - Type this ONLY ONCE per folder structure. 
- `status`: tells you what's going on with git in your current repository.

- `add <FILE(S)`: add the files into the staging area. 
- `commit`: commit (i.e., snapshot) the files from the staging area.

- Let's make a change!

- `log`: shows the log.
    - `log --oneline`: shows the log in condensed format.
    - This may open a terminal program called `less` that lets you **scroll**. Use `q` to quit.

- `diff`: Shows the difference between your changes and the last known **git status**. 
      - `diff --staged`: shows you the difference of the files in the staging area. 

- `restore --staged <FILE>`: Unstages <FILE> from the **staging area**.

-`revert <SHA1 (Hash)>`: undos the changes in the commit specified in SHA1.