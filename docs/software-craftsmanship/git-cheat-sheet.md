| **Use case**                               | **Command**                       | **Note**                        |
|--------------------------------------------|-----------------------------------|---------------------------------|
| **Stage/Unstage modified files**           ||
| Stage a file                               | `git add <filename>`              |                                 |
| Unstage a file                             | `git restore --staged <filename>` |                                 |
| Stage all modified files                   | `git add .`                       | Alterntively use `git add --all` |
| Unstage all modified files on a given path | `git restore --staged <path>`     |                                 |
| **Commit/Amend staged files**              ||
| Commit all staged files                    | `git commit -m <message>`         | -m switch is for message        |
