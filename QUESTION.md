# Git Challenge: Remote Work Tree Isolation

This challenge tests your knowledge of advanced Git environment variables.

## Goal
Find the single command that allows you to run 'git status' successfully, even though your repository's metadata (database) and its project files (work tree) are physically separated on the file system.

## The Environment (The Paths Exist on the Solver's Machine)
* **You are sitting in:** /home/scripts (irrelevant location)
* **Repository Metadata (GIT_DIR):** /data/repo.git
* **Project Files (GIT_WORK_TREE):** /www/html/

## Task
Show the exact shell command that sets the two necessary environment variables and executes 'git status' correctly.

## Flag Format
The solution format is the required command itself (e.g., GIT_VAR=path GIT_OTHER_VAR=other_path git command).
