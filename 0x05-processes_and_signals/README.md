# 0x05. Processes and signals

This project was done during **ALX SE Studies** at **ALX School**. The end game is to learn about PID, processes, and commands that handle them (`ps`, `pgrep`, `pkill`, `kill`, etc) in **Bash**.

## Apparatus
* Used `vi`, `vim`, and `emacs` as editor
* All files are interpreted/compiled on Ubuntu 20.04 LTS
* All files end with a new line
* A `README.md` file, at the root of the folder of the project
* All Bash script files are executable
* All Bash scripts passed `Shellcheck` (version `0.7.0` via `apt-get`) without any error
* The first line of all your Bash scripts is exactly `#!/usr/bin/env bash`
* The second line of all Bash scripts are comments explaining what is the script doing

## Files

| Filename | Description |
| -------- | ----------- |
| `0-what-is-my-pid` | Displays its own PID |
| `1-list_your_processes` | Displays a list of currently running processes |
| `2-show_your_bash_pid` | Displays lines containing the `bash` word in a list of currently running processes |
| `3-show_your_bash_pid_made_easy` | Displays the PID, along with the process name, of processes whose name contains the word `Bash` |
| `4-to_infinity_and_beyond` | Displays `To infinity and beyond` indefinitely |
| `5-dont_stop_me_now` | Stops `4-to_infinity_and_beyond` process |
| `6-stop_me_if_you_can` | Stops `4-to_infinity_and_beyond` process |
| `7-highlander` | Displays `To infinity and beyond` indefinitely with a `sleep 2` in between each iteration and displays `I am invincible!!!` when receiving a `SIGTERM` signal |
| `8-beheaded_process` | Kills the process `7-highlander` |
| `100-process_and_pid_file` | Prints some messages according to sent signals |
| `101-manage_my_process, manage_my_process` | Init script that manages `manage_my_process` with `start`, `stop`, and `restart` instructions |
| `102-zombie.c` | C program that creates 5 zombie processes |

## Author:
### Gideon Selorm Attakpah: [GitHub](https://github.com/iamgideonchrist) - [Twitter](https://twitter.com/iamgideonchrist) - [Linkedin](https://www.linkedin.com/in/iamgideonchrist/)
