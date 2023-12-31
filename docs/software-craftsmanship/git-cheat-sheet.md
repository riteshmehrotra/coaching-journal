---
layout: default
title: Git cheat sheet
nav_order: 4
parent: Software craftsmanship
has_toc: true
---

# Git Cheat Sheet for Beginners

| **Use case**                                | **Command**                                    | **Notes**                                                      |
|---------------------------------------------|------------------------------------------------|----------------------------------------------------------------|
| **Status**                                  ||
| Get current branch status                   | `git status`                                   | Reports branch status against origin, staged or modified files |
| **Stage/Unstage modified files**            ||
| Stage a file                                | `git add <filename>`                           |                                                                |
| Unstage a file                              | `git restore --staged <filename>`              |                                                                |
| Revert changes to modified file             | `git restore <filename>`                       | Use with caution, once reverted git doesn't retain history     |
| Stage all modified files                    | `git add .`                                    | Alterntively use `git add --all`                               |
| Unstage all modified files on a given path  | `git restore --staged <path>`                  |                                                                |
| **Commit/Amend staged files**               ||
| Commit all staged files to local repository | `git commit -m <message>`                      | -m switch is for message                                       |
| Add a missed file to previous commit        | `git add <filename>` <br> `git commit --amend` |                                                                |
