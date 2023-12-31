---
layout: default
title: Git cheat sheet
nav_order: 4
parent: Software craftsmanship
has_toc: true
---

# Git Cheat Sheet for Beginners

| **Use case**                                     | **Command**                                    | **Notes**                                                                       |
|--------------------------------------------------|------------------------------------------------|---------------------------------------------------------------------------------|
| **Status**                                       |                                                |
| Get current branch status                        | `git status`                                   | Reports branch status against origin, staged or modified files                  |
| **Stage/Unstage modified files**                 ||
| Stage a file                                     | `git add <filename>`                           |                                                                                 |
| Unstage a file                                   | `git restore --staged <filename>`              |                                                                                 |
| Revert changes to modified file                  | `git restore <filename>`                       | Use with caution, once reverted git doesn't retain history                      |
| Stage all modified files                         | `git add .`                                    | Alterntively use `git add --all`                                                |
| Unstage all modified files on a given path       | `git restore --staged <path>`                  |                                                                                 |
| **Commit/Amend staged files**                    |                                                |
| Commit all staged files to local repository      | `git commit -m <message>`                      | -m switch is for message                                                        |
| Add a missed file to previous commit             | `git add <filename>` <br> `git commit --amend` |                                                                                 |
| **Working with remote branch**                   |                                                |
| Check remote repositories names                  | `git remote -v`                                | Shows name with url  and permissions                                            |
| Clone a remote repository                        | `git clone <url>`                              |                                                                                 |
| Add a remote branch                              | `git remote add <remote_name> <url>`           |                                                                                 |
| Fetch from remote branch                         | `git fetch`                                    | Fetches data from remote server, but doesn't merge with any local modifications |
| Fetch and automatically merge with remote branch | `git pull`                                     |                                                                                 |
| Push to remote branch                            | `git push <remote_name> HEAD:<branch_name>`    |                                                                                 |
| Rename a remote branch                           | `git remote rename <current_name> <new_name>`  |                                                                                 |
| Remove a remote branch                           | `git remote remove <branch_name>`              |                                                                                 |
| **Branching**                                    |                                                |                                                                                 |