# `0x14. MySQL`

This project was done during **ALX SE Studies** at **ALX School**. The end game is to be able to explain to anyone, **without the help of Google**:
* What is the main role of a database
* What is a database replica
* What is the purpose of a database replica
* Why database backups need to be stored in different physical locations
* What operation should you regularly perform to make sure that your database backup strategy actually works

## `Tech`
* Used editors: `vi`, `vim`, and `emacs`
* All files are compiled on Ubuntu 16.04 LTS
* All files end with a new line
* There is a README.md file, at the root of the folder of the project
* All Bash scripts are executable
* Bash script passes `Shellcheck` (version `0.3.7-5~ubuntu16.04.1` via `apt-get`) without any error
* The first line of all Bash scripts are exactly `#!/usr/bin/env bash`
* The second line of all Bash scripts are comment explaining what is the script doing

## `Files`

| Filename | Description |
| -------- | ----------- |
| `Task 0` | Install `MySQL` on both `web-01` and `web-02` servers. |
| `Task 1` | Create a `user` and `password` for both MySQL databases |
| `Task 2` | Create at least one table and one row in your primary MySQL server (web-01) to replicate from in order for you to set up replication |
| `Task 3` | Create a new user for the replica server. |
| `4-mysql_configuration_primary, 4-mysql_configuration_replica` | Setup Replication |
| `5-mysql_backup` | A Bash script that generates a MySQL dump and creates a compressed archive out of it. |

## `Author:`
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
